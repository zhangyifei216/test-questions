# test-questions

这个地址下的https://airbnb.io/enzyme/docs/api/  三种Rendering方式的区别？

shallow rendering (浅渲染)指的是，将一个组建渲染成虚拟DOM对象，但是只渲染第一层，不渲染所有子组件，所以处理速度非常快，它不需要DOMhuanjing，因为根本没有加载进DOM，返回的结果可以用类似jquery的形式获取组建的信息。
