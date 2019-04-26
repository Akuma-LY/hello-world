
# Step4 生成边界框  
根据$Step3$中寻找到的凸缺陷，生成边界框，边界框算法如下  
边界框中心点$$
\begin{bmatrix}
x_{center}\\
y_{center}
\end{bmatrix}
=
\begin{bmatrix}
x_{start} & x_{end} & x_{farthers}\\
y_{start} & y_{end} & y_{farthers}
\end{bmatrix}
$$  

边界框宽和高  

$$
height = 1.5 \times |y_{start} - y_{end}| \\
width = 0.8 \times height
$$  
