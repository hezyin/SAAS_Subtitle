EAAS_Subtitle
=============

> 经过我们校对的内容将直接放到网上作为课程的字幕文件，所以请大家务必认真对待，谢谢！

校对进度
-------------

**41/114 = 36% 截止到2014.4.20（第二周完结)**

时间要求
-------------

**由于英文字幕不一定靠谱，有道翻译一定不靠谱，所以请大家务必尽早开始校对！**
**考虑到助教答疑工作开始了，从这周开始将校对deadline推到周五晚上，希望不要再出现延误的情况！**

* 所有任务(对新内容的校对和对有道重翻内容的确认)请在**每周五晚12:00之前**完成
* 任务完成时间以最后一次commit为准

文件目录
-------------

根目录下包含两个文件夹: ```\srt_en``` 和 ```\srt_sc```
* ```\srt_en```中包含所有课程英文字幕文件, 已全部上传, 共114个
* ```\srt_sc```中包含有道翻译已经返回的中文字幕文件, 114个初稿已拿到，但为方便大家查看，每周仅上传当周的任务

工作机制
-------------

翻译校对以周为单位，每周五
* 有道: 给我们当周对上周校对内容的修改
* 我们: 返回当周的校对成果(校对内容是有道上一周翻译的字幕)

新的校对机制
-------------

考虑到我们还有**70个字幕**需要校对，以及未来可能需要翻译Quiz题目（老板认为有道很难正确翻译Quiz），我们最终还是决定采取简单的机制，如下:
* 一个字幕仅由一个人校对一遍
* 每人对自己负责的字幕负全责，理论上不会有其他人进行复审
* 每周末我会随机检查本周校对的字幕，可以有小错，但原则上不应有影响理解的大错

具体校对方法如下：

* 用词不当等小错直接在中文字幕文件中原地更改
* 句意错误或几句话不通顺等大错请用{ }将出错的部分括起来，留给有道重新翻译

### Commit 格式

校对完成后，请按以下格式commit后再push
```
git commit -am “string int” \\其中string为校对人姓名拼音首字母, int为一整数，0表示第一次校对，1表示确认有道修改的版本
git commit -am “yhz 0” \\表示校对人为yin he zheng, 此次commit为第一次校对
```

任务分配
--------------

下表为校对任务分配，表格中内容，如w1l1s1对应于一个字幕文件。表格第一行为大家姓名拼音首字母缩写(commit信息的内容应与这里一致)。

| Week |       ja        |      xfz         |      jd         |      ljq        |      xyh       |      yy        |  ymt            |
|------|:---------------:|:----------------:|:---------------:|:---------------:|:--------------:|:--------------:|:---------------:|
|1     |w1l1s1 & w2l1s10 |w2l1s10 & w2l1s11 |w2l1s11 & w3l1s4 |w3l1s4 & w3l1s5 	|w3l1s5 & w3l1s6 |w3l1s6 & w3l1s7 | w3l1s7 & w3l1s9 |
|1     |w3l1s9 & w3l1s10 |w3l1s10 & w3l1s11 |w3l1s11 & w3l1s12|w3l1s12 & w3l2s1 |w3l2s1 & w1l1s1 |     ---        |     ---         |
|2     |w1l1s2 & w1l1s3  |w1l1s6 & w1l1s7   |w1l1s10 & w1l1s11|w2l1s3 & w2l1s4  |w2l1s7 & w2l1s8 |w2l2s2 & w2l2s3 |w2l2s6 & w2l2s7  |
|2     |w1l1s4 & w1l1s5  |w1l1s8 & w1l1s9   |w2l1s1  & w2l1s2 |w2l1s5 & w2l1s6  |w2l1s9 & w2l2s1 |w2l2s4 & w2l2s5 |w2l2s8 & w2l2s9  |
|2     |     ----        |     ------       |    -------      |      -------    |   --------     |     w2l2s10    |     ------      |
|3     |w3l1s1 & w3l1s2  |w3l2s3 & w3l2s5   |w3l2s8 & w3l2s9  |w3l2s12 & w4l1s1 |w4l1s4 & w4l1s5 |w4l1s6 & w4l1s7 |w4l1s8 & w4l1s9  |
|3     |w3l1s3 & w3l2s2  |w3l2s6 & w3l2s7   |w3l2s10 & w3l2s11|w4l1s2 & w4l1s3  |翻译作业及自测题  |翻译作业及自测题  |翻译作业及自测题   |

下表为答疑时间表, 每天由2人负责， 一周每人负责2天

|       ja        |      xfz         |      jd         |      ljq        |      xyh       |      yy        |     ymt         |
|:---------------:|:----------------:|:---------------:|:---------------:|:--------------:|:--------------:|:---------------:|
|      1 & 4      |     4 & 5        |     1 & 3       |     2 & 7       |     2 & 3      |     5 & 6      |    6 & 7        |
