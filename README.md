## pinyin4j

#### 项目来源
本项目基于 pinyin4j, belerweb.pinyin4j, wnjustdoit.pinyin4j 进行再次封装改造。   
* http://sourceforge.net/projects/pinyin4j （原始）
* https://github.com/belerweb/pinyin4j （二次封装，但已经不维护了，有部分缺陷）
* https://github.com/wnjustdoit/pinyin4j （二次封装，但已经不维护了，有部分缺陷）

#### maven坐标
```
        <dependency>
            <groupId>io.github.tokenjan</groupId>
            <artifactId>pinyin4j</artifactId>
            <version>2.6.1</version>
        </dependency>
```

#### QQ Group
QQ群：939928163

#### 多音字识别
在pinyin4j的基础上添加了多音字识别，带近一万个多音词，但是这远远不够，所以用户可设置外挂词库	

#### 外挂多音词库
用户配置的外挂词库会覆盖系统中相同词的读音,可用于纠错。   
配置方式很简单,只需要配置路径即可 
```
MultiPinyinConfig.multiPinyinPath="/Users/yiboliu/my_multi_pinyin.txt"
```

格式同系统的多音词库,如: 
```
吸血鬼日记 (xi1,xue4,gui3,ri4,ji4)
```
