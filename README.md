## 工业物联网公司
1、请指出$.extend(obj)和$.fn.extend(obj)的区别?

2、你如何对网站的文件和资源进行优化?

3、请谈一下你对网页标准和标准制定机构(W3C)重要性的理解?

4、data-属性的作用是什么?

5、请描述一下cookies，sessionStorage和localStorage的区别?

6、你熟悉SVG样式的书写吗?

7、position属性的值及其用法、区别?

8、document.ready和window.onload两个事件的区别?

9、==和===有什么不同?

10、解释一下js的同源策略?

11、js里函数参数arguments是数组吗?

12、下面代码会在console输出什么？为什么？

```js
var xxx = {
    foo: 'bar',
    func: function () {
        var self = this
        console.log(this.foo)
        console.log(self.foo)
        (function () {
            console.log(this.foo)
            console.log(self.foo)
        })
    }
}
xxx.func()
```
13、下面两个函数的返回值是什么？为什么？
```js
function foo1() {
    return {
        bar: "hello"
    }
}
function foo2() {
    return
    {
        bar: "hello"
    }
}
```
14、在下面的代码中，数字1-4会以什么顺序输出？为什么？
```js
(function () {
    console.log(1)
    setTimeout(function () {
        console.log(2)
    }, 1000)
    setTimeout(function () {
        console.log(3)
    }, 0)
    console.log(4)
})()
```
15、哪条语句会产生错误?
```js
A. var a = ()
B. var b = []
C. var c = {}
D. var d = //
```

## 企业移动营销服务商
1、html中Doctype的作用?

2、块级元素有哪些？行内元素有哪些？请分别写出3个。（还有一家没拍照，是叫我写5个以上块级、内联、空元素）

3、什么是css的盒模型？它包含什么元素？和它相关的css属性是哪个?

4、css选择符有哪些？哪些属性可以继承？优先级算法如何计算？css3新增伪类有哪些？

5、如何居中div，如何居中一个浮动元素？

6、请写出几个常用的css hack技巧?

7、`<meta http-equiv="X-UA-Compatible" content="ie=edge">`的作用是什么?

8、一个页面有大量的图片，加载很慢，你有哪些办法优化这些图片的加载?

9、有什么办法能让移动端显示的页面自适应不同尺寸的手机屏幕（我感觉现在用vw方案较好）?

10、代码题，手机上给我看的，一般都是关于作用域、this、log之类的。

## 常问问题

1、你是如何自学的，为什么转行？

2、你有什么想问我的

3、你的缺点和优势？

4、讲一下原型链

5、讲一下面向对象

6、讲一下闭包

7、web性能优化

8、谈谈你对vue的理解（还有个问我vue的原理，哭）


## 其他
目前就这两家拍了照，其他的有些没做笔试，之后面试的题目我会补充上来。

ps：还有个去泰国做y网站的，说的是有出国深造的机会，笑哭，给再多也不去啊，
