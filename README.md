# animate.css-WOW.js

animate.css+WOW.js组合使用，可以轻松实现各种动画效果

- [animate.css官网:](https://daneden.github.io/animate.css/)
- [WOW.js官网:](http://mynameismatthieu.com/WOW/)
- [组合项目效果演示:]()

## 基本用法

- 引入animate.css

```html
	<link rel="stylesheet" href="./animate/animate.css">
	<script src="./wow/js/wow.min.js"></script>
```

- 引入wow.js

```html
	<script src="./wow/js/wow.min.js"></script>
```

- 初始化wow.js

```javascript
	<script>
	    // new WOW.init();
	    var wow = new WOW({
	        boxClass: 'wow',	//需要执行动画的元素的 class
	        animateClass: 'animated',	//animation.css 动画的 class
	        offset: 0,			//距离可视区域多少开始执行动画
	        mobile: true,		//是否在移动设备上执行动画
	        live: true,			//异步加载的内容是否有效
	    });
	    wow.init();
	</script>
```

- 页面使用方法

```html
	<div class="wow animated fadeIn">
        <span>fadeIn</span>
    </div>
```

## 本次学习只是简单的介绍animate.css和WOW.js的组合使用

- 如控制动画的执行时间、距离、和重复次数，需自行查阅相应的文档

## 开发人员

由Matthieu Aussaguel开发，[mynameismatthieu.com](http://mynameismatthieu.com)

+ [@mattaussaguel](//twitter.com/mattaussaguel)
+ [Github的简介](//github.com/matthieua)

## 贡献者

感谢迄今为止为该项目做出贡献的所有人：

- Attila Oláh - [@attilaolah](//twitter.com/attilaolah) - [Github Profile](//github.com/attilaolah)
- [和许多其他人](//github.com/matthieua/WOW/graphs/contributors)
由[Vincent Le Moign](//www.webalys.com/)发起并设计，[@ webalys](//twitter.com/webalys)

学习引自：

- [daneden](https://github.com/daneden/animate.css)
- [Paulo-Sergio](https://github.com/Paulo-Sergio/Animated.css-and-WOW-master)