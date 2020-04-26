# None
Use GA optim a function to get the maximum.

使用遗传算法优化函数，获取其极大值

选取的函数是

def F(x, y):

    ss = x**2 + y**2
    
    return  (0.5 - ((np.sin(np.sqrt(ss)))**2 - 0.5) / (1 + 0.001 * (ss))**2)
    
约束范围是[-100,100]

参数设置：

  DNA_SIZE = 24

  POP_SIZE = 200

  CROSSOVER_RATE = 0.8

  MUTATION_RATE = 0.005

  N_GENERATIONS = 100
  
最后选取每代函数值均值作为纵轴绘制优化曲线：

![img](https://github.com/SivenLSP/None/blob/master/%E4%BC%98%E5%8C%96%E6%9B%B2%E7%BA%BF.png)
