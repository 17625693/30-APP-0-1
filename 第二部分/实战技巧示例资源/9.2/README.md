# README

## DEMO 运行流程说明

- 在云端 [APICloud](https://www.apicloud.com) 的控制台新创建一个Native应用
	
	![创建应用](./readmeImgs/createApp.png)

- 根据下面提供的**使用模块列表**，将对应的模块添加到应用
	
	![添加模块](./readmeImgs/addModule.png)

- 使用 [APICloud Studio2](https://www.apicloud.com/devtools) 或其他 SVN工具将新建的应用代码从云端下载到本地
	
	![从云端下载应用](./readmeImgs/downApp.png)

- 下载本 DEMO 的源代码，使用 DEMO 源码覆盖上面新建的应用代码（注意在config.xml中使用新建应用的appId）

- 将代码保存并同步到云端
	
	![同步新代码到云端](./readmeImgs/uploadApp.png)

- 在 [APICloud](https://www.apicloud.com) 控制台云编译本项目
	
	![控制台云编译](./readmeImgs/buildApp.png)
	
- 使用手机扫描二维码下载安装本项目，即可查看 DEMO 的运行效果

## 使用模块列表

- [UIScrollPicture](https://docs.apicloud.com/Client-API/UI-Layout/UIScrollPicture)
	
	UIScrollPicture 是一个图片轮播模块，只需传入一组图片地址，即可实现图片轮播效果。
	
- [UIButton](https://docs.apicloud.com/Client-API/UI-Layout/UIButton)
	
	UIButton 是 button 模块的优化升级版，用原生代码实现了一个可自定义的按钮，开发者使用此模块可以实现在一个模块视图上添加自定义按钮的功能，本模块支持手指拖动改变按钮位置功能。