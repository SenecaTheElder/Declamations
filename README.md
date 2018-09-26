# Declamations

This repo will be used to organize my workflow. I will primarily focus on data analysis, but may also delve into machine learning, deep learning, logic, and/or AI safety. I will primarily program in **Python**, but am considering also learning a functional programming language.

* [Data Collection](#getData)
* [Algorithmic Learning](#learning)
    * [Keras](#keras)

## Data Collection <a name="getData"></a>

* [spaCy: *the Ruby on Rails of NLP*](https://spacy.io)
* [Towards Natural Language Semantic Code Search](https://githubengineering.com/towards-natural-language-semantic-code-search/) -- Github
* [How To Create Natural Language Semantic Search for Arbitrary Objects with Deep Learning](https://towardsdatascience.com/semantic-code-search-3cd6d244a39c)

## Algorithmic Learning <a name="learning"></a>

* [Keras](#keras)

### Keras <a name="keras"></a>
The Tensorflow Docker images are already configured to run Tensorflow. A Docker container runs in a virtual environment and is the easiest way to set up [GPU support](https://www.tensorflow.org/install/). 

```
docker pull tensorflow/tensorflow                  # Download latest image
docker run -it -p 8888:8888 tensorflow/tensorflow  # Start a Jupyter notebook server
```

[Get started with Keras](https://www.tensorflow.org/guide/keras)

* [A ten-minute introduction to sequence-to-sequence learning in Keras](https://blog.keras.io/a-ten-minute-introduction-to-sequence-to-sequence-learning-in-keras.html)
* [How to Develop an Encoder-Decoder Model for Sequence-to-Sequence Prediction in Keras](https://machinelearningmastery.com/develop-encoder-decoder-model-sequence-sequence-prediction-keras/)

