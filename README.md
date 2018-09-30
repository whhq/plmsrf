# 普逻码汉字编码

Copyright 2018 Wang Haiqing ( plma756@hotmail.com ).

普逻码是一种易学易用的音形结合输入法，由双拼、部首码和字频号三部分组成。

普逻码解决了汉字输入的重码和记忆难题，三个字母即可表示一个常用字，包含字的音节和部首信息，比很多拉丁化文字更先进。

普逻码、普逻码双拼、数字普逻码的知识产权(包括著作权、版权、发明权等)归发明人Wang_Haiqing所有。

个人可以免费使用普逻码，学会后可用资金支持一下发明人。

如用于商业用途需支付版权费，版权费千元起步，每用户十元一年。

发明人：wang haiqing 支付宝邮箱账号 plma756@hotmail.com

普逻码项目网址: https://github.com/whhq/plmsrf


## 普逻码说明

* 1、双拼键位
普逻码双拼键盘，韵母分布在除b以外的英文字母键上。
除w和b键外，一键连按2次都可组成一个音节，达到易记效果，如
qq=qiang,ee=e,rr=ruan,tt=tie,
yy=ying,uu=zhu,ii=shi,oo=o,pp=pei,
aa=a,ss=song,dd=dai,ff=fou,gg=gen,
hh=hang,jj=jian,kk=kun,ll=lian,
zz=zeng,xx=xin,cc=cao,vv=chui,nn=niu,mm=miao 。

nen和nue的双拼同为ng，有些输入法不支持，可将音节nue定为nb，或把韵母ue安排到b键上。

具体双拼设置：
```
(声母)
zh=u
ch=v
sh=i

(零声母音节)
a=aa
ang=ag
e=ee
eng=eg
o=oo

(韵母)
ai=d
ei=p
ui=v

ao=c
ou=f
iu=n

ie=t
ue=g
er

an=l
en=g
in=x
un=k
vn

ang=h
eng=z
ing=y
ong=s

ia=w
iao=m
ian=j
iang=q
iong=s

ua=w
uai=y
uan=r
uo=o
uang=q
```

* 2、部首码（第三位编码）

普逻码部首码主要以部首的声母首字母作编码，部分为指定，使每个键所对应汉字数相对均衡。

具体安排如下：
```
a    手扌
b	 宀勹冫疒癶髟       八白貝鼻匕比卜
c	 釆巛彳             车車川长長镸厂臣辰齒赤虫寸 
d	丶                  大刀刂歹豆斗鬥鼎
e    氵水氺                儿二而
f    耳阝 纟糸糹匚匸      方非飛風缶  阜邑  
g	 廾                 广干甘高戈革艮工弓谷骨鼓瓜龜鬼鬲
h	 一                 父禾黑虍戶黃火灬
i    木
j	 己                 几卩巾斤金見角韭臼已己
k	 衤竹凵衣  
l	 丨月              老耂里力立隶耒龍鹵卤鹿 
m	  冖               麻马馬麦麥毛矛門门米面皿黽目毋
n	 鸟鳥牛女
o    口
p	 石丿爻爿殳           皮片 
q	 酉                犬犭 齐齊气欠青
r	 雨                入日曰肉
s	 罒彡厶豕          示礻色山舌身生尸十食饣矢士氏首黍鼠水
t	 冂禸亠            田土  
u    艹艸屮
v    人亻乙亅
w	 攵攴              王玉无网瓦囗韋文韦  
x	 襾西彐彑          夕舛香小心忄玄辛穴血
y	 廴尢讠黹          牙言羊幺頁衣弋音又聿肀用魚羽龠  
z	 辵辶疋夂夊        支止至豸舟爪隹子孑自走足 
```

利用双拼加部首码，就可以组成三码字（三位编码的常用字）。
例如“软”，编码为rrc，“rr”是双拼，“c”是车的部首码。

![rrc](https://raw.githubusercontent.com/whhq/plmsrf/master/jtg_tuw/rrc.png)

* 3、字频号（第四位码）顺序编排顺序

GB2312字符集6700多常用字字频排位顺序：（预留ab字母）
p、c、d、e、f、g、h、i、j、k、l、m、n、o
例如“键”，由于“jjj”被“见”字占用，就加第四码p编码。

![jjjp](https://raw.githubusercontent.com/whhq/plmsrf/master/jtg_tuw/jjjp.png)

GBK字符集非常用字、繁体字和GB18030其它汉字第四位码字频排位顺序：（预留r字母）
q、s、t、u、v、w、x、y、z、o、n、m、l、k、j、i、h、g
例如“盤”字，不在GB2312字符集，第四码用q编码。

![plmq](https://raw.githubusercontent.com/whhq/plmsrf/master/jtg_tuw/plmq.png)


* 4、特定三码字
《通用规范汉字表》一级字表中的3500个常用字，如果是四码的，指定一个还未占用的三码作为该字的另一个编码。
例如“子ziz ,自zizp，字zizc，孜zizd，趑zize”，其中“自”和“字”是常用字，指定编码“自zip”，“字zid”，以提高输入效率。

* 5、输入中文
单字可用双拼二码选同音字，也可直接输入普逻码三码、四码打字。
词组可输入双拼选取。
四字成语和诗句可打简拼选取。
 
* 6、输入英文
点击“中”“英”可切换输入中英文。
 
* 7、九宫格输入

点击“九键”，可进入九宫格键盘，输入数字编码可打出汉字，也可在“全键”下直接输入数字打中文。
英文字母数字码转换:
```
a=21 b=22 c=23
d=31 e=32 f=33
g=41 h=42 i=43
j=51 k=52 l=53
m=61 n=62 o=63
p=71 q=72 r=73 s=74
t=81 u=82 v=83
w=91 x=92 y=93 z=94
```

九宫格全码,编码用数字表示,如普“pur”用数字编码为“718273”，译“yiyp”数字全码为“93439371”。
数字全码无重码，可直接打出想要的字。

![pur_iuma](https://raw.githubusercontent.com/whhq/plmsrf/master/jtg_tuw/pur_iuma.png)

九宫格简码
例如 普“pur”,p在7键,u在8键,r数字码为73,输入“7873”后出现3个字,选要打的字就可以了。

* 8、普逻码目前可应用于多个输入法平台和软件，其中包括：
在Trime2同文安卓输入法平台，实现了全键盘和九宫格键盘输入，可全码、双拼、简拼混合输入，超570万词库也不会卡。

普逻码的无重码特点，在Rime和同文3输入法平台，可轻松实现整句无差错输入，这是拼音云输入法一直追求的梦想。
在小小输入法平台，普逻码可以配置成三码自动上屏，四码空格上屏的类似顶功输入法功能。

在很多输入法里，可通过自定义短语功能，加入普逻码。再通过自定义双拼方案，使用普逻码双拼，让云输入法的功能更强大。
其中包括百度pc和手机输入法，华宇拼音，win10微软拼音，搜狗pc版等。
