H. Jin's Machine Learning Notes
===
## Set up development environment (macOS)

### TensorFlow install
[TensorFlow](https://www.tensorflow.org/install/install_mac)
* install [Anaconda](https://anaconda.org/)
* create an virtualenv named "tensorflow" in Anaconda GUI
* open a terminal and go to `~/anaconda/envs/tensorflow`
    + start virtualenv by `source ./bin/activate`
    + start jupyter by `jupyter notebook`
    + ...
    + exit virtualenv by `deactivate`


All the packages and frameworks should be installed in the virtualenv. When we stay at tensorflow virtualenv, run the following command to install tensorflow framework. The source code used here is **not the official version**, it is from https://github.com/lakshayg/tensorflow-build

    pip install --ignore-installed --upgrade \ https://github.com/lakshayg/tensorflow-build/raw/master/tensorflow-1.4.0-cp36-cp36m-macosx_10_12_x86_64.whl
