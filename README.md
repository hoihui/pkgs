* files starting with capitalized letters are sample codes for respective topics
* files starting with lower-case letters are tutorials for packages
# Table of Contents
## Topics
### <a href="https://github.com/hoihui/pkgs/blob/master/Autoencoder.ipynb">Autoencoder.ipynb</a>
  * MNIST w/ torch
    * Load Data
    * Linear Autoencoder
    * Convolutional Autoencoder
    * Denoising Convolutional Autoencoder
### <a href="https://github.com/hoihui/pkgs/blob/master/CNN.ipynb">CNN.ipynb</a>
  * MNIST
    * Torch
    * Keras
  * [Human or horse](https://github.com/lmoroney/dlaicourse/blob/master/Course%202%20-%20Part%202%20-%20Lesson%202%20-%20Notebook.ipynb)
    * Data
    * Model
    * Train
  * Evaluate
  * CIFAR-10
    * Torch
  * Cats/dogs by Transfer Learning
    * DenseNet  with torch
    * MobileNet V2 with tensorflow
  * Transfer VGG16 to Flowers
    * Load data
    * Load VGG19 Model
    * Train
    * Evaluate
### <a href="https://github.com/hoihui/pkgs/blob/master/GAN.ipynb">GAN.ipynb</a>
  * MNIST, MLP
    * Load Data
    * Model
    * Train
    * Evaluate
  * Street View House Number, Convolutional
    * Data
    * Model
    * Train
    * Evaluate
  * CycleGAN
    * Data
### <a href="https://github.com/hoihui/pkgs/blob/master/MLP.ipynb">MLP.ipynb</a>
  * MNIST
    * Torch
    * Keras
### <a href="https://github.com/hoihui/pkgs/blob/master/NLP.ipynb">NLP.ipynb</a>
  * Logistic Regression on imdb for sentiment
    * BOW - 1-gram
    * 2-gram?
  * Word2Vec
    * Data
    * SkipGram using Torch
    * SkipGram + Negative Sampling
    * Visualization
  * Word Embedding + sentiment of imdb
    * Load Data
    * Model
    * Train
    * Evaluation
  * Classification by CNN
  * Language modelling by MLP
### <a href="https://github.com/hoihui/pkgs/blob/master/RNN.ipynb">RNN.ipynb</a>
  * Sine Curve
    * Torch
  * char-rnn
    * Torch
    * Keras
  * IMDB Sentiment by RNN with LSTM
    * Data
    * Model
    * Train
    * Evaluate
  * IMDB large sentiment by Bidirectional LSTM
    * Load Data
    * Model
    * Train
    * Evaluate
  * [HRNN](https://github.com/fchollet/keras/blob/master/examples/mnist_hierarchical_rnn.py)
    * Data
    * Model
### <a href="https://github.com/hoihui/pkgs/blob/master/Reinforcement.ipynb">Reinforcement.ipynb</a>
  * Catch (https://gist.github.com/EderSantana/c7222daa328f0e885093)
  * Flappy
### <a href="https://github.com/hoihui/pkgs/blob/master/StyleTransfer.ipynb">StyleTransfer.ipynb</a>
  * Torch
    * Load VGG19 and Images
    * Extracting style/content features from vgg
    * Defining and Optimizing wrt Loss function
    * Final Display
## Packages
### <a href="https://github.com/hoihui/pkgs/blob/master/gensim.ipynb">gensim.ipynb</a>
  * Preprocess
    * Tokenize
    * Vectorize Corpora
  * Transformations
    * Tfidf (term frequency-inverse document frequency)
    * <a href="https://radimrehurek.com/gensim/models/lsimodel.html#module-gensim.models.lsimodel">lsi (Latent Semantic Indexing)</a>
    * <a href="https://radimrehurek.com/gensim/models/ldamodel.html">lda (Latent Dirichlet Allocation)</a>
    * <a href="https://radimrehurek.com/gensim/models/hdpmodel.html">hdp (Hierarchical Dirichlet Process)</a>
  * Similarities
  * <a href="https://radimrehurek.com/gensim/models/phrases.html">Phrase Modelling</a> 
  * Word2Vec
    * pretrained by nltk
    * pretrained by Google
    * pretrained GloVe by Stanford
    * self-trained Word2Vec
  * Topic Modelling
    * Internal LDA
    * umass Mallet
### <a href="https://github.com/hoihui/pkgs/blob/master/nltk.ipynb">nltk.ipynb</a>
  * Corpora
    * Samples
    * Special Corpora ("Lexical Resources")
    * WordNet
    * Own Corpus
  * Text exploration statistics
    * Frequencies
    * n-grams
  * Preprocessing
    * Tokenization
    * Sentence Segmentation
    * Stemming
    * Lemmatization
  * ngram Language Modelling
    * MLE $P(w|v)=\frac{P(v,w)}{P(w)}$
    * Laplace smoothing $P(w|v)=\frac{P(v,w)+1}{P(w)+V}$
    * Kneser-Ney Interpolated
  * Sequence Tagging
    * Tagged Corpora
    * Custom Tagger
    * N-gram Tagging
    * Probabilistic Graphical Model
  * Sentiment
    * VADER
### <a href="https://github.com/hoihui/pkgs/blob/master/othernlp.ipynb">othernlp.ipynb</a>
  * Stanford NLP
  * TextBlob for sentiment
  * Spacy for preprocessing
  * scikit-learn
### <a href="https://github.com/hoihui/pkgs/blob/master/pytorch.ipynb">pytorch.ipynb</a>
  * Tensors
    * Numbers
    * Linear Alegra
    * Functions
    * Autograd
    * To/from Numpy
  * Datasets
    * Images
    * MNIST
    * Cats/Dogs
  * Constructing Network
    * Instantiate
    * Initialization
    * Forward
    * Using nn. without class
  * Training Network
    * Defining loss function
    * backprop
    * Optimizer
    * On GPU
  * Inference
  * Save / Load
    * Pretrained Models
### <a href="https://github.com/hoihui/pkgs/blob/master/tensorflow_keras.ipynb">tensorflow_keras.ipynb</a>
  * Tensors
    * Numbers
    * Linear Alegra
    * Functions
    * Autograd
    * To/from Numpy
    * [TF function and AutoGraph](https://www.tensorflow.org/alpha/tutorials/eager/tf_function)
  * Datasets
    * [Keras.datasets](https://keras.io/datasets/) 
    * [tensorflow_datasets](https://www.tensorflow.org/datasets/datasets)
    * Transformation
    * Custom Dataset
    * Handling images
    * Download csv
  * Constructing Network
    * Prebuilt <a href="https://www.tensorflow.org/api_docs/python/tf/keras/layers">Layers</a>
    * Custom Layer
    * Sequential Building
    * Functional API ~nngraph
    * Common Model Properties
    * Common Layer Properties
    * Composite model specifying inputs/outputs
  * Training Network
    * Custom Training
    * Custom grad + [Keras Optimizer](https://keras.io/optimizers/)
    * Keras Loss & Optimizer
  * Save / load
    * Pretrained models from Built-in 
    * Pretrained models from TFHub
  * Custom Evaluation
  * sklearn-style interface ?
