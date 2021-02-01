## 使用效果

![WechatIMG494](img/WechatIMG494.jpeg)

## 使用

下载xpi格式文件，然后按照正常插件安装即可

## Zotero 插件制作

Zotero 的插件格式和 Firefox 一致，后缀为 xpi，但是本质其实是一个 zip 压缩文件

新建一个目录`markdownhere4zotero`包含如下内容

```
chrome.manifest
install.rdf
common/
firefox/
```

在该目录下进行 zip 即可

```sh
zip -r ./markdownhere4zotero.zip ./
```

然后修改 `markdownhere4zotero.zip` 为 `markdownhere4zotero.xpi` 即可。

## 源文件

markdown here github https://github.com/adam-p/markdown-here

markdown here zotero https://github.com/fei0810/markdownhere4zotero