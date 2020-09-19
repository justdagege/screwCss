# screwCss
开发中, 不可避免的需要使用css来绘制样式, 特别是react开发, 代码中极易充斥着各种 style={{}}, 编写起来又耗时又耗力。基于Bootstrap的启发, 抽象了此css样式库, 在dom上只需要添加 class 类名即可实现样式。
最后在有限的开发中，无限的装逼。。。。

# example

1. 指定div为flex-box
    &ltdiv className = 'flex-box'&gt&lt/div&gt"

2. 设置边距值
    &ltdiv className = 'm-a-1'&gt&lt/div&gt
    m: margin
    p: padding
    a: 全部-四个方向
    1：5px (2为10px，以此类推)

# tips
    使用前建议看一眼源码(都是简单css, 看不懂我也没办法), 知道大概封装了哪些css样式, 后续使用也方便。