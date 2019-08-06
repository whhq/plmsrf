# 普逻码输入法 Puluoma Input Mathod  Readme

普逻码是一种拼音加部首码的汉字输入法，经过普逻码发明人whhq的研究改进，实现了[双拼](https://whhq.github.io/index.html)和[全拼加部首码](https://whhq.github.io/pinyin-plma.html)的GBK二万多字无重码输入，完全攻克拼音输入法的重码难题，让汉字能象拉丁文字一样，不用选字直接键盘输入电脑。  
 
普逻码能“一码一字”表示汉字，包含了拼音、部首和字频等信息，让汉字和拉丁字母无误转换，拼音加部首码方式可作为一种直观的拉丁表音文字方案，双拼加部首方式四码内就能指定一个GBK汉字，可作为简写的拉丁文字。  

普逻码编码简单易记，如“普”字编码为pur，r是部首“日”的编码。
“逻”字编码为loz，z是部首“辶”的编码，lo是双拼，也可直接打拼音luo加z，“luoz”输入逻字。
“码”字编码为map，ma是拼音，部首“石”编码是p。 

## 普逻码简答 Q & A
1. 普逻码是什么？  拼音+部首   
2. 部位码是什么？  部首+部首+部首   
3. 然后呢？  按顺序排成无重码
4. 什么顺序？ 常用的靠前，不常用的按笔画顺序排位。
5. 怎么去记？ 不用记，常用的字大多是拼音后加一码，靠后的常用字排位码可用字母顺序推出，候选窗口也有提示。
6. 不会读音的字怎么办？ 用部位码，每个汉字都可用部首分成三码。

## 普逻码快速入门方案——全拼普逻码
全拼普逻码可以让拼音用户轻松实现盲打单字，用拼音打单个汉字的时候，不用在一堆同音字里逐个去找，而且超越形码，真正做到无重码。  
根据[普逻码输入法全拼版](https://whhq.github.io/pinyin-plma.html)
统计，打完拼音，加一个部首码，能打出国标6763字里的4436个常用字，超过三分之二的常用字可以用拼音加部首的方法打出。  
其它字可用b/c/d/e/f/g/h/i/j/k/l/选出，通常同音字到f都能找到，不用刻意去记，一般打一两次就有印象。 
另外的GBK繁体字和难字，编码是m到z，常用的繁体字和相对容易的字都占在m/n/o编码上，一般用户可忽略这些字，需要时也可以按字母顺序去试打。



## 普逻双拼键位编排

普逻码双拼韵母只用25键，除w和b键，双击一键就得一个音节，键位很好记。

|键位 | 韵母 |  助记|
| :-------------|:------------- |:------------- |
|q |iang uang | 央 王 |
|w |ia wa     |呀 哇 | 
|e  |  
|r |uan       |  弯冤 软|  
|t |ie        |  铁    |
|y |ing uai |  英 外   |
|u | Zh-    | 珠   |
|i | Sh-    | 是  |
|o | |  
|p |ei      | 配  |
|a |  
|s |ong iong  |  松 拥  |
|d |ai        | 代  |
|f |ou        |  否  |
|g |en ue     |  根 恩月  |
|h |ang  | 杭   |
|j |ian  |尖 烟 | 
|k |un   | 昆云|  
|l |an   |兰  |
|z |eng    |曾  |
|x |in     |心   |
|c |ao     |草   |
|v |Ch- ui |  吹|  
|b |  
|n |iu    |牛  |
|m |iao   | 秒  |


## 普逻部首码编排 

|字母 |非简拼部首|部首（共259个） |
| :-------------|:------------- |:------------- |
|a  |  手         |扌手  |
|b  |  宀         |丷宀八贝勹卜白匕疒貝比冫髟癶鼻  |
|c  |             |虫寸厂车彳車巛臣辰采川齒长赤齿镸長  |
|d  | 丶          |丶大刀刂豆歹斗鬥鼎  |
|e  | 水已        |氵儿水而二已  |
|f  | 阝耳纟      |阝糹匚耳方纟糸丰缶非父風风飞邑阜  |
|g  |             |戈广弓工廾艮革干骨鬼谷高甘瓜鬲鼓龟  |
|h  | 一          |一火禾灬虍户黑黄  |
|i  | 木          |木  |
|j  |             |釒巾钅臼卩几斤见金角見旡己韭|
|k  | 竹衣〇      |竹衣衤凵克 〇（空）|
|l  | 丨月        |丨月力立耂鹿里龍耒龙隶鹵卤|
|m  |             |目米冖皿馬门马門毛矛母麻面黽麥黾麦毋|
|n  |  乀         |女乀鳥牛鸟牜|
|o  | 口          |口|
|p  | 丿石尸殳    |丿石尸殳皮片爿丬|
|q  | 酉          |犭酉欠犬青气齐齊|
|r  | 雨          |日雨肉曰入|
|s  |             |十山厶士罒豕彡示巳飠礻氏矢生饣舌身鼠色食首|
|t  | 冂亠        |土冂田亠 √（提）|
|u  |艹           |艹艸|
|v  |乙人         |乙人亻|
|w  |囗           |王攵囗兀文瓦韦韋攴|
|x  |乂彑         |心小忄夕彐西乂穴辛玄香血彑爻|
|y  |廴           |又言魚羽聿羊讠用鱼业页頁幺廴弋音尢牙龠|
|z  |夂疋         |辶隹夂足子爫止疋舟至走自豸支之爪|


## 普逻码三种方案编订过程要点 

普逻码可以看作是一种音形码，和拼音加辅助码的形式也相同，不同的是对拼音加部首后的排位顺序进行了“逻辑编码”。  

一、[双拼普逻码](https://whhq.github.io/index.html)，四码无重，双拼为前两码，第三码是部首码，第四码是“逻辑排位码”。  
1. 国标GB2312共6763字，一级字库3755常用字按字频排位，二级字库按笔画顺序排位，第四位码按bcdefghijkl字母顺序选取。  
2. GBK字集除去6763字，将一级字库3755字转换得出的繁体字按字频排位，二级字库转换得出的繁体字按笔画顺序排位，两步完成后得出两千多个常用和比较常见的繁体字，剩下的过万字按笔画顺序排位。第四码由m到z按顺选取，z后是za-zq的排位（107个）。  
3. 第四、五位为za-zq的，韵母位改z，第四码按笔画顺序排到z，这些都是罕用字，只用作记录。  

二、[全拼普逻码](https://whhq.github.io/pinyin-plma.html) ，拼音无重码输入。  
1. 将双拼普逻码的两个双拼编码换成全拼。
2. 有重码的难字加l（400个加l，14个加ll），都是罕用字，只用作记录。

三、[双拼全拼通用无重码](https://whhq.github.io/py-sp.html)

1. 双拼普逻码加全拼普逻码，去除重复行。为保证双拼四码能无重码输入，双拼和全拼有重码的，全拼编码后加a（共263个，4个加aa）。  
2. 将全拼普逻码的部首位变成大写，就可以成为一种拉丁文字方案，双拼普逻码可以作为简写拉丁文字。  


* *niV haoN，shiHB jieTA!*  
* *niv hcn , iihb jtt!*  
* *你好，世界！* 

因为字频和双拼优先的原因（shiH事 iih事 jiET漃），“世”shiH iih要加b（要点一、1），“界”jieT要加a（要点三、1）。 


## 普逻码形码方案———— [部位码](https://whhq.github.io/buweima.html) ( Buweima Input Mathod   )

部位码规则非常简单，将一个汉字分解成三个部首码。
1. 部首+部首+部首   
2. 部首+部首+末笔    
3. 部首+首笔+次笔      

如“部”分解为“阝 口 立”   
  “位”分解为“亻 立 一“    
  ”首”分解为”首 丶 丿“ 

部位码只要三码就能很容易找到要打的字，加上第四码简拼或末笔，重码率已经接近或超过其它常用形码。
如果第四码采用字频和笔画顺序排位的话，也能成为无重码输入法。  

部位码所编排的部首，总共259个，成功将数以万计的汉字通过部首、偏旁、笔画系统整合，让每个汉字按常规分成三部分，而且部首分解可读，可用来帮助汉字识记，应用于汉字教学中,
类似拼读英文单词的字母。  

部位码还可以作为一种汉字拆字标准，让其它形码的“字根”按照部位码的部首模式重新改造，避免各种形码拆分混乱变成“万码”。  
最常见的五笔、郑码、仓颉、二笔、表形码等形码都可采用259个部首打造出比原形码更好记的方案。


### 快又准的三码无重方案———— [普逻三码无重](https://whhq.github.io/pb-3m.html)

26个英文字母按三码组合，可以得到26x26x26=17576个组合，常用汉字两三千，GB2312中的6763个汉字几乎能满足日常应用，理论上三码就能输入GB2312的汉字。
普逻码和部位码都能做到四码无重输入GBK里2万多汉字，将两者结合起来，成功打造出快又准的三码方案。  
  
普逻码为声声部，部位码为部部部，两种组合成五类编码，另加特定编码和一二简码，统计七类编码总数：  
1. 声声部 4232字
2. 部部部 1627字
3. 部部声 373字
4. 部声声 239字
5. 声部部 105字
6. 其它特定 187字
7. 一简二简 702字

>  n hc，WR jt!  
> 你好，世界  

> GI qj my yg gq , 床前明月光  
> yiB i di ih iqR . 疑是地上霜  
> juD tf whL my yg , 举头望明月  
> diV tf siX guW VVx .低头思故乡  

最简单的普逻部位码，三码内就能确定6763个字，满足日常使用，还可以变成世界上最简单的拉丁字，其中小写代表双拼或声母，大写代表部首或特定，输入时不区分大小写。  
以后全世界不懂写汉字的人都可以先用简单的三个字母标注汉字，学会了拼音和部首，就不怕认不了汉字。

### 发明普逻码的目标和过程

当初发明普逻码输入法时的目标是让汉字简单容易地无重码输入电脑，经过不断研究，实现[双拼+部首](https://whhq.github.io/index.html)四码内无重输入汉字，转换成[全拼+部首](https://whhq.github.io/pinyin-plma.html)也实现了这个目标，接着把普逻码尝试变成一种新的拉丁拼音文字 。  

然后想不认识的字怎么输入，难道要死记各种拆分字根的形码？后来想到把部首的威力发挥起来，把每个汉字分解成三个部首码，发明了[部位码](https://whhq.github.io/buweima.html),再难的字也不怕打不出，很快又把部位码设计成象普逻码一样四码內无重输入二万多GBK字。  
 
接着编排好一简和二简，能不能三码内输入GB2312里的6763个字？经过一段时间的思索，把普逻码和部位码结合起来，分成五类编码，剩下一两百字用特定编码，实现了[三码输入](https://whhq.github.io/pb-3m.html)所有常用字的目标。

普逻码输入法已经完成了多种方案和编码，还需要核对和修订，越多人使用就能让输入法更完善。解决了汉字输入难题，用拼音学汉语，用部首帮助识字，相信汉字也会象字母文字一样世界通行。

