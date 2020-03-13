'ues strict'  : 开启严格模式 , 定义变量需要let 声明 开头
+ - * / 加减乘除
% 求余
== 相等     != 不等 ;比如说1 == "1",成立,仅仅判断字面是否相等
=== 全等    !==全不等;全等判断严格,判断内存是否相对

if(条件a="123"){
    执行代码;
}else if (条件二a="321"){
    执行代码;
}else{
    执行代码;
}

&& :and 条件全为真即可输出真
|| :or 有一个为真即可输出真

while(事件){         :事件为真,就一直执行循环,必须要有跳出机制,可以在事件里判断 
    继续执行;       :事件为0时,返回false,例如while(--100){}
    if(条件){
        berak;//    :跳出循环,终止当前循环
    }
}
console.log("字符"+变量+"字符")
变量++;   :自身加1
变量+=2     :自身加二
--变量;     :自身减一,符号先后影响运行顺序
循环里的 执行代码 如果只有一条就不需要大括号{}

for(let 开始 = 0;开始 < let 结束 ; 开始++>){}     :专门为循环多少次设计的

    if(开始=1)
        continue;       :跳过这次循环,继续循环
        berak;//    :跳出循环,终止当前循环

function 方法名(){      //函数的作用是代码封装,函数内的变量不可以被函数外面调用
    执行内容
};
window.a=1;  全局变量,可以夸窗口使用
let 只能在当前页面使用

一个函数只能用一个return

数组.forEach()   循环数组每一个元素

每隔毫秒循环执行函数
setInterval(function () {},毫秒)


获取类为border的元素
let a = document.querySelector(".border");


返回text的style样式,传入透明度==1参数.
let elementStyle = getComputedStyle(text).opacity == 1;

替换设置text2的文字内容
text2.innerText = text3;


设置text的透明度
text.style.opacity = 0;

display:inline-block; 设置行内块元素