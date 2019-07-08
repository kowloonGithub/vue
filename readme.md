VUEjs实战

data可以是一个对象
生命周期：
    created：未挂载，初始化数据
    mounted:el挂载，一般第一个业务逻辑
    beforeDestory:实例销毁之前，解绑一些应用

插值{{}}

v-link绑定 输出是html
v-model绑定 输出的是纯文本

v-pre标签不会被编译，显示的仍然是{{}}

{{}}内部可以是表达式

v-bind更新html元素上的属性
v-on 绑定事件监听器

语法糖：v-bind可以省略,v-on可以用@表示

计算属性:类似method，只要其中任何一个方法更新了，计算属性就会被执行。
计算属性缓存：依赖的属性变化时，就会重新取值。method则重新渲染的时候才会执行

class绑定的方法:数组，计算属性，对象
v-bind:style  :style绑定内联样 直接写，对象，对象名
v-cloak:防止显示变量名： 和display：none配合使用
v-once只渲染一次
v-if v-else-if v-else
v-show 为false表示隐藏元素,类似display:none
v-for:"(book,index) in books"

数组更新:通过索引设置项/修改数组长度 不会触发视图的更新
    set
    slice

计算属性来返回过滤或者排序后的数组，不会对原数组有改动

方法与事件on method 点击事件

修饰符：.stop ...

表单控件 v-model  @input代替时：会实时的更新

单选时，checked=true
组合单选时候 v-model = value时选中

修饰符：v-model.lazy .number .trim

组件,注册+使用
使用components属性来进行组建注册


使用props传递数据,接受父组件的message数据

单项数据流：data域可以将父组件的数据处理后再给子组件

数据验证：限定组件传值的类型

父子组件通信：
兄弟组件通信：
跨级组件通信：

自定义事件：$emit 子组件向父组件通信

非父子组件通信：dispatch（向上级派发事件） broadcast

this.$parent  this.$children 用于访问父子组件

使用slot分发内容
props传递数据，events触发事件，slot内容分发构成了vue的三个api来源。
理清什么是父组件，什么是子组件（内侧是子组件）

单个slot
有名字slot
作用域插槽：

动态组件：切换组件的值
异步组件：setTimeout延时渲染

&nextTick：DOM更新完成后执行函数
X-template：不用再拼凑template了

8：自定义指令
注册方法类似于组件的注册方法

9：Render函数 。。。
虚拟DOM：
Render函数
createElement

10：webpack
插件





13知乎日报开发
