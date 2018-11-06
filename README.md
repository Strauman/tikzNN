# tikzNN
Please cite usage of this figure with the web address of this git repo

TikZ code of feed forward neural network.
See the [example.pdf](https://github.com/Strauman/tikzNN/blob/master/example.pdf) file for an example.
[example.tex](https://github.com/Strauman/tikzNN/blob/master/example.tex) contains the code for the above example.
The annotation in the example are the TikZ node names. Most have a `north`,`south`,`east`,`west` and `center` and combos of those
anchor. E.g. you could do `\node at (NN-rectangle-1.south east){X}`, which would put an X ont the bottom right
corner of the second layer.

Set `verbose=false` to remove all the annotations.

![Example png](https://github.com/Strauman/tikzNN/raw/master/example.png)
