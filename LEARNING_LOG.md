# 学习日志（2h/天）
说明：
- 每次学习记录一个条目，包含：学了啥 → 生疏点 → 反思
- 建议每天提交（commit）一次，并在提交信息中引用当天日期

## 模板（复制使用）
```
日期：YYYY-MM-DD（周X）

学了啥：
- 平台：
- 笔记关键词：
生疏点：
- 第一点：
- 第二点：
……
反思：
- 第一点：
- 第二点：


日期：2025-10-08

学了啥：
- 平台：datacamp
- 笔记关键词：完成了introduce to python

生疏点：
- 第一点：初次接触numpy
- 第二点：学习了plot的制作，x轴，y轴，标题，三种格式（散点，折线，柱状）
……

反思：
- ：
- 我如何尝试/解决：

日期：2025-10-09

学了啥：
- 平台：datacamp
- 笔记关键词：完成了中级python的第二章

生疏点：
- 第一点：初次接触pandas
- 第二点：初次接触字典
……

反思：
- ：pandas的方括号，双方括号很难
- 我如何尝试/解决：方括号用于检索标签（行、列）
（列表）单方括号：['行标签'，'列标签']
（dataframe）双方括号：[['行标签1'，'行标签2']]
cars.loc[['MOR','RU'],['drives_right','country']]
冒号用法：print(cars.loc[:,['drives_right']])
print(cars.loc[:,1:2])
print(cars.loc[:,['drives_right':'ABC']])

## 模板（复制使用）
```
日期：10.11（周X）

学了啥：
- 平台：datacamp
- 笔记关键词：逻辑比较，逻辑判断
生疏点：
- 第一点：逻辑在pandas里的子集操作
- 第二点：for循环的for var in seq:expression
- 第三点(列表)：for index ,var in enumerate(seq):
- 第四点（dataframe,iterrows是按行循环的意思）：for lab,row in seq.iterrows():
- 第五点（新添列）：cars.loc[lab,"COUNTRY"]=row["country"].upper()
……
反思：
- 第一点：逻辑在pandas里的子集操作,先把对应区域给到a,然后a做逻辑运算后，值给到b，然后c=data[b]
- 第二点：逻辑在pandas里的子集操作,c[c['123']<2]
