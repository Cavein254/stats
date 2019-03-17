# Sigmoid Function
The sigmoid function is simply;

$$A = \frac{1}{1 + e^{-x}}$$

'''python
    import numpy as np
    import matplotlib as mpl
    mpl.use('Agg')
    import matplotlib.pyplot as plt

    fig = plt.figure(figsize=(10, 8))
    ax = fig.add_subplot(111)

    points = []

    x = np.linspace(-1,1,100)
    y = []
    def sigmoid(x):
        a = (1.0/(1.0 + np.exp(x)))
        y.append(a)
    for v in range(-50,50):
        sigmoid(v)
    ax.plot(x,y)
    fig.savefig('graph.png')
'''