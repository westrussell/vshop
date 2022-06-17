1:vue-cli脚手架初始化项目
node_modules文件夹：项目依赖文件夹

public文件夹：一般放置一些静态资源（图片），需要注意，放在public文件夹中的静态资源，webpack进行打包的时候，会原封不动打包到dist文件夹中

src文件夹（程序员源代码文件夹）：
    assets文件夹：一般也是放置静态资源，（一般放置多个组件公用的静态资源），需要注意，放置在assets文件里面的静态资源，在webpack打包的时候，会把静态资源当作一个模块，放在js文件里面

    components文件夹:一般放置的是非路由组件（全局组件）

    App.vue 唯一的根组件
    main.js：程序入口文件，也是整个程序当中最先执行的文件

babel.config.js:配置文件

package.json文件：认为项目的‘身份证’，记录项目叫什么，项目中有哪些依赖，项目怎么运行

package-lock.json文件：缓存性文件