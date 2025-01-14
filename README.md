# docker-available-source
update: 1-14-2025 


```BASH
sudo vi /etc/docker/daemon.json

```
```JSON

 {
"registry-mirrors": [
    "https://docker.m.daocloud.io", 
    "https://noohub.ru", 
    "https://huecker.io",
    "https://dockerhub.timeweb.cloud",
    "https://0c105db5188026850f80c001def654a0.mirror.swr.myhuaweicloud.com",
    "https://5tqw56kt.mirror.aliyuncs.com",
    "https://docker.1panel.live",
    "http://mirrors.ustc.edu.cn/",
    "http://mirror.azure.cn/",
    "https://hub.rat.dev/",
    "https://docker.ckyl.me/",
    "https://docker.chenby.cn",
    "https://docker.hpcloud.cloud",
    "https://docker.m.daocloud.io"
  ]
}
```
## reload and restart
```BASH
# reload
systemctl daemon-reload
# restart
systemctl restart docker

```
