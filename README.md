# vee-image 为vue2+设计的绘图组件库！

<p>
  <a href="https://yelloxing.gitee.io/npm-downloads?interval=7&packages=vee-image"><img src="https://img.shields.io/npm/dm/vee-image.svg" alt="downloads"></a>
  <a href="https://packagephobia.now.sh/result?p=vee-image"><img src="https://packagephobia.now.sh/badge?p=vee-image" alt="install size"></a>
  <a href="https://www.jsdelivr.com/package/npm/vee-image"><img src="https://data.jsdelivr.com/v1/package/npm/vee-image/badge" alt="CDN"></a>
  <a href="https://www.npmjs.com/package/vee-image"><img src="https://img.shields.io/npm/v/vee-image.svg" alt="Version"></a>
  <a href="https://github.com/Open-Organize/vee-image/blob/master/LICENSE"><img src="https://img.shields.io/npm/l/vee-image.svg" alt="License"></a>
</p>


- 如何引入和使用，包括具体的组件等请查看[接口文档](http://yelloxing.gitee.io/vee-image/)

如何启动测试用例？
-----------------------------

首先安装并启动用例项目:

```bash
npm start
```

然后在浏览器中打开下列地址：

http://127.0.0.1:20000/examples/index.html

此外，文档页面地址如下：

http://127.0.0.1:20000/docs/index.html

开发需知
----------------------------

本项目基于[image2D](https://github.com/yelloxing/image2D)实现，开发中你需要查阅[image2D接口文档](https://yelloxing.gitee.io/image2d/#/guide)，如果在使用过程中遇到任何问题请在[Issue](https://github.com/yelloxing/image2D/issues)中提问，包括新增接口等。

任何一个新的组件的开发或旧组件的维护，除了在代码中添加良好的备注和[测试用例](https://github.com/Open-Organize/vee-image/tree/master/examples)中进行测试外，还应该同步[文档](https://github.com/Open-Organize/vee-image/tree/master/docs)到中。

修改了文档或代码以后，在提交或发布前别忘了进行打包：

```bash
npm run build
```

## License

[MIT](https://github.com/Open-Organize/vee-image/blob/master/LICENSE)

Copyright (c) 2020 Open-Organize
