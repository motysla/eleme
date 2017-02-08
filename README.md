> 这是一个vue实战项目，源码采用vue1.0编写，非常适合新手进阶的绝佳教程。

### #使用项目
```
1.克隆项目：      git clone https://github.com/motysla/eleme.git 
2.安装依赖：      npm install
3.项目运行：      npm run dev  
4.编译打包：      npm run build
```

### #目录结构
<pre>
├── build              // 构建服务和webpack配置
├── config             // 项目开发环境配置
├── resource	         // 项目相关图片资源
├── dist               // 项目build目录
├── src                // 项目源码
│   ├── common            // 公共的模块和资源
│   ├── components        // 组件
│   │   ├── cartcontrol      // 购买控件
│   │   ├── food             // 商品详情页
│   │   ├── goods            // 商品列表页 
│   │   ├── header           // 页面头部 
│   │   ├── ratings          // 评价列表页 
│   │   ├── ratingselect     // 评价显示筛选
│   │   ├── seller           // 商家详情页 
│   │   ├── shopcart         // 购物车 
│   │   ├── split            // 分割线 
│   │   └── star             // 评星
│   ├── App.vue           // 主页面 
│   └── main.js           // 页面入口js
├── static	           // 第三方静态资源
├── .babelrc           // ES6语法编译配置
├── .editorconfig      // 编辑器的配置
├── .eslintignore      // 忽略语法检查的目录文件
├── .eslintrc.js			 // eslint的配置文件
├── .gitignore         // git仓库忽略的目录文件
├── README.md	         // 项目描述文件
├── data.json	         // 模拟数据文件
├── index.html         // 项目入口文件
├── package.json       // 项目配置文件
├── prod.server.js     // 搭建本地httpServer
</pre>

### #功能实现
- [x] 商家详细信息展示，商品列表，优惠活动
- [x] 商品列表滚动
- [x] 商品多列表滚动联动
- [x] 购物车功能
- [x] 餐馆及单个商品的评价列表展示、筛选
- [x] 图片左右滑动
- [x] 商品详情 父子组件通信
- [x] 商家收藏
- [x] 等等

### #项目技术架构
*  vue-cli
*  vue
*  vue-resource
*  vue-router
*  better-scroll
*  stylus
*  webpack
*  flex 弹性布局
*  css sticky footer 布局
*  移动端1px边框实现
*  vue 过渡动画
*  localStorage 数据存取

### #项目总结
```
1.使用 vue-cli 构建项目，可以快速起手进入代码编写。
2.使用 eslint 规范项目格式，保持风格统一。
3.使用 better-scroll，来进行滑动的支持。
4.尽量使用组件化，模块化的思想，即什么都能成为组件。
5.本项目在安卓4.2以下的动画效果不是很理想，滑动也不流畅，正在进一步改善中。
6.不利用 vuex ，进行父子间的通信。
```

### #项目界面

![1.png](http://www.zhoujiping.com/usr/uploads/2016/12/3945488787.png)

![2.png](http://www.zhoujiping.com/usr/uploads/2016/12/3608107615.png)

![3.png](http://www.zhoujiping.com/usr/uploads/2016/12/2024602137.png)

![4.png](http://www.zhoujiping.com/usr/uploads/2016/12/2686055158.png)
