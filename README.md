 

# 传统蒙古文信息交换与处理字形字符编码字符集

 

  编者按：文中蒙古文的编码用的是本文公布的字形字符编码标准，读者在本地PC机（手机）上安装ᠬᠠᠮᠤᠭ ᠮᠣᠩᠭᠤᠯ（蒙古文万码字库）字库就可以在本地机器上正确显现蒙古文文字，字库文件名:HMK.TTF,字体名称：HMK Hamvg Mongol KQD.

  ***\*本团队开源地址：\****[https://github.com/qidehua63/MongolianCode](https://github.com/qidehua63/MongolianCode)

 

传统蒙古文字形字符研究团队公开发布团队标准1号（The Team Standard No.1）

 

## 一、 标准代号与名称

代号： TmSd AEI768 Ver 0.1.0

名称：《传统蒙古文信息交换与处理字形字符编码字符集》团队标准（简称《字形字符编码》团队标准）0.1.0版。



## 二、 标准的应用范围

TmSd AEI768 Ver 0.1.0为试用版本，目的是检验其在实际应用中的效果。虽然我团队对各种应用场景进行了丰富的模拟想象，但还是未经过广大用户的实践检验。我们希望在广大用户充分实践的基础上继续改进字形编码标准。

为了广大用户充分检验TmSd AEI768 Ver 0.1.0，在此标准上开发系统平台和应用系统，总结其应用效果，我团队尽最大可能保持TmSd AEI768 Ver 0.1.0的稳定性，在充分评估其应用结果后，做出版本是否升级的决策。

确定1.0.0版本是为广大用户提供的是应用版本，1.0.0之前的版本均为试用版本。

为了加快《字形编码》完善进度，本次发布的是TmSd AEI768-2020 Ver 0.1.0的核心内容，包括编码字符集及使用说明，另文发布TmSd AEI768-2020 Ver 0.1.0的完整内容。



### 三、 《传统蒙古文信息交换与处理字形字符编码》字符集及使用说明

1. TmSd AEI768 Ver 0.1.0文字部分,文字字形拆解规则是以蒙古文文字的标音特征，按音拆解为字形字符，其规律为：字符皆有音，有音必有形，重音不重形，一形对一码。

TmSd AEI768-2020 Ver 0.1.0文字部分按蒙古文读音排序：①按字头排②同音按单独、上、末形排；③再者参考前接字符。

2. 《传统蒙古文信息交换与处理字形字符标准编码》字符集如表1

![img](https://github.com/qidehua63/MongolianCode/blob/master/code.png)



 

3. 《字形编码》字符使用说明

   3.1 在《字形编码》字符集中没有编入传统蒙古文的标点符号。在按蒙古文竖排习惯显现输出传统蒙古文的标点符号时，引用国家标准GB/T 25914第10.1和10.2之条款规定；在按西文从左到右文种混合横排习惯时，请参考横排蒙古文规则显现输出传统蒙古文的标点符号。

   3.2 《字形编码》字符集字符使用详细说明（略）

## 四、 用户测试重点

《字形编码》字符集制定的好坏，对于蒙古文电子化、信息化、数字化、人工智能以及未来发展具有深远的影响。然而，《字形编码》字符集制定的好坏，是由字符集所选择字符是否合理和字符集字符排序是否合理两个因素决定。

所以，请大家重点检验以下几个方面：

1.重码问题：重码是有多余字符的表现，用户在录入、修改、信息处理时会产生难以选则哪一个字符的情况。TmSd  AEI768-2020 Ver 0.1.0中的![img](http://music.suyetech.com\gitimgimage-20200801083041926.png) ![image-20200801083331311](music.suyetech.com/gitimgimage-20200801083331311.png)![image-20200801083422243](music.suyetech.com/gitimgimage-20200801083422243.png)![image-20200801083514074](music.suyetech.com/gitimgimage-20200801083514074.png)![image-20200801083541454](music.suyetech.com/gitimgimage-20200801083541454.png)![image-20200801083614062](music.suyetech.com/gitimgimage-20200801083614062.png)都是一些字形相近的字符，除此之外有重码隐患字符是组合字，如：![image-20200801083642767](music.suyetech.com/gitimgimage-20200801083642767.png)等诸如此类问题

2.缺字符问题：用户在录入、修改、信息处理时会产生找不到用哪一个字符的情况；

3.排序问题：用户在文字列表和信息处理列表时会产生难以接受的列表。

4.未尽事宜：即是团队呢意见分歧较大的事情，需要在实践中检验、总结确定

①未能确定zhi,chi和附加成分yi是用文字的标音特征还是用文字的音节特征拆解文字来选择字符；有了如下两种选择方法：一是![image-20200801083759524](music.suyetech.com/gitimgimage-20200801083759524.png)(独立)，![image-20200801083824232](music.suyetech.com/gitimgimage-20200801083824232.png)(独立)，![image-20200801083855221](music.suyetech.com/gitimgimage-20200801083855221.png)(独立)，![image-20200801083908813](music.suyetech.com/gitimgimage-20200801083908813.png)(上)，![image-20200801083924108](music.suyetech.com/gitimgimage-20200801083924108.png)(末)，二是![image-20200801083941662](music.suyetech.com/gitimgimage-20200801083941662.png)(独立)，![image-20200801083952648](music.suyetech.com/gitimgimage-20200801083952648.png)(独立)，![image-20200801084002099](music.suyetech.com/gitimgimage-20200801084002099.png)(独立)，![image-20200801084009826](music.suyetech.com/gitimgimage-20200801084009826.png)(上)，![image-20200801084020610](music.suyetech.com/gitimgimage-20200801084020610.png)(末)；

②未能确定中形 ![image-20200801084039398](music.suyetech.com/gitimgimage-20200801084039398.png)᠊选一个字符还是两个都选。 

 

传统蒙古文字形字符研究团队

​              2020年8月1日星期六  
