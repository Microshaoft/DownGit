
# 浏览器端打包下载 GitHub 目录/文件夹

## 启动程序
```
npm run dev
```

## 注意事项
- 浏览器端可能要翻墙
- 下载包含文件数量 200 左右的目录, 成功率较高
- 浏览器端密集下载文件可能会被 GitHub 封杀浏览器端 IP
    - 如果被 GitHub 封杀返回 403/404, 需要更换浏览器端 IP  
    - F12 -> Network 筛选 "Fetch/XHR" 请求即为下载目标文件的请求


<h1> <img src="https://github.com/MinhasKamal/DownGit/raw/master/res/images/downgit.png" width="20" height=auto /> DownGit </h1>

#### Create GitHub Resource Download Link

With this tool you can directly download or create download link to any GitHub **public directory or file**.

### Website

[DownGit ↑](https://minhaskamal.github.io/DownGit)

### How to Use?

<table><tr><td> <img src="https://cloud.githubusercontent.com/assets/5456665/17822364/940bded8-6678-11e6-9603-b84d75bccec1.gif" /> </td></tr></table>

##### Advanced Usage

A typical download URL will look like this- `https://minhaskamal.github.io/DownGit/#/home?url=<link>&fileName=<name>&rootDirectory=<true or false or name>`

Now, if you want to download this directory- **`https://github.com/MinhasKamal/DownGit/tree/master/res/images`** with this file name- **`DownGit-Images.zip`** and this root directory name- **`ImagesOfDownGit`**, then the URL will be- https://minhaskamal.github.io/DownGit/#/home?url=https://github.com/MinhasKamal/DownGit/tree/master/res/images&fileName=DownGit-Images&rootDirectory=ImagesOfDownGit

In default, value of `fileName` and `rootDirectory` is set to the name of the downloading file or directory. If you do not want to add the directory itself in the zip, then set `rootDirectory=false`. Like: this link- https://minhaskamal.github.io/DownGit/#/home?url=https://github.com/MinhasKamal/DownGit/tree/master/res/images&rootDirectory=false, will download a file named **`images.zip`**; however the root directory- `"images"`, will not be included in the zip.

If you want to download file- **`https://github.com/MinhasKamal/DownGit/blob/master/res/images/downgit.png`** with name- **`DownGitIcon.zip`**, then the link will be- https://minhaskamal.github.io/DownGit/#/home?url=https://github.com/MinhasKamal/DownGit/blob/master/res/images/downgit.png&fileName=DownGitIcon

### License
<a rel="license" href="https://opensource.org/licenses/MIT"><img alt="MIT License" src="https://cloud.githubusercontent.com/assets/5456665/18950087/fbe0681a-865f-11e6-9552-e59d038d5913.png" width="60em" height=auto/></a><br/><a href="https://github.com/MinhasKamal/DownGit">DownGit</a> is licensed under <a rel="license" href="https://opensource.org/licenses/MIT">MIT License</a>.
