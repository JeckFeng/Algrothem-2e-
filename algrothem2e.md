# Ŀ¼
<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [Ŀ¼](#Ŀ¼)
- [<font color='#9c6680'>1. algorithm 2e  ���ѧϰ</font>](#font-color9c66801-algorithm-2e-���ѧϰfont)
- [<font color='#9c6680'>2. How to use it?</font>](#font-color9c66802-how-to-use-itfont)
- [<font color='#9c6680'>3. Here is a quick example</font>](#font-color9c66803-here-is-a-quick-examplefont)
	- [<font color='#94a657'>��һ�����ӵĽ���</font>](#font-color94a657��һ�����ӵĽ���font)
- [<font color='#9c6680'>4. �ڶ��� example</font>](#font-color9c66804-�ڶ���-examplefont)
	- [<font color = '#94a657'>�ڶ������ӵĽ���</font>](#font-color-94a657�ڶ������ӵĽ���font)
- [<font color="#9c6680">5. If-else�ĺ�����</font>](#font-color9c66805-if-else�ĺ�����font)
	- [<font color='#94a657'>If ��Else��������������±���ʾ��</font>](#font-color94a657if-��else��������������±���ʾfont)
- [<font color="#9c6680">6. Forѭ���ĺ�����</font>](#font-color9c66806-forѭ���ĺ�����font)
	- [<font color='#94a657'>Forѭ����������������±���ʾ��</font>](#font-color94a657forѭ����������������±���ʾfont)
- [<font color="#9c6680">7. Whileѭ���ĺ�����</font>](#font-color9c66807-whileѭ���ĺ�����font)
	- [<font color='#94a657'>whileѭ�������ʹ�ã�</font>](#font-color94a657whileѭ�������ʹ��font)
- [<font color="#9c6680">8. ע�ͺ�����</font>](#font-color9c66808-ע�ͺ�����font)
	- [<font color='#94a657'>`\tcp{}` ��`\tcc{}`�Ĳ�ͬ��</font>](#font-color94a657tcp-��tcc�Ĳ�ͬfont)
	- [<font color='#94a657'>`\tcp{}` ��`\tcp*[options]{}`�Ĳ�ͬ��</font>](#font-color94a657tcp-��tcpoptions�Ĳ�ͬfont)
- [<font color="#9c6680">9. �Զ��庯��Function</font>](#font-color9c66809-�Զ��庯��functionfont)
	- [<font color='#94a657'>`\SetKwFunction{KwFn}{Fn}`����</font>](#font-color94a657setkwfunctionkwfnfn����font)
	- [<font color='#94a657'>`\SetKwProg{Prog}{Title}{is}{end}`����</font>](#font-color94a657setkwprogprogtitleisend����font)
	- [<font color='#94a657'>��Ӧ��ͬ����ĺ�����ʽ</font>](#font-color94a657��Ӧ��ͬ����ĺ�����ʽfont)
	- [<font color='#94a657'>��`\SetKwProg`������������</font>](#font-color94a657��setkwprog������������font)
	- [<font color='#94a657'>�������㷨��ֻ������һ��������ʱ</font>](#font-color94a657�������㷨��ֻ������һ��������ʱfont)
- [<font color="#9c6680">10.�㷨����������� </font>](#font-color9c668010�㷨�����������-font)
	- [<font color='#94a657'> `Input - Ouput`���͵ĺ�����</font>](#font-color94a657-input-ouput���͵ĺ�����font)
	- [<font color='#94a657'>  `Data - Result`���͵ĺ�����</font>](#font-color94a657-data-result���͵ĺ�����font)
- [<font color="#9c6680">11.�����Լ��Ĺؼ��ʵĻ������� </font>](#font-color9c668011�����Լ��Ĺؼ��ʵĻ�������-font)
	- [<font color='#94a657'> `\SetKw{Kw}{text}` ʾ��</font>](#font-color94a657-setkwkwtext-ʾ��font)
	- [<font color='#94a657'> `\SetKwHangingKw{HData}{Data}` ʾ��</font>](#font-color94a657-setkwhangingkwhdatadata-ʾ��font)
	- [<font color='#94a657'>`\SetKwData{Left}{left}` ʾ��</font>](#font-color94a657setkwdataleftleft-ʾ��font)
	- [<font color='#94a657'>`\SetKwArray{KwAarray}{array}` ʾ��</font>](#font-color94a657setkwarraykwaarrayarray-ʾ��font)
- [<font color="#9c6680">12.Algorithm2e����л����ؼ��ʺͻ�����ṹ </font>](#font-color9c668012algorithm2e����л����ؼ��ʺͻ�����ṹ-font)
- [<font color="#9c6680">13.��Algorithm2e�����ʹ������ </font>](#font-color9c668013��algorithm2e�����ʹ������-font)
- [<font color="#9c6680">14.�㷨���� </font>](#font-color9c668014�㷨����-font)
	- [`\caption{}`����](#caption����)
	- [`ruled`options](#ruledoptions)
	- [�޸��㷨�ı��](#�޸��㷨�ı��)
	- [�޸��㷨�Ĺؼ���](#�޸��㷨�Ĺؼ���)
- [<font color="#9c6680">δ�����... </font>](#font-color9c6680δ�����-font)

<!-- /TOC -->

***
---

# <font color='#9c6680'>1. algorithm 2e  ���ѧϰ</font>

---
# <font color='#9c6680'>2. How to use it?</font>
- ��֮ǰ`\begin{document}`����Ҫ����algorithm 2e��`usepackage[options]{algorithm2e}`,�Լ�����������
 `\def\SetClass{article}`,  `\documentclass{\SetClass}`��

- `[options]`ѡ����`ruled`,`linesnumbered`,`boxed`:


    - `ruled`:���ñ�����ʾ�����棬�����㷨�ı����������档


    - `linesnumbered`:���㷨����ʾ�кš�


    - `boxed`:���㷨�Ű�ʱ������һ��������
---
# <font color='#9c6680'>3. Here is a quick example</font>
��Ӧ��tex�ļ� `E:\markdown�ʼ�\Algrothem 2e ���ѧϰ\tex�ļ�\2e_test1.tex`

![20220719_235022_40](image/20220719_235022_40.png)
## <font color='#94a657'>��һ�����ӵĽ���</font>
Very important ������
- each line MUST end with `\;`���һ��Զ����У����������ÿ��ĩβ��`;`�������������`\DontPrintSemicolon`  ;`\PrintSemicolon`�������ÿ��ĩβ��ӡ��`;`

- only those with a macro beginning a block should not end with `\;`  ��macro--> �꡿

- ��Ҳ������`\;`�������ѧģ���У�����һС��ռ�

- `caption{}`ѡ��Ӧ�÷���ĩβ��`caption{}`��������ݾ�������㷨����
- ����`\SetAlgoNoLine`����������㷨��û�����ߣ�����ͼ��ʾ��

   ![20220720_153737_97](image/20220720_153737_97.png)
- ����`\SetAlgoLined`����������㷨�������ߣ�����ͼ��ʾ��

   ![20220720_153921_25](image/20220720_153921_25.png)
- ��������`\SetAlgoVlined`���������㷨�������ߣ�����ͼ��ʾ��

   ![20220720_154205_63](image/20220720_154205_63.png)

ע��Ƚ�`\SetAlgoNoLine`��`\SetAlgoLined`��`\SetAlgoVlined`���������ֻ�����һ�������ʹ��if-else,��while��block��û��`end`��Ϊ��β

---
- While ��䣺ʹ������`While{����}{���}`������ͼ��ʾ��

  ![20220720_163110_78](image/20220720_163110_78.png)

- if-else��䣺ʹ������`eIf{����}{if �µ����}{else�µ����}`������ͼ��ʾ��

   ![20220720_163225_22](image/20220720_163225_22.png)
- while�������Ƕif-else��䣬�ĸ�ʽ����ͼ��ʾ��

  ![20220720_163446_88](image/20220720_163446_88.png)

---
# <font color='#9c6680'>4. �ڶ��� example</font>
��Ӧ��tex�ļ� `E:\markdown�ʼ�\Algrothem 2e ���ѧϰ\tex�ļ�\2e_test2.tex`

![20220720_002704_21](image/20220720_002704_21.png)

![20220720_002728_58](image/20220720_002728_58.png)
## <font color = '#94a657'>�ڶ������ӵĽ���</font>
- ������㷨�м�ע�ͣ�
  - ע���﷨1Ϊ `\tcp[options]{}`  ע�͵���ʽΪ��`//`������ͼ��ʾ

    ![20220720_145914_34](image/20220720_145914_34.png)

  - ע���﷨2Ϊ `��tcc[options]{}`  ע�͵���ʽΪ��`/*`������ͼ��ʾ

     ![20220720_145956_69](image/20220720_145956_69.png)
  - ��if��ʹ��ע��ʱ, `\If(tcc{ע��}){����}`


- ��ӿհ������� `\BlankLine`�����������������Ҫ����հ��еĵط�


- `\emph{}`���������ʾб��

- ��ͨ�����ֱ��д�������Ҫ������Ҫ�����������`\`����

- `\IncMargin{1em}`���ʹ���кŲ�����ͻ��

---




# <font color="#9c6680">5. If-else�ĺ�����</font>
## <font color='#94a657'>If ��Else��������������±���ʾ��</font>
| IF 	| Else 	|
|:--:	|:----:	|
| `\If{condition}{then block}`   	|   `Else{else block }`   	|
|   `\uIf{condition}{then block without end }`   	|    `uElse{else block without end }`   	|
|    `\lIf{condition}{then's line text }` 	|  `lElse{else's line text}`     	|
|    `\ElseIf{condition}{elseif block }` 	|      	|
|    `\uElseIf{condition}{elseif block without end }` 	|      	|
|    `\lElseIf{condition}{elseif's line text  }`	|      	|
|    `\eIf{condition}{then block }{else block  }` 	|      	|
|    `\leIf{condition}{then block }{else block  }` 	|      	|

If-Else��Ƕ��ʹ�ã�

---
- `\eIf(comment){condition}{then block }{else block  }` ��

	![20220721_092100_65](image/20220721_092100_65.png)

	![20220721_092137_28](image/20220721_092137_28.png)

---
-  `\If{condition}{then block}`   :

	![20220721_092334_84](image/20220721_092334_84.png)

	![20220721_092402_71](image/20220721_092402_71.png)

---
- `\lIf{condition}{then's line text }` :

	![20220721_092824_26](image/20220721_092824_26.png)

	![20220721_092850_17](image/20220721_092850_17.png)

---
- `\leIf{condition}{then block }{else block  }`  :

	![20220721_093239_80](image/20220721_093239_80.png)

	![20220721_093309_59](image/20220721_093309_59.png)

---
- ���If-Else�ṹǶ��ʹ�ã�

	![20220721_093555_27](image/20220721_093555_27.png)

	![20220721_093430_14](image/20220721_093430_14.png)

---
- ���If-Else�ṹǶ��ʹ��2��

	![20220721_093703_22](image/20220721_093703_22.png)

	![20220721_093723_54](image/20220721_093723_54.png)

---
��Ӧ��tex�ļ�ʾ����`E:\markdown�ʼ�\Algrothem 2e ���ѧϰ\tex�ļ�\IF_Else.tex`

---

# <font color="#9c6680">6. Forѭ���ĺ�����</font>
## <font color='#94a657'>Forѭ����������������±���ʾ��</font>
|for loop 	|
|:----:	|
| `\For{loop's condition}{For's text}`	|
| `\For{loop's condition}{For's text (comment)}`	|
| `\lFor{loop's condition}{For's text}`	|
| `\lFor*{loop's condition}{For's text}`	|
| `\ForAll{loop's condition}{For's text}`	|
| `\ForEach{loop's condition}{For's text}`	|

Forѭ����ʹ�ã�

---
- `\For{loop's condition}{For's text}` :

	![20220720_215153_29](image/20220720_215153_29.png)

	![20220720_215734_24](image/20220720_215734_24.png)

---
- `\lFor{loop's condition}{For's text}` :

	![20220720_215502_97](image/20220720_215502_97.png)

	![20220720_215818_41](image/20220720_215818_41.png)

---
- `\lFor*{loop's condition}{For's text}` :

	 ![20220720_215425_95](image/20220720_215425_95.png)

	 ![20220720_215845_87](image/20220720_215845_87.png)

---
- `\ForAll{loop's condition}{For's text}`��

	 ![20220720_215604_50](image/20220720_215604_50.png)

   ![20220720_215911_85](image/20220720_215911_85.png)

---
- `\ForEach{loop's condition}{For's text}` :

	![20220720_215629_35](image/20220720_215629_35.png)

	![20220720_215939_68](image/20220720_215939_68.png)

---
- ����Forѭ��Ƕ�ף�

	![20220720_220129_71](image/20220720_220129_71.png)

	![20220720_220106_71](image/20220720_220106_71.png)

---
��Ӧ��tex�ļ�ʾ����`E:\markdown�ʼ�\Algrothem 2e ���ѧϰ\tex�ļ�\For_loop.tex`


---

# <font color="#9c6680">7. Whileѭ���ĺ�����</font>
- algorithm2e ����õ�whileѭ������Ϊ��`\While{}{}`
- algorithm2e ��û��`do-while`�ṹ�ĺ�����������Զ���

## <font color='#94a657'>whileѭ�������ʹ�ã�</font>
- `\While{}{}` ��

	![20220721_095410_25](image/20220721_095410_25.png)

	![20220721_095540_86](image/20220721_095540_86.png)

- While ѭ����If-Else�ṹǶ�ף�

	![20220721_100540_21](image/20220721_100540_21.png)

	![20220721_100517_17](image/20220721_100517_17.png)

- While , If-else and For Ƕ��ʹ�ã�

	![20220721_102644_34](image/20220721_102644_34.png)

	![20220721_102658_55](image/20220721_102658_55.png)

---
��Ӧ��tex�ļ�ʾ����`E:\markdown�ʼ�\Algrothem 2e ���ѧϰ\tex�ļ�\While.tex`

---

# <font color="#9c6680">8. ע�ͺ�����</font>
��Algorithm2e����У�ע����������������¼��֣�

| tcc 	| tcp 	|
|:---:	|:---:	|
|   `\tcc{}`  	|   `\tcp{}`   	|
|   `\tcc*[l]{}`   	|   `\tcp*[l]{}`   	|
|   `\tcc*[r]{}`   	|    `\tcp*[r]{}`  	|
|   `\tcc*[h]{}`   	|    `\tcp*[h]{}`  	|
|   `\tcc*[f]{}`   	|    `\tcp*[f]{}`  	|

## <font color='#94a657'>`\tcp{}` ��`\tcc{}`�Ĳ�ͬ��</font>
`\tcp`��ע����ʽΪ��`//`������ͼ��ʾ��

![20220721_125300_16](image/20220721_125300_16.png)

`\tcc`��ע����ʽΪ��`/*  */`������ͼ��ʾ��

![20220721_125248_35](image/20220721_125248_35.png)

## <font color='#94a657'>`\tcp{}` ��`\tcp*[options]{}`�Ĳ�ͬ��</font>
-  `\tcc{}`:  ע����䵥��һ�У�ע�����ǰ��`;`����ĩ��`;`

	![20220721_125846_22](image/20220721_125846_22.png)
	![20220721_125735_26](image/20220721_125735_26.png)

-  `\tcc*[l]{}`:ע��������룬ע�����ǰ��`;`

	![20220721_130141_58](image/20220721_130141_58.png)
	![20220721_130124_74](image/20220721_130124_74.png)

-  `\tcc*[r]{}`:ע������ҿ��룬ע�����ǰ��`;`

	![20220721_130243_73](image/20220721_130243_73.png)
	![20220721_130232_30](image/20220721_130232_30.png)

-  `\tcc*[h]{}`:ע��������룬ע�����ǰ��`;`����ĩ��`;`

	![20220721_130421_46](image/20220721_130421_46.png)
	![20220721_130451_20](image/20220721_130451_20.png)

-  `\tcc*[f]{}`:ע������ҿ��룬ע�����ǰ��`;`����ĩ��`;`

	![20220721_130503_66](image/20220721_130503_66.png)
	![20220721_130516_18](image/20220721_130516_18.png)

`\tcp`�����options��������ͬ

- **Please note that��**

	- ����IF-Else,While�� block Ƕ��ʹ��ʱ��ֻ��Ƕ�� `\tcc*[h]{}`��`\tcc*[f]{}`����
	- һ����䵥��һ��ʱ��ֻ��ʹ�� `\tcc{}`����
	- ��Ҫ��һ����ͨ�����������ע��ʱ����ʹ�� `\tcc*[l]{}`�� `\tcc*[r]{}`����

# <font color="#9c6680">9. �Զ��庯��Function</font>

## <font color='#94a657'>`\SetKwFunction{KwFn}{Fn}`����</font>
`\SetKwFunction{KwFn}{Fn}`��Ҫ��������һ����������

`KwFn`Ϊtex�ڶ���Ĺؼ��֣�{Fn}Ϊpdf����ʵ��ʾ�Ĺؼ��֡����У�`KwFn`�ؼ��ֵ����ƿ�������������{Fn}Ϊ��pdf�ĵ�����Ҫ�ĺ������ƣ�һ��ΪFunction��Def��

## <font color='#94a657'>`\SetKwProg{Prog}{Title}{is}{end}`����</font>
 `\SetKwProg{Prog}{Title}{is}{end}`������д�����ľ���ʵ��

 `Prog`Ϊ�ؼ��֣�`Title`Ϊ��pdf�ĵ��еĺ�����ǩ��
 `is`��pdf�ĵ��У��������ֺ������ӱ�ǩ��`end`��ʾ�ú�����`end`��β

 ## <font color='#94a657'>�Զ��庯��������</font>

 ---
 - ����һ��`Function`����
 	- step1. ����ú�����һ���������ƣ�
	![20220721_163001_79](image/20220721_163001_79.png)
	`Fsum`Ϊ������дtex������Ҫ���õĹؼ��֣���`Sum`ΪPDF�ĵ��������ֵĺ�������

	- step2. ʵ�־���ĺ������ܣ�
	![20220721_163146_42](image/20220721_163146_42.png)
	- �����Ķ���һ�������Ĵ������£�
	![20220721_163334_01](image/20220721_163334_01.png)
	![20220721_163432_13](image/20220721_163432_13.png)

---
- ����һ��`Def`����
	- step1. ����ú�����һ���������ƣ�
	![20220721_164127_90](image/20220721_164127_90.png)

	- step2. ʵ�־���ĺ������ܣ�
	![20220721_164150_77](image/20220721_164150_77.png)

	- �����Ķ���һ�������Ĵ������£�
	![20220721_164222_68](image/20220721_164222_68.png)
	![20220721_164239_54](image/20220721_164239_54.png)

ͬ������붨��һ����ǩΪ`Main`�ĺ�����ֻ��Ҫ�޸�`\SetKwProg{Prog}{Title}{is}{end}`����ĵڶ��������ŵ�����Ϊ`Main`
��������ʾ��
![20220721_164627_74](image/20220721_164627_74.png)
![20220721_164644_69](image/20220721_164644_69.png)

## <font color='#94a657'>��Ӧ��ͬ����ĺ�����ʽ</font>
- ��`end`��β��Function
	- ���룺

		![20220721_175635_55](image/20220721_175635_55.png)
	- Ч����

		![20220721_175707_66](image/20220721_175707_66.png)
	- <font color='red'>Note!  </font>�� `\SetKwProg{Prog}{Title}{is}{}`����ĵ��ĸ������ſ��ž���.
---

- ��`end`��β��Function
	- ���룺

	![20220721_175906_93](image/20220721_175906_93.png)

	- Ч����

	![20220721_175922_17](image/20220721_175922_17.png)

	- <font color='red'>Note!  </font>������������ı䣬����Ҫ��`End`��β,������ `\SetKwProg{Prog}{Title}{is}{End}`�ĵ��ĸ�����������Ϊ`End`.
---

- ��`return`��β��Function
	- ���룺

	![20220721_180151_70](image/20220721_180151_70.png)

	- Ч����

	![20220721_180207_36](image/20220721_180207_36.png)

---

	- <font color='red'>Note!  </font>�����ȣ�return��Algorithm2e�еĹؼ���Ϊ`\KwRet`����Σ������� `\SetKwProg{Prog}{Title}{is}{\KwRet{}}`�ĵ��ĸ������ŵ�����Ϊ`\KwRet` �Һ������ڲ�Ҳ��`\KwRet`�ؼ��֣�������return������ʾ��

	![20220721_181428_27](image/20220721_181428_27.png)
	![20220721_181507_47](image/20220721_181507_47.png)

---

- Function is ��ʽ
	- ���룺

	![20220721_180324_79](image/20220721_180324_79.png)

	- Ч����

	![20220721_180341_94](image/20220721_180341_94.png)

---

- Function ����ʽ
	- ���룺

	![20220721_180504_64](image/20220721_180504_64.png)

	- Ч����

	![20220721_180451_69](image/20220721_180451_69.png)

---

## <font color='#94a657'>��`\SetKwProg`������������</font>
- ���룺


![20220721_185650_25](image/20220721_185650_25.png)

- Ч����


![20220721_185730_25](image/20220721_185730_25.png)

---

-  <font color='red'>Note!  </font>���������ں������ڲ�����return,������return����Ӵ֣�Ӧ��ʹ��algorithm2e�Ĺؼ���`\KwRet`����Σ����������ĺ����ĺ���������б��ģ���Ȼ���ַ�������㣬����Ҫ�õ�`\SetKwFunction`���������ѡ��ʹ�����ַ�����������


## <font color='#94a657'>�������㷨��ֻ������һ��������ʱ</font>

�������㷨��ֻ������һ����������������ʵ�ָú����ľ��庯����ʱ��Ҳ���Բ���`\SetKwFunction`��������������һ���������ơ�
- ���룺

![20220721_190848_02](image/20220721_190848_02.png)

- Ч����

![20220721_190901_45](image/20220721_190901_45.png)

---

�������������Ӷ�Ӧ��tex�ļ�Ϊ��`E:\markdown�ʼ�\Algrothem 2e ���ѧϰ\tex�ļ�\Function\Function.tex`

---

# <font color="#9c6680">10.�㷨����������� </font>
�������г�����������������֣�
- ��һ�֣�`Input - Ouput`���ͣ�����ͼ��ʾ��
	- Ч��ͼ��
	![20220721_194833_94](image/20220721_194833_94.png)
	- ���룺

		![20220721_195228_85](image/20220721_195228_85.png)

- �ڶ��֣� `Data - Result`���ͣ�����ͼ��ʾ��
	- Ч��ͼ��
	![20220721_194851_96](image/20220721_194851_96.png)
	- ���룺
		![20220721_195203_49](image/20220721_195203_49.png)
---

##  <font color='#94a657'> `Input - Ouput`���͵ĺ�����</font>
`Input - Ouput`�����漰�ĺ�������Ҫ��������
- `\SetKwInput{KwInput}{Input}`
- `\KwInput{input text}`
- `\KwOutput{output text}`


`\SetKwInput{KwInput}{Input}`�ĵ�һ���������е�����`KwInput`��ҪΪд��������ʹ�õĺ�����ڶ��������ŵ�����`Input`Ϊpdf�ĵ��У�����Ҫ��input��ǩ.���У���һ���������е����ݿ������⡣���Ƹ��Ի����������������������ӣ�

---
- �������ҪСдinput
	- ���룺

		![20220721_200233_98](image/20220721_200233_98.png)

	- Ч��ͼ��

		![20220721_200244_85](image/20220721_200244_85.png)

---
- �������Ҫ��д��input
	 - ���룺

	 	![20220721_200406_35](image/20220721_200406_35.png)

	 - Ч��ͼ��

	 	![20220721_200418_35](image/20220721_200418_35.png)

---

`\KwInput{input text}`��Ҫʵ�ֵ��ǣ�ʵ�����㷨�е��������ݣ��������е����ݾ������㷨����������

`\KwOutput{output text}`��Ҫʵ�ֵ��ǣ�ʵ�����㷨�е�������ݣ��������е����ݾ������㷨���������


<font color='red'>Note!  </font>������`Input - Ouput`���͵����������������ͨ��`\SetKwInput{KwInput}{Input}`���ָ��input�ı�ǩ����ʹ��`\KwInput{input text}`��`\KwOutput{output text}`����ʵ�����㷨�������������

һ�������Ĺ���`Input - Output`�Ĵ��룺
![20220721_201100_79](image/20220721_201100_79.png)

##  <font color='#94a657'>  `Data - Result`���͵ĺ�����</font>
 `Data - Result`���͵ĺ����������`Input - Ouput`���͵ĺ�������򵥡�

 �����㷨��Data,ֻ��Ҫ`\KwData{ data text}`���

 �����㷨��Result��ֻ��Ҫ`\KwResult{result text}`����

 һ�������Ĺ���`Input - Output`�Ĵ��룺
![20220721_201510_20](image/20220721_201510_20.png)

�������������Ӷ�Ӧ��tex�ļ�Ϊ��`E:\markdown�ʼ�\Algrothem 2e ���ѧϰ\tex�ļ�\Input_and_Ouput\InputAndOuput.tex`

# <font color="#9c6680">11.�����Լ��Ĺؼ��ʵĻ������� </font>

�˴�������ϸ���⣬��Ϊ�������ò���

��Algorithm2e����У������Լ��Ĺؼ��ʵķ�����һ�¼��֣�
| Macro command 	| definition	|
|:---:	|:---:	|
| `\SetKw{Kw}{text}`	|which define a keyword `text`|
| `\SetKwHangingKw{HData}{Data}`	|which define a hanging keyword `Data`	|
| `\SetKwData{Left}{left}`	| which define a data text `left`.	|
| `\SetKwArray{KwAarray}{array}`	|`which define an array keywords`	|

## <font color='#94a657'> `\SetKw{Kw}{text}` ʾ��</font>
- ���룺

	![20220721_211320_50](image/20220721_211320_50.png)

- Ч����

	![20220721_211329_46](image/20220721_211329_46.png)

## <font color='#94a657'> `\SetKwHangingKw{HData}{Data}` ʾ��</font>
- ���룺

	![20220721_211403_27](image/20220721_211403_27.png)

- Ч����

	![20220721_211416_11](image/20220721_211416_11.png)

##  <font color='#94a657'>`\SetKwData{Left}{left}` ʾ��</font>
- ���룺

	![20220721_211428_31](image/20220721_211428_31.png)

- Ч����

	![20220721_211436_95](image/20220721_211436_95.png)

##  <font color='#94a657'>`\SetKwArray{KwAarray}{array}` ʾ��</font>
- ���룺

	![20220721_211450_25](image/20220721_211450_25.png)

- Ч����

	![20220721_211500_38](image/20220721_211500_38.png)

�������������Ӷ�Ӧ��tex�ļ�Ϊ��`E:\markdown�ʼ�\Algrothem 2e ���ѧϰ\tex�ļ�\Keywords\keywords.tex`

#  <font color="#9c6680">12.Algorithm2e����л����ؼ��ʺͻ�����ṹ </font>

---

- �ؼ��ʣ�`to`
	- ���룺

		![20220721_212723_62](image/20220721_212723_62.png)

		- Ч����

			![20220721_212734_97](image/20220721_212734_97.png)

---

- �ؼ��ʣ�`return`
	- ���룺

		![20220721_212802_82](image/20220721_212802_82.png)

		- Ч����

			![20220721_212813_66](image/20220721_212813_66.png)

<font color='red'> Note!  </font>�� ò��`\KwRet{}`��`\Return{}`���ߵ�Ч��һ��

---

- ��ṹ��begin
	- ���룺

		![20220721_212843_57](image/20220721_212843_57.png)

		- Ч����

			![20220721_212900_14](image/20220721_212900_14.png)


�������������Ӷ�Ӧ��tex�ļ�Ϊ��`E:\markdown�ʼ�\Algrothem 2e ���ѧϰ\tex�ļ�\Basic_Kw\basicKw.tex`

# <font color="#9c6680">13.��Algorithm2e�����ʹ������ </font>

���㷨���������ģ�ֻ��Ҫ��`\begin{document}`֮ǰ���һ�������ɣ�
`\usepackage[GBK]{ctex}  `

<font color='red'> Note!  </font>����������������������Գ��԰�`[GBK]`����`[UTF-8]`.

# <font color="#9c6680">14.�㷨���� </font>
## `\caption{}`����
`\caption{}`�������ڵ����ݼ�Ϊ������㷨����


## `ruled`options

��`\usepackage[linesnumbered,lined,ruled,boxed]{algorithm2e}`�����У�`ruled`��ʾ�㷨�ı������㷨���Ϸ���������`ruled`ʱ��Ĭ���㷨�ı���λ���㷨���·���

��������������ʾ��

- ���룺

![20220722_110618_00](image/20220722_110618_00.png)

- Ч����

![20220722_110558_84](image/20220722_110558_84.png)


- ���룺

![20220722_110733_25](image/20220722_110733_25.png)

- Ч����

![20220722_110723_90](image/20220722_110723_90.png)

## �޸��㷨�ı��

�޸��㷨�ı�������ַ�ʽ
-  `\renewcommand{\thealgocf}{number}` ,`number`Ϊ�޸ĵ��㷨���
-  `\SetAlgoRefName{number}`,`number`Ϊ�޸ĵ��㷨���

## �޸��㷨�Ĺؼ���

ʹ��`\renewcommand{\algorithmcfname}{�㷨�ؼ���}`�����޸��㷨�Ĺؼ���

����������ʾ��
- ���룺

![20220722_111354_45](image/20220722_111354_45.png)

- Ч����

![20220722_111342_57](image/20220722_111342_57.png)


# <font color="#9c6680">δ�����... </font>
