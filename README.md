# Tools to Design or Visualize Architecture of Neural Network

## [Net2Vis](https://viscom.net2vis.uni-ulm.de/OG1Br2BAkYSwwrV6CADl4X5EfErFjUzvuUwXWDdLbdsIXNhb9L)

Net2Vis automatically generates abstract visualizations for convolutional neural networks from Keras code.

![](https://viscom.publications.uni-ulm.de/api/uploads/4/baeuerle19net2vis-teaser-application.png)

## [visualkeras](https://github.com/paulgavrikov/visualkeras/)

Visualkeras is a Python package to help visualize Keras (either standalone or included in tensorflow) neural network architectures. It allows easy styling to fit most needs. As of now it supports layered style architecture generation which is great for CNNs (Convolutional Neural Networks) and a grap style architecture.

```python
import visualkeras

model = ...

visualkeras.layered_view(model).show() # display using your system viewer
visualkeras.layered_view(model, to_file='output.png') # write to disk
visualkeras.layered_view(model, to_file='output.png').show() # write and show

visualkeras.layered_view(model)
```

![Visualization of the VGG16 neural network with stacked layers of decreasing size.](https://github.com/paulgavrikov/visualkeras/raw/master/figures/vgg16.png)

## [draw_convnet](https://github.com/gwding/draw_convnet)

Python script for illustrating Convolutional Neural Network (ConvNet)

![img](https://raw.githubusercontent.com/gwding/draw_convnet/master/convnet_fig.png)

## [NNSVG](http://alexlenail.me/NN-SVG/LeNet.html)

![AlexNet style](https://i.stack.imgur.com/Q0xOe.png)

![enter image description here](https://i.stack.imgur.com/K9lmg.png)

![enter image description here](https://i.stack.imgur.com/DlJ8J.png)

## [PlotNeuralNet](https://github.com/HarisIqbal88/PlotNeuralNet)

Latex code for drawing neural networks for reports and presentation. Have a look into examples to see how they are made. Additionally, lets consolidate any improvements that you make and fix any bugs to help more people with this code.

![img](https://user-images.githubusercontent.com/17570785/50308846-c2231880-049c-11e9-8763-3daa1024de78.png)

![img](https://user-images.githubusercontent.com/17570785/50308873-e2eb6e00-049c-11e9-9587-9da6bdec011b.png)

## [Tensorboard](https://www.tensorflow.org/tensorboard/graphs)

TensorBoard’s **Graphs dashboard** is a powerful tool for examining your TensorFlow model.

![enter image description here](https://i.stack.imgur.com/zJHpV.png)

## [Caffe](https://github.com/BVLC/caffe/blob/master/python/caffe/draw.py)

In Caffe you can use [caffe/draw.py](https://github.com/BVLC/caffe/blob/master/python/caffe/draw.py) to draw the NetParameter protobuffer:

![enter image description here](https://i.stack.imgur.com/5Z1Cb.png)

## [Matlab](http://www.mathworks.com/help/nnet/ref/view.html)

![enter image description here](https://i.stack.imgur.com/rPpfa.png)

## [Keras.js](https://transcranial.github.io/keras-js/#/inception-v3)

![enter image description here](https://i.stack.imgur.com/vEfTv.png)

## [keras-sequential-ascii](https://github.com/stared/keras-sequential-ascii/)

A library for [Keras](https://keras.io/) for investigating architectures and parameters of sequential models.

### VGG 16 Architecture

```text
           OPERATION           DATA DIMENSIONS   WEIGHTS(N)   WEIGHTS(%)

              Input   #####      3  224  224
         InputLayer     |   -------------------         0     0.0%
                      #####      3  224  224
      Convolution2D    \|/  -------------------      1792     0.0%
               relu   #####     64  224  224
      Convolution2D    \|/  -------------------     36928     0.0%
               relu   #####     64  224  224
       MaxPooling2D   Y max -------------------         0     0.0%
                      #####     64  112  112
      Convolution2D    \|/  -------------------     73856     0.1%
               relu   #####    128  112  112
      Convolution2D    \|/  -------------------    147584     0.1%
               relu   #####    128  112  112
       MaxPooling2D   Y max -------------------         0     0.0%
                      #####    128   56   56
      Convolution2D    \|/  -------------------    295168     0.2%
               relu   #####    256   56   56
      Convolution2D    \|/  -------------------    590080     0.4%
               relu   #####    256   56   56
      Convolution2D    \|/  -------------------    590080     0.4%
               relu   #####    256   56   56
       MaxPooling2D   Y max -------------------         0     0.0%
                      #####    256   28   28
      Convolution2D    \|/  -------------------   1180160     0.9%
               relu   #####    512   28   28
      Convolution2D    \|/  -------------------   2359808     1.7%
               relu   #####    512   28   28
      Convolution2D    \|/  -------------------   2359808     1.7%
               relu   #####    512   28   28
       MaxPooling2D   Y max -------------------         0     0.0%
                      #####    512   14   14
      Convolution2D    \|/  -------------------   2359808     1.7%
               relu   #####    512   14   14
      Convolution2D    \|/  -------------------   2359808     1.7%
               relu   #####    512   14   14
      Convolution2D    \|/  -------------------   2359808     1.7%
               relu   #####    512   14   14
       MaxPooling2D   Y max -------------------         0     0.0%
                      #####    512    7    7
            Flatten   ||||| -------------------         0     0.0%
                      #####       25088
              Dense   XXXXX ------------------- 102764544    74.3%
               relu   #####        4096
              Dense   XXXXX -------------------  16781312    12.1%
               relu   #####        4096
              Dense   XXXXX -------------------   4097000     3.0%
            softmax   #####        1000
```

## [Netron](https://github.com/lutzroeder/Netron)

![screenshot.png](https://github.com/lutzroeder/netron/raw/main/.github/screenshot.png)

## [DotNet](https://github.com/martisak/dotnets)

![Simple net](https://github.com/martisak/dotnets/raw/master/test.png)

## [Graphviz](http://www.graphviz.org/)

**[Tutorial](https://tgmstat.wordpress.com/2013/06/12/draw-neural-network-diagrams-graphviz/)**

![img](https://tgmstat.files.wordpress.com/2013/05/multiclass_neural_network_example.png)

## [Keras Visualization](https://keras.io/visualization/)

The [keras.utils.vis_utils module](https://keras.io/visualization/) provides utility functions to plot a Keras model (using graphviz)

![enter image description here](https://i.stack.imgur.com/o17GY.png)

## [Conx](https://conx.readthedocs.io/en/latest/index.html)

The Python package `conx` can visualize networks with activations with the function `net.picture()` to produce SVG, PNG, or PIL Images like this:

![enter image description here](https://i.stack.imgur.com/nhHjO.png)

## [ENNUI](https://math.mit.edu/ennui/)

Working on a drag-and-drop neural network visualizer (and more). Here's an example of a visualization for a LeNet-like architecture.

![A visualization of a LeNet-like architecture](https://i.stack.imgur.com/pRLeG.png)

## NNet - R Package

**[Tutorial](https://beckmw.wordpress.com/2013/03/04/visualizing-neural-networks-from-the-nnet-package/)**

```R
data(infert, package="datasets")
plot(neuralnet(case~parity+induced+spontaneous, infert))
```

![neuralnet](https://i.stack.imgur.com/yyftd.png)

## [GraphCore](https://www.graphcore.ai/posts/what-does-machine-learning-look-like)

These approaches are more oriented towards visualizing neural network operation, however, NN architecture is also somewhat visible on the resulting diagrams.

### AlexNet

![alexnet_label logo.jpg](https://www.graphcore.ai/hubfs/images/alexnet_label%20logo.jpg)

### ResNet50

![resnet50_label_logo.jpg](https://www.graphcore.ai/hubfs/images/resnet50_label_logo.jpg)

## [Neataptic](https://wagenaartje.github.io/neataptic/)

Neataptic offers flexible neural networks; neurons and synapses can be removed with a single line of code. No fixed architecture is required for neural networks to function at all. This flexibility allows networks to be shaped for your dataset through neuro-evolution, which is done using multiple threads.

![img](https://i.gyazo.com/f566d2364af43dd3a78c8926ed204a51.png)

## [TensorSpace](https://tensorspace.org/)

TensorSpace is a neural network 3D visualization framework built by TensorFlow.js, Three.js and Tween.js. TensorSpace provides Layer APIs to build deep learning layers, load pre-trained models, and generate a 3D visualization in the browser. By applying TensorSpace API, it is more intuitive to visualize and understand any pre-trained models built by TensorFlow, Keras, TensorFlow.js, etc.

**[Tutorial](https://www.freecodecamp.org/news/tensorspace-js-a-way-to-3d-visualize-neural-networks-in-browsers-2c0afd7648a8/)**

![enter image description here](https://i.stack.imgur.com/ekF5v.png)

## [Netscope CNN Analyzer](http://dgschwend.github.io/netscope/quickstart.html)

![enter image description here](https://i.stack.imgur.com/VVDsg.png)

## [Monial](https://github.com/mlajtos/moniel)

Interactive Notation for Computational Graphs <https://mlajtos.github.io/moniel/>

![img](https://miro.medium.com/max/819/1*u6uIQF4xTVe-ylJnAPoIDg.png)

## [Texample](http://www.texample.net/tikz/examples/neural-network/)

![Neural Network](https://texample.net/media/tikz/examples/PNG/neural-network.png)

```latex
\documentclass{article}

\usepackage{tikz}
\begin{document}
\pagestyle{empty}

\def\layersep{2.5cm}

\begin{tikzpicture}[shorten >=1pt,->,draw=black!50, node distance=\layersep]
    \tikzstyle{every pin edge}=[<-,shorten <=1pt]
    \tikzstyle{neuron}=[circle,fill=black!25,minimum size=17pt,inner sep=0pt]
    \tikzstyle{input neuron}=[neuron, fill=green!50];
    \tikzstyle{output neuron}=[neuron, fill=red!50];
    \tikzstyle{hidden neuron}=[neuron, fill=blue!50];
    \tikzstyle{annot} = [text width=4em, text centered]

    % Draw the input layer nodes
    \foreach \name / \y in {1,...,4}
    % This is the same as writing \foreach \name / \y in {1/1,2/2,3/3,4/4}
        \node[input neuron, pin=left:Input \#\y] (I-\name) at (0,-\y) {};

    % Draw the hidden layer nodes
    \foreach \name / \y in {1,...,5}
        \path[yshift=0.5cm]
            node[hidden neuron] (H-\name) at (\layersep,-\y cm) {};

    % Draw the output layer node
    \node[output neuron,pin={[pin edge={->}]right:Output}, right of=H-3] (O) {};

    % Connect every node in the input layer with every node in the
    % hidden layer.
    \foreach \source in {1,...,4}
        \foreach \dest in {1,...,5}
            \path (I-\source) edge (H-\dest);

    % Connect every node in the hidden layer with the output layer
    \foreach \source in {1,...,5}
        \path (H-\source) edge (O);

    % Annotate the layers
    \node[annot,above of=H-1, node distance=1cm] (hl) {Hidden layer};
    \node[annot,left of=hl] {Input layer};
    \node[annot,right of=hl] {Output layer};
\end{tikzpicture}
% End of code
\end{document}
```

## [Quiver](https://github.com/keplr-io/quiver)

![gzqll3](https://cloud.githubusercontent.com/assets/5866348/20253975/f3d56f14-a9e4-11e6-9693-9873a18df5d3.gif)

**References:**

1) <https://datascience.stackexchange.com/questions/12851/how-do-you-visualize-neural-network-architectures>

2) <https://datascience.stackexchange.com/questions/2670/visualizing-deep-neural-network-training>
