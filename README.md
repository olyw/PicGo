# 图床

* 使用 GitHub + PicGo-Core搭建图床

* PicGo配置文件`config.json`

~~~json
{
  "picBed": {
    "current": "github",
    "uploader": "github",
    "transformer": "path",
    "github": {
      "repo": "olyw/PicGo",	//仓库名
      "branch": "main",	//分支名
      "token": "***",	//GitHub Token
      "path": "images/2022",//自定义存储路径
      "customUrl": "https://cdn.jsdelivr.net/gh/olyw/PicGo"//自定义域名
    }
  },
  "picgoPlugins": {}
}
~~~

