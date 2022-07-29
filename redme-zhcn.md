# 行云控制台-前端

## 构建设置

```重点
# 安装依赖环境
$ yarn install
# 服务器重载为localhost:3000
$ yarn dev
# 为生产和启动服务器构建
$ yarn build
$ yarn start
# 生成静态项目
$ yarn generate
```

有关工作原理的详细说明，请查看 [文档](https://nuxtjs.org)。

## 特殊目录

您可以创建以下额外目录，其中一些具有特殊行为。只需要`pages`；如果您不想使用它们的功能，可以删除它们。

### `assets`

assets 目录包含未编译的资产，例如 Stylus 或 Sass 文件、图像或字体。

[文档](https://nuxtjs.org/docs/2.x/directory-structure/assets) 中有关此目录使用的更多信息。

### `components`

components 目录包含你的 Vue.js 组件。组件构成页面的不同部分，可以重复使用并导入到页面、布局甚至其他组件中。

[文档](https://nuxtjs.org/docs/2.x/directory-structure/components) 中有关此目录使用的更多信息。

### `layouts`

当您想要更改 Nuxt 应用程序的外观和感觉时，无论您想要包含侧边栏还是为移动设备和桌面提供不同的布局，布局都是一个很大的帮助。

[文档](https://nuxtjs.org/docs/2.x/directory-structure/layouts) 中有关此目录使用的更多信息。


### `pages`

此目录包含您的应用程序视图和路由。 Nuxt 将读取此目录中的所有 `*.vue` 文件并自动设置 Vue Router。

[文档](https://nuxtjs.org/docs/2.x/get-started/routing) 中有关此目录使用的更多信息。

### `plugins`

plugins 目录包含您希望在实例化根 Vue.js 应用程序之前运行的 JavaScript 插件。这是添加 Vue 插件和注入函数或常量的地方。每次需要使用 `Vue.use()` 时，都应该在 `plugins/` 中创建一个文件，并将其路径添加到 `nuxt.config.js` 中的插件中。

[文档](https://nuxtjs.org/docs/2.x/directory-structure/plugins) 中有关此目录使用的更多信息。

### `static`

此目录包含您的静态文件。此目录中的每个文件都映射到`/`。

示例：`/static/robots.txt` 被映射为 `/robots.txt`。

[文档](https://nuxtjs.org/docs/2.x/directory-structure/static) 中有关此目录使用的更多信息。

### `store`

此目录包含您的 Vuex 存储文件。在此目录中创建文件会自动激活 Vuex。

[文档](https://nuxtjs.org/docs/2.x/directory-structure/store) 中有关此目录使用的更多信息。
