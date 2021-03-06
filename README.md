
<!-- README.md is generated from README.Rmd. Please edit that file -->

## Configuração inicial

#### Passo 1: Instalar pacotes

``` r
install.packages("remotes")

# instalar pacote da Curso-R
remotes::install_github("curso-r/CursoR")

# instalar pacotes que vamos usar durante o curso
CursoR::instalar_dependencias()
```

#### Passo 2: Criar um projeto do RStudio

Faça um projeto do RStudio para usar durante todo o curso e em seguida
abra-o.

``` r
install.packages("usethis")
usethis::create_package("caminho_ate_o_projeto/nome_do_projeto")
```

#### Passo 3: Baixar o material

Certifique que você está dentro do projeto criado no passo 2 e rode o
código abaixo.

**Observação**: Assim que rodar o código abaixo, o programa vai pedir
uma escolha de opções. Escolha o número correspondente ao curso de Deep
Learning\!

``` r
# Baixar ou atualizar material do curso
CursoR::atualizar_material()
```

## Slides

| slide             | link                                                             |
| :---------------- | :--------------------------------------------------------------- |
| slides/index.html | <https://curso-r.github.io/main-deep-learning/slides/index.html> |

## Scripts usados em aula

#### Exemplos

| exemplo                    | link                                                                                       |
| :------------------------- | :----------------------------------------------------------------------------------------- |
| 01-linear-regression.R     | <https://curso-r.github.io/deep-learning-com-r-mestre/exemplos/01-linear-regression.R>     |
| 02-sgd.R                   | <https://curso-r.github.io/deep-learning-com-r-mestre/exemplos/02-sgd.R>                   |
| 03-keras.R                 | <https://curso-r.github.io/deep-learning-com-r-mestre/exemplos/03-keras.R>                 |
| 04-mlp.R                   | <https://curso-r.github.io/deep-learning-com-r-mestre/exemplos/04-mlp.R>                   |
| 05-regressao-logistica.R   | <https://curso-r.github.io/deep-learning-com-r-mestre/exemplos/05-regressao-logistica.R>   |
| 06-convolution.R           | <https://curso-r.github.io/deep-learning-com-r-mestre/exemplos/06-convolution.R>           |
| 07-conv-mnist.R            | <https://curso-r.github.io/deep-learning-com-r-mestre/exemplos/07-conv-mnist.R>            |
| 08-tfhub.R                 | <https://curso-r.github.io/deep-learning-com-r-mestre/exemplos/08-tfhub.R>                 |
| 09-text-vectorization.R    | <https://curso-r.github.io/deep-learning-com-r-mestre/exemplos/09-text-vectorization.R>    |
| 10-embedding.R             | <https://curso-r.github.io/deep-learning-com-r-mestre/exemplos/10-embedding.R>             |
| 11-avg-pooling.R           | <https://curso-r.github.io/deep-learning-com-r-mestre/exemplos/11-avg-pooling.R>           |
| 12-simple-rnn.R            | <https://curso-r.github.io/deep-learning-com-r-mestre/exemplos/12-simple-rnn.R>            |
| 13-simple-lstm.R           | <https://curso-r.github.io/deep-learning-com-r-mestre/exemplos/13-simple-lstm.R>           |
| 14-lstm.R                  | <https://curso-r.github.io/deep-learning-com-r-mestre/exemplos/14-lstm.R>                  |
| 15-pre-trained-embedding.R | <https://curso-r.github.io/deep-learning-com-r-mestre/exemplos/15-pre-trained-embedding.R> |
| 15-simple-gru.R            | <https://curso-r.github.io/deep-learning-com-r-mestre/exemplos/15-simple-gru.R>            |
| 16-gru.R                   | <https://curso-r.github.io/deep-learning-com-r-mestre/exemplos/16-gru.R>                   |
| 17-pre-trained-embedding.R | <https://curso-r.github.io/deep-learning-com-r-mestre/exemplos/17-pre-trained-embedding.R> |
| 18-encadeando-lstms.R      | <https://curso-r.github.io/deep-learning-com-r-mestre/exemplos/18-encadeando-lstms.R>      |
| 19-bidirecional.R          | <https://curso-r.github.io/deep-learning-com-r-mestre/exemplos/19-bidirecional.R>          |
| 20-quora.R                 | <https://curso-r.github.io/deep-learning-com-r-mestre/exemplos/20-quora.R>                 |
| 21-series-temporais.R      | <https://curso-r.github.io/deep-learning-com-r-mestre/exemplos/21-series-temporais.R>      |
| 22-unet.R                  | <https://curso-r.github.io/deep-learning-com-r-mestre/exemplos/22-unet.R>                  |
| 23-captcha.R               | <https://curso-r.github.io/deep-learning-com-r-mestre/exemplos/23-captcha.R>               |

#### Exercicios

| exercicio                    | link                                                                                           |
| :--------------------------- | :--------------------------------------------------------------------------------------------- |
| 01-linear-regression.R       | <https://curso-r.github.io/deep-learning-com-r-mestre/exercicios/01-linear-regression.R>       |
| 02-mini-batch-sgd.R          | <https://curso-r.github.io/deep-learning-com-r-mestre/exercicios/02-mini-batch-sgd.R>          |
| 03-keras-linear-regression.R | <https://curso-r.github.io/deep-learning-com-r-mestre/exercicios/03-keras-linear-regression.R> |
| 04-boston-housing.R          | <https://curso-r.github.io/deep-learning-com-r-mestre/exercicios/04-boston-housing.R>          |
| 05-boston-housing-logistic.R | <https://curso-r.github.io/deep-learning-com-r-mestre/exercicios/05-boston-housing-logistic.R> |
| 06-mlp-mnist.R               | <https://curso-r.github.io/deep-learning-com-r-mestre/exercicios/06-mlp-mnist.R>               |
| 07-cifar-conv.R              | <https://curso-r.github.io/deep-learning-com-r-mestre/exercicios/07-cifar-conv.R>              |
| 08-dropout-batch-norm.R      | <https://curso-r.github.io/deep-learning-com-r-mestre/exercicios/08-dropout-batch-norm.R>      |
| 09-fruit360.R                | <https://curso-r.github.io/deep-learning-com-r-mestre/exercicios/09-fruit360.R>                |
| 10-sarcasm.R                 | <https://curso-r.github.io/deep-learning-com-r-mestre/exercicios/10-sarcasm.R>                 |
| 11-lstm-sarcasm.R            | <https://curso-r.github.io/deep-learning-com-r-mestre/exercicios/11-lstm-sarcasm.R>            |
| 12-pre-trained-sarcasm.R     | <https://curso-r.github.io/deep-learning-com-r-mestre/exercicios/12-pre-trained-sarcasm.R>     |
| 13-bidirecional-sarcasm.R    | <https://curso-r.github.io/deep-learning-com-r-mestre/exercicios/13-bidirecional-sarcasm.R>    |
| 14-quora.R                   | <https://curso-r.github.io/deep-learning-com-r-mestre/exercicios/14-quora.R>                   |

#### Respostas

| exercicio                    | link                                                                                          |
| :--------------------------- | :-------------------------------------------------------------------------------------------- |
| 01-linear-regression.R       | <https://curso-r.github.io/deep-learning-com-r-mestre/respostas/01-linear-regression.R>       |
| 02-mini-batch-sgd.R          | <https://curso-r.github.io/deep-learning-com-r-mestre/respostas/02-mini-batch-sgd.R>          |
| 03-keras-linear-regression.R | <https://curso-r.github.io/deep-learning-com-r-mestre/respostas/03-keras-linear-regression.R> |
| 04-boston-housing.R          | <https://curso-r.github.io/deep-learning-com-r-mestre/respostas/04-boston-housing.R>          |
| 05-boston-housing-logistic.R | <https://curso-r.github.io/deep-learning-com-r-mestre/respostas/05-boston-housing-logistic.R> |
| 06-mlp-mnist.R               | <https://curso-r.github.io/deep-learning-com-r-mestre/respostas/06-mlp-mnist.R>               |
| 07-cifar-conv.R              | <https://curso-r.github.io/deep-learning-com-r-mestre/respostas/07-cifar-conv.R>              |
| 08-dropout-batch-norm.R      | <https://curso-r.github.io/deep-learning-com-r-mestre/respostas/08-dropout-batch-norm.R>      |
| 09-fruit360.R                | <https://curso-r.github.io/deep-learning-com-r-mestre/respostas/09-fruit360.R>                |
| 10-sarcasm.R                 | <https://curso-r.github.io/deep-learning-com-r-mestre/respostas/10-sarcasm.R>                 |
| 11-lstm-sarcasm.R            | <https://curso-r.github.io/deep-learning-com-r-mestre/respostas/11-lstm-sarcasm.R>            |
| 12-pre-trained-sarcasm.R     | <https://curso-r.github.io/deep-learning-com-r-mestre/respostas/12-pre-trained-sarcasm.R>     |
| 13-bidirecional-sarcasm.R    | <https://curso-r.github.io/deep-learning-com-r-mestre/respostas/13-bidirecional-sarcasm.R>    |
| 14-quora.R                   | <https://curso-r.github.io/deep-learning-com-r-mestre/respostas/14-quora.R>                   |
