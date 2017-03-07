Sequences

code for ipython notebook pleace click the github link below.

Tensorflow versions 0.12

tf.linspace(start, stop, num, name=None)

在间隔中生成值。

从开始开始生成num个均匀间隔值的序列。 如果num> 1，则序列中的值增加stop-start / num-1，以便最后一个正好停止。

start: A Tensor。 必须是以下类型之一：float32，float64。 范围中的第一个条目。
stop:A Tensor。 必须具有与start相同的类型。 范围中的最后一个条目。
num: A Tensor。 必须是以下类型之一：int32，int64。 要生成的值数。
name: 操作的名称（可选）。
In[1]

import tensorflow as tf
In[2]

a = tf.linspace(10., 12., 5, name="yoodoo")
with tf.Session() as sess:
    print('a:\n', sess.run(a))
Out[2]

a:
 [ 10.   10.5  11.   11.5  12. ]
tf.range(start, limit=None, delta=1, dtype=None, name='range')

创建一个数字序列。

创建从start并以增量delta直到但不包括limit的数字序列。

除非明确地提供，否则从输入推断得到的tensor的dtype。

与Python内置范围类似，开始默认为0，因此range（n）= range（0，n）。

start: A 0-D Tensor (scalar). 如果limit不为None，则作为范围中的第一个条目; 否则，作为范围限制，第一个条目默认为0。
limit: A 0-D Tensor (scalar). 序列上限。 如果为无，则默认为start的值，而该范围的第一个条目的默认值为0。
delta: A 0-D Tensor (scalar). 递增开始的数字。 默认值为1。
dtype: 生成tensor的元素的类型。
name: 操作的名称。 默认为“range”。
In[3]

b = tf.range(start=1, limit=9, delta=2)
c = tf.range(start=9)
with tf.Session() as sess:
    print('b:\n', sess.run(b))
    print('c:\n', sess.run(c))
Out[3]

b:
 [1 3 5 7]
c:
 [0 1 2 3 4 5 6 7 8]
References

1.Hourout/Tensorflow-basics-tutorial-with-python

2.https://www.tensorflow.org
