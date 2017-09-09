# HTML Basic Intro


- [hr](#hr)
- [img](#img)
    - [usemap](#usemap)
        - [map](#map)


## hr

> horizontal rule 水平分割线

```
<hr>
```

## img

### usemap

> usemap="#map_id"

```
<img src="../img/search_engine_1.jpg" usemap="#search_engine_1_map">
```

#### map

```
<map id="search_engine_1_map">
    <area href="https://www.baidu.com/" alt="百度搜索" shape="rect" coords="30,20,190,90" target="_blank">
    <area href="https://www.so.com/" alt="360搜索" coords="210,20,390,90" target="_blank">
    <area href="http://www.chinaso.com/" alt="中国搜索" coords="30,110,190,180" target="_blank">
    <area href="https://www.sogou.com/" alt="搜狗搜索" coords="210,110,390,180" target="_blank">
    <area href="https://www.dgso.cn/" alt="稻谷搜索" coords="30,200,190,270" target="_blank">
    <area href="http://cn.bing.com/" alt="Bing" coords="210,200,390,270" target="_blank">
</map>
```

