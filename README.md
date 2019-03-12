# Vue还原美团商家界面

网上购买的一个Vue实战课程,把整个项目完整写了下来,虽然是跟着实战,但也学到了很多,希望下次自己也能写出来吧。
课程收获:学习了移动端常见的样式设计,实现购物车核心功能,购物车列表数据联动,商品详情和购物车联动,评价星级的实现,商家页面的左右轮播

**技术栈:**

Vue2.0+Vue-CLI+Vue-Router+better-scroll

**项目运行**
```
git clone https://github.com/kawaii7/Meituan.git
npm install
npm run serve
```
**功能介绍:**

在商家页面顶部部分有活动详情页可以展开。导航栏会有点餐、评价和商家三个功能块，点击会路由跳转到各自区域。

![enter image description here](https://github.com/kawaii7/Vue/blob/master/images/%E7%BE%8E%E5%9B%A2/1.gif)

核心功能区点餐页左侧商品分类列表和右侧具体商品实现分类的联动，主要是通过计算右侧具体商品分类的滚动位置，并在各个分类滚动位置区间确认唯一下标，与左侧分类对应。点击分类项可以跳转到具体商品区域和列表滚动是通过better-scroll实现

![enter image description here](https://github.com/kawaii7/Vue/blob/master/images/%E7%BE%8E%E5%9B%A2/2.gif)

购物车实现了添加商品，点击购物车可以展开，购物车高度限制，商品数量超出购物车限定高度实现滚动效果，购物车中可以添加减少商品和清空购物车还有总价结算

![enter image description here](https://github.com/kawaii7/Vue/blob/master/images/%E7%BE%8E%E5%9B%A2/3.gif)

点击商品进入商品详情页里面包含外面评价和添加减少商品

![enter image description here](https://github.com/kawaii7/Vue/blob/master/images/%E7%BE%8E%E5%9B%A2/4.gif)

进入评价页有三项评价分类， 显示商家和配送的评分星级

![enter image description here](https://github.com/kawaii7/Vue/blob/master/images/%E7%BE%8E%E5%9B%A2/5.gif)

进入商家页商家实景图可以左右滚动

![enter image description here](https://github.com/kawaii7/Vue/blob/master/images/%E7%BE%8E%E5%9B%A2/6.gif)
