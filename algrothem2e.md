# 目录
<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [目录](#目录)
- [<font color='#9c6680'>1. algorithm 2e  宏包学习</font>](#font-color9c66801-algorithm-2e-宏包学习font)
- [<font color='#9c6680'>2. How to use it?</font>](#font-color9c66802-how-to-use-itfont)
- [<font color='#9c6680'>3. Here is a quick example</font>](#font-color9c66803-here-is-a-quick-examplefont)
	- [<font color='#94a657'>第一个例子的解析</font>](#font-color94a657第一个例子的解析font)
- [<font color='#9c6680'>4. 第二个 example</font>](#font-color9c66804-第二个-examplefont)
	- [<font color = '#94a657'>第二个例子的解析</font>](#font-color-94a657第二个例子的解析font)
- [<font color="#9c6680">5. If-else的宏命令</font>](#font-color9c66805-if-else的宏命令font)
	- [<font color='#94a657'>If 和Else宏命令的种类如下表所示：</font>](#font-color94a657if-和else宏命令的种类如下表所示font)
- [<font color="#9c6680">6. For循环的宏命令</font>](#font-color9c66806-for循环的宏命令font)
	- [<font color='#94a657'>For循环宏命令的种类如下表所示：</font>](#font-color94a657for循环宏命令的种类如下表所示font)
- [<font color="#9c6680">7. While循环的宏命令</font>](#font-color9c66807-while循环的宏命令font)
	- [<font color='#94a657'>while循环命令的使用：</font>](#font-color94a657while循环命令的使用font)
- [<font color="#9c6680">8. 注释宏命令</font>](#font-color9c66808-注释宏命令font)
	- [<font color='#94a657'>`\tcp{}` 与`\tcc{}`的不同：</font>](#font-color94a657tcp-与tcc的不同font)
	- [<font color='#94a657'>`\tcp{}` 与`\tcp*[options]{}`的不同：</font>](#font-color94a657tcp-与tcpoptions的不同font)
- [<font color="#9c6680">9. 自定义函数Function</font>](#font-color9c66809-自定义函数functionfont)
	- [<font color='#94a657'>`\SetKwFunction{KwFn}{Fn}`命令</font>](#font-color94a657setkwfunctionkwfnfn命令font)
	- [<font color='#94a657'>`\SetKwProg{Prog}{Title}{is}{end}`命令</font>](#font-color94a657setkwprogprogtitleisend命令font)
	- [<font color='#94a657'>适应不同需求的函数样式</font>](#font-color94a657适应不同需求的函数样式font)
	- [<font color='#94a657'>以`\SetKwProg`单独创建函数</font>](#font-color94a657以setkwprog单独创建函数font)
	- [<font color='#94a657'>当你在算法中只想引用一个函数名时</font>](#font-color94a657当你在算法中只想引用一个函数名时font)
- [<font color="#9c6680">10.算法的输入与输出 </font>](#font-color9c668010算法的输入与输出-font)
	- [<font color='#94a657'> `Input - Ouput`类型的宏命令</font>](#font-color94a657-input-ouput类型的宏命令font)
	- [<font color='#94a657'>  `Data - Result`类型的宏命令</font>](#font-color94a657-data-result类型的宏命令font)
- [<font color="#9c6680">11.构造自己的关键词的基本方法 </font>](#font-color9c668011构造自己的关键词的基本方法-font)
	- [<font color='#94a657'> `\SetKw{Kw}{text}` 示例</font>](#font-color94a657-setkwkwtext-示例font)
	- [<font color='#94a657'> `\SetKwHangingKw{HData}{Data}` 示例</font>](#font-color94a657-setkwhangingkwhdatadata-示例font)
	- [<font color='#94a657'>`\SetKwData{Left}{left}` 示例</font>](#font-color94a657setkwdataleftleft-示例font)
	- [<font color='#94a657'>`\SetKwArray{KwAarray}{array}` 示例</font>](#font-color94a657setkwarraykwaarrayarray-示例font)
- [<font color="#9c6680">12.Algorithm2e宏包中基本关键词和基本块结构 </font>](#font-color9c668012algorithm2e宏包中基本关键词和基本块结构-font)
- [<font color="#9c6680">13.在Algorithm2e宏包中使用中文 </font>](#font-color9c668013在algorithm2e宏包中使用中文-font)
- [<font color="#9c6680">14.算法标题 </font>](#font-color9c668014算法标题-font)
	- [`\caption{}`命令](#caption命令)
	- [`ruled`options](#ruledoptions)
	- [修改算法的编号](#修改算法的编号)
	- [修改算法的关键字](#修改算法的关键字)
- [<font color="#9c6680">未完待续... </font>](#font-color9c6680未完待续-font)

<!-- /TOC -->

***
---

# <font color='#9c6680'>1. algorithm 2e  宏包学习</font>

---
# <font color='#9c6680'>2. How to use it?</font>
- 在之前`\begin{document}`，需要加载algorithm 2e包`usepackage[options]{algorithm2e}`,以及加入这两行
 `\def\SetClass{article}`,  `\documentclass{\SetClass}`，

- `[options]`选项有`ruled`,`linesnumbered`,`boxed`:


    - `ruled`:是让标题显示在上面，否则算法的标题则在下面。


    - `linesnumbered`:让算法中显示行号。


    - `boxed`:让算法排版时插入在一个盒子里
---
# <font color='#9c6680'>3. Here is a quick example</font>
对应的tex文件 `E:\markdown笔记\Algrothem 2e 宏包学习\tex文件\2e_test1.tex`

![20220719_235022_40](image/20220719_235022_40.png)
## <font color='#94a657'>第一个例子的解析</font>
Very important ！！！
- each line MUST end with `\;`，且会自动换行，如果不想在每行末尾有`;`，可以添加命令`\DontPrintSemicolon`  ;`\PrintSemicolon`命令会在每行末尾打印出`;`

- only those with a macro beginning a block should not end with `\;`  【macro--> 宏】

- 你也可以用`\;`命令，在数学模块中，创造一小块空间

- `caption{}`选项应该放在末尾；`caption{}`里面的内容就是你的算法名称
- 加入`\SetAlgoNoLine`命令，可以让算法中没有竖线，如下图所示：

   ![20220720_153737_97](image/20220720_153737_97.png)
- 加入`\SetAlgoLined`命令，可以让算法中有竖线，如下图所示：

   ![20220720_153921_25](image/20220720_153921_25.png)
- 加入命令`\SetAlgoVlined`，可以让算法中有折线，如下图所示：

   ![20220720_154205_63](image/20220720_154205_63.png)

注意比较`\SetAlgoNoLine`，`\SetAlgoLined`，`\SetAlgoVlined`这三个命令，只有最后一个命令，会使得if-else,或while等block，没有`end`作为结尾

---
- While 语句：使用命令`While{条件}{语句}`，如下图所示：

  ![20220720_163110_78](image/20220720_163110_78.png)

- if-else语句：使用命令`eIf{条件}{if 下的语句}{else下的语句}`，如下图所示：

   ![20220720_163225_22](image/20220720_163225_22.png)
- while语句中内嵌if-else语句，的格式如下图所示：

  ![20220720_163446_88](image/20220720_163446_88.png)

---
# <font color='#9c6680'>4. 第二个 example</font>
对应的tex文件 `E:\markdown笔记\Algrothem 2e 宏包学习\tex文件\2e_test2.tex`

![20220720_002704_21](image/20220720_002704_21.png)

![20220720_002728_58](image/20220720_002728_58.png)
## <font color = '#94a657'>第二个例子的解析</font>
- 如何在算法中加注释？
  - 注释语法1为 `\tcp[options]{}`  注释的样式为：`//`，如下图所示

    ![20220720_145914_34](image/20220720_145914_34.png)

  - 注释语法2为 `、tcc[options]{}`  注释的样式为：`/*`，如下图所示

     ![20220720_145956_69](image/20220720_145956_69.png)
  - 在if句使用注释时, `\If(tcc{注释}){条件}`


- 添加空白行命令 `\BlankLine`，将该命令添加在需要加入空白行的地方


- `\emph{}`，该命令表示斜体

- 普通的语句直接写，如果需要换行需要在语句最后加入`\`符号

- `\IncMargin{1em}`命令：使得行号不向外突出

---




# <font color="#9c6680">5. If-else的宏命令</font>
## <font color='#94a657'>If 和Else宏命令的种类如下表所示：</font>
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

If-Else的嵌套使用：

---
- `\eIf(comment){condition}{then block }{else block  }` ：

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
- 多个If-Else结构嵌套使用：

	![20220721_093555_27](image/20220721_093555_27.png)

	![20220721_093430_14](image/20220721_093430_14.png)

---
- 多个If-Else结构嵌套使用2：

	![20220721_093703_22](image/20220721_093703_22.png)

	![20220721_093723_54](image/20220721_093723_54.png)

---
对应的tex文件示例：`E:\markdown笔记\Algrothem 2e 宏包学习\tex文件\IF_Else.tex`

---

# <font color="#9c6680">6. For循环的宏命令</font>
## <font color='#94a657'>For循环宏命令的种类如下表所示：</font>
|for loop 	|
|:----:	|
| `\For{loop's condition}{For's text}`	|
| `\For{loop's condition}{For's text (comment)}`	|
| `\lFor{loop's condition}{For's text}`	|
| `\lFor*{loop's condition}{For's text}`	|
| `\ForAll{loop's condition}{For's text}`	|
| `\ForEach{loop's condition}{For's text}`	|

For循环的使用：

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
- `\ForAll{loop's condition}{For's text}`：

	 ![20220720_215604_50](image/20220720_215604_50.png)

   ![20220720_215911_85](image/20220720_215911_85.png)

---
- `\ForEach{loop's condition}{For's text}` :

	![20220720_215629_35](image/20220720_215629_35.png)

	![20220720_215939_68](image/20220720_215939_68.png)

---
- 两个For循环嵌套：

	![20220720_220129_71](image/20220720_220129_71.png)

	![20220720_220106_71](image/20220720_220106_71.png)

---
对应的tex文件示例：`E:\markdown笔记\Algrothem 2e 宏包学习\tex文件\For_loop.tex`


---

# <font color="#9c6680">7. While循环的宏命令</font>
- algorithm2e 中最常用的while循环命令为：`\While{}{}`
- algorithm2e 中没有`do-while`结构的宏命令，但可以自定义

## <font color='#94a657'>while循环命令的使用：</font>
- `\While{}{}` ：

	![20220721_095410_25](image/20220721_095410_25.png)

	![20220721_095540_86](image/20220721_095540_86.png)

- While 循环与If-Else结构嵌套：

	![20220721_100540_21](image/20220721_100540_21.png)

	![20220721_100517_17](image/20220721_100517_17.png)

- While , If-else and For 嵌套使用：

	![20220721_102644_34](image/20220721_102644_34.png)

	![20220721_102658_55](image/20220721_102658_55.png)

---
对应的tex文件示例：`E:\markdown笔记\Algrothem 2e 宏包学习\tex文件\While.tex`

---

# <font color="#9c6680">8. 注释宏命令</font>
在Algorithm2e宏包中，注释命令的种类有如下几种：

| tcc 	| tcp 	|
|:---:	|:---:	|
|   `\tcc{}`  	|   `\tcp{}`   	|
|   `\tcc*[l]{}`   	|   `\tcp*[l]{}`   	|
|   `\tcc*[r]{}`   	|    `\tcp*[r]{}`  	|
|   `\tcc*[h]{}`   	|    `\tcp*[h]{}`  	|
|   `\tcc*[f]{}`   	|    `\tcp*[f]{}`  	|

## <font color='#94a657'>`\tcp{}` 与`\tcc{}`的不同：</font>
`\tcp`的注释样式为：`//`，如下图所示：

![20220721_125300_16](image/20220721_125300_16.png)

`\tcc`的注释样式为：`/*  */`，如下图所示：

![20220721_125248_35](image/20220721_125248_35.png)

## <font color='#94a657'>`\tcp{}` 与`\tcp*[options]{}`的不同：</font>
-  `\tcc{}`:  注释语句单独一行，注释语句前无`;`，行末无`;`

	![20220721_125846_22](image/20220721_125846_22.png)
	![20220721_125735_26](image/20220721_125735_26.png)

-  `\tcc*[l]{}`:注释语句左靠齐，注释语句前有`;`

	![20220721_130141_58](image/20220721_130141_58.png)
	![20220721_130124_74](image/20220721_130124_74.png)

-  `\tcc*[r]{}`:注释语句右靠齐，注释语句前有`;`

	![20220721_130243_73](image/20220721_130243_73.png)
	![20220721_130232_30](image/20220721_130232_30.png)

-  `\tcc*[h]{}`:注释语句左靠齐，注释语句前无`;`，行末无`;`

	![20220721_130421_46](image/20220721_130421_46.png)
	![20220721_130451_20](image/20220721_130451_20.png)

-  `\tcc*[f]{}`:注释语句右靠齐，注释语句前无`;`，行末无`;`

	![20220721_130503_66](image/20220721_130503_66.png)
	![20220721_130516_18](image/20220721_130516_18.png)

`\tcp`命令的options与上述相同

- **Please note that：**

	- 当与IF-Else,While等 block 嵌套使用时，只能嵌套 `\tcc*[h]{}`或`\tcc*[f]{}`命令
	- 一个语句单独一行时，只能使用 `\tcc{}`命令
	- 需要在一条普通的语句后面紧接注释时，请使用 `\tcc*[l]{}`或 `\tcc*[r]{}`命令

# <font color="#9c6680">9. 自定义函数Function</font>

## <font color='#94a657'>`\SetKwFunction{KwFn}{Fn}`命令</font>
`\SetKwFunction{KwFn}{Fn}`主要用来定义一个函数名称

`KwFn`为tex内定义的关键字，{Fn}为pdf内真实显示的关键字。其中，`KwFn`关键字的名称可以随意命名，{Fn}为你pdf文档中需要的函数名称，一般为Function或Def。

## <font color='#94a657'>`\SetKwProg{Prog}{Title}{is}{end}`命令</font>
 `\SetKwProg{Prog}{Title}{is}{end}`用来编写函数的具体实现

 `Prog`为关键字，`Title`为你pdf文档中的函数标签。
 `is`是pdf文档中，函数名字后面所接标签，`end`表示该函数以`end`结尾

 ## <font color='#94a657'>自定义函数的例子</font>

 ---
 - 定义一个`Function`函数
 	- step1. 定义该函数的一个函数名称：
	![20220721_163001_79](image/20220721_163001_79.png)
	`Fsum`为接下来写tex程序需要调用的关键字，而`Sum`为PDF文档中所出现的函数名。

	- step2. 实现具体的函数功能：
	![20220721_163146_42](image/20220721_163146_42.png)
	- 完整的定义一个函数的代码如下：
	![20220721_163334_01](image/20220721_163334_01.png)
	![20220721_163432_13](image/20220721_163432_13.png)

---
- 定义一个`Def`函数
	- step1. 定义该函数的一个函数名称：
	![20220721_164127_90](image/20220721_164127_90.png)

	- step2. 实现具体的函数功能：
	![20220721_164150_77](image/20220721_164150_77.png)

	- 完整的定义一个函数的代码如下：
	![20220721_164222_68](image/20220721_164222_68.png)
	![20220721_164239_54](image/20220721_164239_54.png)

同理，如果想定义一个标签为`Main`的函数，只需要修改`\SetKwProg{Prog}{Title}{is}{end}`命令的第二个中括号的内容为`Main`
即如下所示：
![20220721_164627_74](image/20220721_164627_74.png)
![20220721_164644_69](image/20220721_164644_69.png)

## <font color='#94a657'>适应不同需求的函数样式</font>
- 无`end`结尾的Function
	- 代码：

		![20220721_175635_55](image/20220721_175635_55.png)
	- 效果：

		![20220721_175707_66](image/20220721_175707_66.png)
	- <font color='red'>Note!  </font>： `\SetKwProg{Prog}{Title}{is}{}`命令的第四个中括号空着就行.
---

- 以`end`结尾的Function
	- 代码：

	![20220721_175906_93](image/20220721_175906_93.png)

	- 效果：

	![20220721_175922_17](image/20220721_175922_17.png)

	- <font color='red'>Note!  </font>：这里可以灵活改变，若需要以`End`结尾,则命令 `\SetKwProg{Prog}{Title}{is}{End}`的第四个中括号内容为`End`.
---

- 以`return`结尾的Function
	- 代码：

	![20220721_180151_70](image/20220721_180151_70.png)

	- 效果：

	![20220721_180207_36](image/20220721_180207_36.png)

---

	- <font color='red'>Note!  </font>：首先，return在Algorithm2e中的关键字为`\KwRet`。其次，若命令 `\SetKwProg{Prog}{Title}{is}{\KwRet{}}`的第四个中括号的内容为`\KwRet` 且函数体内部也有`\KwRet`关键字，则两个return都会显示。

	![20220721_181428_27](image/20220721_181428_27.png)
	![20220721_181507_47](image/20220721_181507_47.png)

---

- Function is 样式
	- 代码：

	![20220721_180324_79](image/20220721_180324_79.png)

	- 效果：

	![20220721_180341_94](image/20220721_180341_94.png)

---

- Function ：样式
	- 代码：

	![20220721_180504_64](image/20220721_180504_64.png)

	- 效果：

	![20220721_180451_69](image/20220721_180451_69.png)

---

## <font color='#94a657'>以`\SetKwProg`单独创建函数</font>
- 代码：


![20220721_185650_25](image/20220721_185650_25.png)

- 效果：


![20220721_185730_25](image/20220721_185730_25.png)

---

-  <font color='red'>Note!  </font>：不建议在函数体内部打字return,这样的return不会加粗，应该使用algorithm2e的关键字`\KwRet`。其次，这样创建的函数的函数名称是斜体的，虽然这种方法更简便，不需要用到`\SetKwFunction`命令，请自行选择使用哪种方法创建函数


## <font color='#94a657'>当你在算法中只想引用一个函数名时</font>

当你在算法中只想引用一个函数名，而不用实现该函数的具体函数体时，也可以采用`\SetKwFunction`命令来单独创建一个函数名称。
- 代码：

![20220721_190848_02](image/20220721_190848_02.png)

- 效果：

![20220721_190901_45](image/20220721_190901_45.png)

---

本节中所有例子对应的tex文件为：`E:\markdown笔记\Algrothem 2e 宏包学习\tex文件\Function\Function.tex`

---

# <font color="#9c6680">10.算法的输入与输出 </font>
在文献中常见的输入输出有两种：
- 第一种：`Input - Ouput`类型，如下图所示：
	- 效果图：
	![20220721_194833_94](image/20220721_194833_94.png)
	- 代码：

		![20220721_195228_85](image/20220721_195228_85.png)

- 第二种： `Data - Result`类型，如下图所示：
	- 效果图：
	![20220721_194851_96](image/20220721_194851_96.png)
	- 代码：
		![20220721_195203_49](image/20220721_195203_49.png)
---

##  <font color='#94a657'> `Input - Ouput`类型的宏命令</font>
`Input - Ouput`类型涉及的宏命令主要有三个：
- `\SetKwInput{KwInput}{Input}`
- `\KwInput{input text}`
- `\KwOutput{output text}`


`\SetKwInput{KwInput}{Input}`的第一个中括号中的内容`KwInput`主要为写代码中所使用的宏命令；第二个中括号的内容`Input`为pdf文档中，你想要的input标签.其中，第一个中括号中的内容可以随意。定制个性化的输入输出，见下面的例子：

---
- 如果你想要小写input
	- 代码：

		![20220721_200233_98](image/20220721_200233_98.png)

	- 效果图：

		![20220721_200244_85](image/20220721_200244_85.png)

---
- 如果你想要大写的input
	 - 代码：

	 	![20220721_200406_35](image/20220721_200406_35.png)

	 - 效果图：

	 	![20220721_200418_35](image/20220721_200418_35.png)

---

`\KwInput{input text}`主要实现的是，实现你算法中的输入内容，中括号中的内容就是你算法的输入内容

`\KwOutput{output text}`主要实现的是，实现你算法中的输出内容，中括号中的内容就是你算法的输出内容


<font color='red'>Note!  </font>：对于`Input - Ouput`类型的输入输出，必须先通过`\SetKwInput{KwInput}{Input}`命令，指定input的标签，再使用`\KwInput{input text}`和`\KwOutput{output text}`命令实现你算法的输入输出内容

一套完整的构造`Input - Output`的代码：
![20220721_201100_79](image/20220721_201100_79.png)

##  <font color='#94a657'>  `Data - Result`类型的宏命令</font>
 `Data - Result`类型的宏命令相比于`Input - Ouput`类型的宏命令更简单。

 构造算法的Data,只需要`\KwData{ data text}`命令；

 构造算法的Result，只需要`\KwResult{result text}`命令

 一套完整的构造`Input - Output`的代码：
![20220721_201510_20](image/20220721_201510_20.png)

本节中所有例子对应的tex文件为：`E:\markdown笔记\Algrothem 2e 宏包学习\tex文件\Input_and_Ouput\InputAndOuput.tex`

# <font color="#9c6680">11.构造自己的关键词的基本方法 </font>

此处不再详细讲解，因为基本上用不到

在Algorithm2e宏包中，构造自己的关键词的方法有一下几种：
| Macro command 	| definition	|
|:---:	|:---:	|
| `\SetKw{Kw}{text}`	|which define a keyword `text`|
| `\SetKwHangingKw{HData}{Data}`	|which define a hanging keyword `Data`	|
| `\SetKwData{Left}{left}`	| which define a data text `left`.	|
| `\SetKwArray{KwAarray}{array}`	|`which define an array keywords`	|

## <font color='#94a657'> `\SetKw{Kw}{text}` 示例</font>
- 代码：

	![20220721_211320_50](image/20220721_211320_50.png)

- 效果：

	![20220721_211329_46](image/20220721_211329_46.png)

## <font color='#94a657'> `\SetKwHangingKw{HData}{Data}` 示例</font>
- 代码：

	![20220721_211403_27](image/20220721_211403_27.png)

- 效果：

	![20220721_211416_11](image/20220721_211416_11.png)

##  <font color='#94a657'>`\SetKwData{Left}{left}` 示例</font>
- 代码：

	![20220721_211428_31](image/20220721_211428_31.png)

- 效果：

	![20220721_211436_95](image/20220721_211436_95.png)

##  <font color='#94a657'>`\SetKwArray{KwAarray}{array}` 示例</font>
- 代码：

	![20220721_211450_25](image/20220721_211450_25.png)

- 效果：

	![20220721_211500_38](image/20220721_211500_38.png)

本节中所有例子对应的tex文件为：`E:\markdown笔记\Algrothem 2e 宏包学习\tex文件\Keywords\keywords.tex`

#  <font color="#9c6680">12.Algorithm2e宏包中基本关键词和基本块结构 </font>

---

- 关键词：`to`
	- 代码：

		![20220721_212723_62](image/20220721_212723_62.png)

		- 效果：

			![20220721_212734_97](image/20220721_212734_97.png)

---

- 关键词：`return`
	- 代码：

		![20220721_212802_82](image/20220721_212802_82.png)

		- 效果：

			![20220721_212813_66](image/20220721_212813_66.png)

<font color='red'> Note!  </font>： 貌似`\KwRet{}`与`\Return{}`两者的效果一样

---

- 块结构：begin
	- 代码：

		![20220721_212843_57](image/20220721_212843_57.png)

		- 效果：

			![20220721_212900_14](image/20220721_212900_14.png)


本节中所有例子对应的tex文件为：`E:\markdown笔记\Algrothem 2e 宏包学习\tex文件\Basic_Kw\basicKw.tex`

# <font color="#9c6680">13.在Algorithm2e宏包中使用中文 </font>

在算法中输入中文，只需要在`\begin{document}`之前添加一个包即可：
`\usepackage[GBK]{ctex}  `

<font color='red'> Note!  </font>：如果出现乱码的情况，可以尝试把`[GBK]`换成`[UTF-8]`.

# <font color="#9c6680">14.算法标题 </font>
## `\caption{}`命令
`\caption{}`中括号内的内容即为，你的算法名称


## `ruled`options

在`\usepackage[linesnumbered,lined,ruled,boxed]{algorithm2e}`命令中，`ruled`表示算法的标题在算法的上方，当不加`ruled`时，默认算法的标题位于算法的下方。

两个例子如下所示：

- 代码：

![20220722_110618_00](image/20220722_110618_00.png)

- 效果：

![20220722_110558_84](image/20220722_110558_84.png)


- 代码：

![20220722_110733_25](image/20220722_110733_25.png)

- 效果：

![20220722_110723_90](image/20220722_110723_90.png)

## 修改算法的编号

修改算法的编号有两种方式
-  `\renewcommand{\thealgocf}{number}` ,`number`为修改的算法编号
-  `\SetAlgoRefName{number}`,`number`为修改的算法编号

## 修改算法的关键字

使用`\renewcommand{\algorithmcfname}{算法关键字}`命令修改算法的关键字

例子如下所示：
- 代码：

![20220722_111354_45](image/20220722_111354_45.png)

- 效果：

![20220722_111342_57](image/20220722_111342_57.png)


# <font color="#9c6680">未完待续... </font>
