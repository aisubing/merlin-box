## 主程序更新下载缓存修改

> 修改下载到U盘，修改文件：/jffs/merlin-box/sh/tool.sh

```
修改“更新 merlin-box”部分：local tmp_dir="${CUR_DIR}/.tmp-update-merlin-box"修改为：local tmp_dir="/mnt/u-disk/user/.tmp-update-merlin-box"
```
## 网页图标修改

>替换文件：/merlin-box//wwwroot/favicon.ico

```
新favicon：/merlin-box/favicon.ico
```