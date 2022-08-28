# TV_Spider
服务端爬虫 T4，基于`Python 3`

### [DEMO](https://t4.secan.icu/vod)：`https://t4.secan.icu/vod?sites=all&ali_token=xxxxxxxxx&timeout=10`

[参数说明及如何在TVBoxOSC中调用](https://github.com/sec-an/TV_Spider/wiki/%E5%A6%82%E4%BD%95%E5%9C%A8TVBoxOSC%E4%B8%AD%E8%B0%83%E7%94%A8)

---

### [腾讯云函数版本](https://github.com/sec-an/TV_Spider/tree/scf)
### 安装及使用说明，请参考[Wiki](https://github.com/sec-an/TV_Spider/wiki)
### 爬虫失效及其它问题，请移步[Issues](https://github.com/sec-an/TV_Spider/issues)


### `仅供Python爬虫学习交流使用！切勿用于违法用途，否则开发者不承担任何责任。`
### `欢迎Star 欢迎PR`

---
### 安装依赖
```pip install -r requirements.txt```
### 运行
```gunicorn -w 4 -b 0.0.0.0:8080 app:app```
### 说明
1. 部分爬虫代码参考自[Tangsan99999 / TvJar](https://github.com/Tangsan99999/TvJar)
