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

使用props传递数据,接受父组件的message
单项数据流：
数据验证：

父子组件通信：
兄弟组件通信：
跨级组件通信：


67组件内容：pass
8指令 pass





