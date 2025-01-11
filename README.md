<!--
 * @Author: ningyongheng ningyongheng@jeejio.com
 * @Date: 2025-01-11 13:28:39
 * @LastEditors: ningyongheng ningyongheng@jeejio.com
 * @LastEditTime: 2025-01-11 14:04:04
 * @FilePath: /my-website-peojecr/README.md
 * @Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->
# Website

## 引入搜索插件
### @easyops-cn/docusaurus-search-local
第一步：nodejs18.18.0

首先第一步：npm run build

第二步：npm run serve
注意：一定要用服务器配置，不能本地。

npm run build后，npm run serve

### 注意：使用模版，不要使用ts，使用js模版，不然
总有一些奇怪的问题，可能是搜索功能组件不适配ts




This website is built using [Docusaurus](https://docusaurus.io/), a modern static website generator.

### Installation

```
$ yarn
```

### Local Development

```
$ yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

Using SSH:

```
$ USE_SSH=true yarn deploy
```

Not using SSH:

```
$ GIT_USER=<Your GitHub username> yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.
