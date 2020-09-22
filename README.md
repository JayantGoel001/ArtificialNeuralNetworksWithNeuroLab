# Artificial Neural Networks With NeuroLab And Python

Neurolab is a simple and powerful Neural Network Library for Python. Contains based neural networks, train algorithms and flexible framework to create and explore other neural network types.

### Features:	
* Pure python + numpy
* API like Neural Network Toolbox (NNT) from MATLAB
* Interface to use train algorithms form scipy.optimize
* Flexible network configurations and learning algorithms. You may change: train, error, initialization and activation functions
* Unlimited number of neural layers and number of neurons in layers
* Variety of supported types of Artificial Neural Network and learning algorithms

## Support neural networks types
<ul>
  <li><strong>Single layer perceptron</strong></li>
  <ul>
    <li>create function: neurolab.net.newp()</li>
    <li>example of use: newp</li>
    <li>default train function: neurolab.train.train_delta()</li>
    <li>support train functions: train_gd, train_gda, train_gdm, train_gdx, train_rprop, train_bfgs, train_cg</li>
    <br>
  </ul>
    <li><strong>Multilayer feed forward perceptron</strong></li>
  <ul>
    <li>create function: neurolab.net.newff()</li>
    <li>example of use: newff</li>
    <li>default train function: neurolab.train.train_gdx()</li>
    <li>support train functions: train_gd, train_gda, train_gdm, train_rprop, train_bfgs, train_cg</li>
    <br>
  </ul>
    <li><strong>Competing layer (Kohonen Layer)</strong></li>
  <ul>
    <li>create function: neurolab.net.newc()</li>
    <li>example of use: newc</li>
    <li>default train function: neurolab.train.train_cwta()</li>
    <li>support train functions: train_wta</li>
    <br>
  </ul>
    <li><strong>Learning Vector Quantization (LVQ)</strong></li>
  <ul>
    <li>create function: neurolab.net.newlvq()</li>
    <li>example of use: newlvq</li>
    <li>default train function: neurolab.train.train_lvq()</li>
    <br>
  </ul>
      <li><strong>Elman Recurrent network</strong></li>
  <ul>
    <li>create function: neurolab.net.newelm()</li>
    <li>example of use: newelm</li>
    <li>default train function: neurolab.train.train_gdx()</li>
    <li>support train functions: train_gd, train_gda, train_gdm, train_rprop, train_bfgs, train_cg</li><br>
  </ul>
      <li><strong>Hopfield Recurrent network</strong></li>
  <ul>
    <li>create function: neurolab.net.newhop()</li>
    <li>example of use: newhop</li><br>
  </ul>
  <li><strong>Hemming Recurrent network</strong></li>
  <ul>
    <li>create function: neurolab.net.newhem()</li>
    <li>example of use: newhem</li><br>
  </ul>
 </ul>
