# 起名生成器

基本思路

任何中文名, 都由姓+两个中文字符构成. 其中名的发音必为所有可能中文发音的组合

所以, 可以通过遍历的方式, 生成所有可能的中文名称发音. 然后先选发音, 再替换文字.

使用规则:

0.  起名用字
    1.  从 3500 常见字中选字
    2.  从知名学校录取名单中选字
1.  声调变化
    1.  禁止出现声调相同的情况
    2.  音律富于变化
        1.  允许范围
            1.  -\ /
            2.  -\/\
            3.  -\/-
            4.  -\ -
            5.  -/ \
            6.  -/ \/
            7.  -/ -
2.  不能使用叠字/叠音
3.  不能使用轻声

# 扩展资料

1.  起名方案一: 参考各高校新生入学名册

搜索各大学 + 拟录取名单, 可获得研究生入学名册

示例: [北京大学深圳研究生院 2018 年拟接收推荐免试研究生公示名单](http://115.27.240.62/docs/20171204112036269349.pdf)
