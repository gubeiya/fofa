# fofa

自行下载在api.conf填入自己的帐号和key

fofa-api采集搜索脚本 ------顾北.
Usage:
使用说明  fofa -s host="edu.cn"
高级搜索 
fofa -s  'host="edu.cn"&&body="学号"' 
在单引号里面输入你要搜索的内容即可
默认采集1w条数据，默认保存名称url.txt  
如果想保存其他名称 fofa -s host="edu.cn" -f aa.txt
