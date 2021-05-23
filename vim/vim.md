https://www.youtube.com/watch?v=IiwGbcd8S7I&t=2250s
https://vim.rtorr.com/lang/zh_cn

dd: 删除行
G: 底部
gg: 顶部
{: 跳到上一个block
}: 跳到下一个block
u: 撤销
<C+r>: redo
.: 重复上个指令
yy: 复制行
p: 复制到下一行
P: 复制到上一行
V: virtual模式
o: 插入新行并进入编辑模式
O: 在前面插入一行
w: 下一个单词
b: 上一个单词
0: 回到行首
^: 第一个有字母的位置
$: 行尾
t{char}: 定位到{char}前
f{char}: 定位到{char}
%: 跳转到配对的符号
cw: 修改单词
D: 删除光标后的值
C: 删除光标以后的值，并切换成insert模式
ct{char}: 删除到{char}的值并切换到insert模式
\*: 查到下一个当前word
;: 重复之前的f、t、F、T操作
zz: 移动光标到居中
a: 从光标后开始插入字符
A: 从行尾开始插入字符
x: 剪切当前字符
~: 大小写切换

\vpattern - <kbd>pattern</kbd> 中的非字母数字字符被视为正则表达式特殊字符 (不需转义字符)
n: 查找下一个
N: 查找上一个
