# Tikz

1、数学公式加粗：        \boldmath    \node [inner sep=0pt,right of = Y,node distance = 12mm] (charspandex) (t1) {\bf $h_l$};     \unboldmath
2、矩形    \node [rectangle, thick,draw,rounded corners=1mm,  minimum height=5mm, minimum width = 20mm, right of = n, node distance = 40mm] (N) {\bf LSTM};

3、梯形    \node [trapezium, draw, fill=B, trapezium left angle=45, trapezium right angle=45, trapezium stretches = true, minimum height=10mm, mi   nimum width = 50mm, above of = a1, node distance = 16mm] (B) {\bf CNN};

4、实体之间连线。(方位)    \path[draw, thick, ->] (f1.east) -- (f3.west);

5、曲线    \path[draw, thick, - ](w5') to [out=0,in=270](w4');     out = 0 :出度节点切线的与x轴正向角度。

6、旋转    1）图形旋转：rotate = 90

7、双向箭头    \path [draw, thick, ->] (b11.10) -- (b12.170) node[midway, above] {};    \path [draw, thick, ->] (b12.190) -- (b11.-10)node[midway, below] {};    node.y  y为与x轴正向角度

8、虚线：
   断线dashed  断点dotted 
