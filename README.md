# webpack4.x_Demo
1.add ts done
2.add multi page entrance done
3.add egg.js done
4.nunjucks support
5.add sample
6.add jq support done
7.add real page styles
8.dev add public directory prod add custom directory

# hackernews-async-ts

[Hacker News](https://news.ycombinator.com/) showcase using typescript && egg

## QuickStart

### Development

```bash
$ npm i
$ npm run dev
$ open http://localhost:7001/
```

Don't tsc compile at development mode, if you had run `tsc` then you need to `npm run clean` before `npm run dev`.

### Deploy

```bash
$ npm run tsc
$ npm start
```

### Npm Scripts

- Use `npm run lint` to check code style 
- Use `npm test` to run unit test 
- se `npm run clean` to clean compiled js at development mode once

### Requirement

- Node.js 8.x
- Typescript 2.8+

### 打包路径简短调用
path_components // 公共组件目录
path_images // 公共资源目录
path_styles // 公共样式目录
path_view   // 模板目录

