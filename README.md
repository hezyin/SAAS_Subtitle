EAAS_Subtitle
=============

> 经过我们校对的内容将直接放到网上作为课程的字幕文件，所以请大家务必认真对待，谢谢！

文件目录
-------------

根目录下包含两个文件夹: ```\srt_en``` 和 ```\srt_sc```
* ```\srt_en```中包含所有课程英文字幕文件, 已全部上传, 共114个
* ```\srt_sc```中包含有道翻译已经返回的中文字幕文件

工作机制
-------------

翻译校对以周为单位，每周五
* 有道: 给我们当周新翻译好的字幕和对上周校对内容的修改
* 我们: 返回当周的校对成果(校对内容是有道上一周翻译的字幕)

新的校对机制
-------------

* 一个字幕先由主审人认真校对一遍，应该解决大部分翻译错误
* 主审人校对一遍之后，由复审人查遗补漏，以相对较快的速度校对一遍

具体校对方法如下：

* 用词不当等小错直接在中文字幕文件中原地更改
* 句意错误或几句话不通顺等大错请用{ }将出错的部分括起来，留给有道重新翻译

### Commit 格式

* 校对完成后，请按以下格式commit后再push
```
git commit -am “aaa b” \\其中xxxx为校对者姓名拼音首字母, x为一整数, 取0表示第一次校对，取1表示确认有道重翻的结果
git commit -am “yhz 0” \\表示校对者为yin he zheng, 是第一次校对
```

### 时间要求

* 所有任务(对新内容的校对和对有道重翻内容的确认)请在**每周四晚12:00之前**完成
* 任务完成时间以最后一次commit为准

任务分配
--------------

下表为第一周的校对任务分配，表格中内容，如w1l1s1对应于一个字幕文件。表格第一行为大家姓名拼音首字母缩写(commit信息的内容应与这里一致)。

| Week |       ja        |      xfz         |      jd         |      ljq        |      xyh       |      yy        |  ymt            |
|------|:---------------:|:----------------:|:---------------:|:---------------:|:--------------:|:--------------:|:---------------:|
|1     |w1l1s1 & w2l1s10 |w2l1s10 & w2l1s11 |w2l1s11 & w3l1s4 |w3l1s4 & w3l1s5 	|w3l1s5 & w3l1s6 |w3l1s6 & w3l1s7 | w3l1s7 & w3l1s9 |
|1     |w3l1s9 & w3l1s10 |w3l1s10 & w3l1s11 |w3l1s11 & w3l1s12|w3l1s12 & w3l2s1 |w3l2s1 & w1l1s1 |     ---        |     ---         |
































