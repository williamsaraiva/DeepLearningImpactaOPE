# Classificação de Objetos

[Classificação de Imagens](https://en.wikipedia.org/wiki/Computer_vision#Recognition) (ou Identificação de Imagens)um dos principais casos de uso para deep learning. O objetivo dessa tarefa é trainar um modelo capaz de identificr objetos de interesse em uma imagem. 

### Classificação de Melanoma

Neste notebook, construiremos um modelo para identificar melanomas malignos. 

<img src="https://github.com/williamsaraiva/cancer_diag_with_keras/blob/master/exemp-google.jpg?raw=true" width="700" height="450" align="center"/>

Nós usaremos o [ISIC-Archive -  The International Skin Imaging Collaboration: Melanoma Project ](https://www.isic-archive.com/#!/topWithHeader/onlyHeaderTop/gallery) dataset para treino. Com mais de 20000 imagens de melanomas benignos e mais de 2000 imagens para melanomas malignos. 

Utilizamos modelos pré treinados [Using Pre-Trained Models](https://keras.rstudio.com/articles/applications.html) e [E construiremos as camadas com o modelo VGG19](https://www.kaggle.com/keras/vgg19) para classificar as imagens como benigno ou maligno.


Nos iremos:
- Preprocessar imagens;
- construir novas camadas em cima do modelo VGG19 usando Keras e Tensorflow
- Estimar a eficiência  do nosso modelo com um conjunto de teste.



Vamos nessa! 🚀
