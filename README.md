## 起因

V2fly 于 [v4.32.0](https://github.com/v2fly/v2ray-core/releases/tag/v4.32.0) 引入了 ["Reproducible Builds"](https://github.com/v2fly/reproducible-builds)，允许你检视发布文件是否被篡改，是否由源码编译而成		

相比使用 Docker 构建并检查发布文件的"正确性"，何不自行 **从源码编译** 并下载使用呢？		

本模板即提供了这样一个环境，利用 Github Actions 免费的算力帮助你在 20 分钟内自行构建出和 V2fly 官方一模一样的发布文件	

## 使用方法

![1](https://github.com/charlieethan/v2ray-build/blob/master/Pictures/1.png)

- 点击右上角的 `Use this template` ，创建自己的仓库	

![2](https://github.com/charlieethan/v2ray-build/blob/master/Pictures/2.png)

- 输入仓库的名称，例如 `v2ray` ，点击下方 `Create repository from template` 即可完成

- 更改仓库内 `version` 这个文件，将其改为你想编译的版本号，例如 `v4.32.0` 	

- 构建已经开始，请耐心等待 20 分钟后在自己仓库的 release 下寻找需要的程序

## 授权

[Mozilla Public License 2.0](https://github.com/charlieethan/v2ray-build/blob/master/LICENSE)