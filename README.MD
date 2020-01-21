# Plano de estudos em machine learning com conteúdos em português.

### Créditos: 

Essa awesome foi inspirado em [machine-learning-for-software-engineers](https://github.com/ZuzooVn/machine-learning-for-software-engineers/blob/master/README-pt-BR.md).
A diferença é aqui aqui você encontrará conteúdos em português para seus estudos.

_Se você gostou deste projeto, por favor dê uma estrela_ &#9733; _e ajude a divulgar o material._ ;)

<a href="https://twitter.com/intent/tweet?text=Plano%20de%20estudos%20para%20Machine%20Learning%20com%20conte%C3%BAdos%20em%20portugu%C3%AAs%20https://github.com/italojs/awesome-machine-learning-portugues" target="_blank">
Compartilhe no Twitter</a> :bird:

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

## O que é?

Este é um plano de estudos com conteúdos em português para aqueles que não são conhecedores da língua inglesa.

Por favor, sinta-se livre para fazer qualquer contribuição que você achar que pode o tornar melhor.

---

## Alfinetada/lembrete

Fulano(a), sei que não é fácil aprender inglês, mas só queria lembrar que você está perdendo MUITO conteúdo em não focar nessa língua, você perde muito conteúdo e os assuntos que não consegue estudar em inglês, muito provavelmente são assuntos atrasados, se você estudasse tudo isso em inglês veria o quádruplo de contéudo. Não quero que você pare de estudar machine learning (programação em geral na verdade), mas olha, começe a se cobrar um pouco mais nese ponto :wink:

Agora vamos estudar machine learning até o talo! :punch:

## Tabela de conteúdo :ballot_box_with_check:

- [O que é? :interrobang:](#o-que-é)
- [Por que usar? :interrobang:](#por-que-usar)
- [Como usar? :interrobang:](#como-usar)
- [Não sinta que não é inteligente o bastante :poop:](#não-sinta-que-não-é-inteligente-o-bastante)
- [Assuntos introdutórios :baby:](#Assuntos-introdutórios)
    - [classificação vs predição](#classificação-vs-predição)
- [Machine learning superviosionado](#Machine-learning-superviosionado)
    - [Árvore de decisão](#Árvore-de-decisão)
    - [KNN](#KNN)
    - [Naive bayes](#Naive-bayes)
    - [Support vector machine(SVM)](#Support-vector-machine(SVM))
    - [Regressão linear](#Regressão-linear)
    - [Perceptron](#Perceptron)
    - [Regressão logística](#Regressão-logística)
    - [Função de custo](#Função-de-custo)
    - [Gradient Descent](#Gradient-Descent)
    - [Multilayer perceptron](#Multilayer-perceptron)
    - [Redes neurais convolucionais](#Redes-neurais-convolucionais)]
    - [Adaboost](#Adaboost)
    - [Rede neurais recorrentes](#Rede-neurais-recorrentes)
- [Machine learning não superviosionado](#Machine-learning-não-superviosionado)
---
## Por que usar?

Muito das pessoas que querem entra no mundo de machine learning começam pelo mais avançado que há, redes neurais com algum framwork(tensorflow, CNTK, pytorch e etc), mas antes de chegar em redes neurais é importante que você passe por outros assuntos mais básicos para então chegar a desenvolver uma rede neural de fato, ou pelo menos entender o que você está fazendo.

Aqui você encontrará um lista já pronta de assunos a serem estudados, tudo na ordem correta, assim você não terá de gastar tempo aprendendo a aprender machine learning.

- [Posso aprender e arrumar um emprego em Machine Learning sem estudar mestrado e Phd em Ciência da Computação?](https://www.quora.com/Can-I-learn-and-get-a-job-in-Machine-Learning-without-studying-CS-Master-and-PhD)
    - *"Você pode, mas isto é muito mais difícil do que quando eu entrei no campo."* [Drac Smith](https://www.quora.com/Can-I-learn-and-get-a-job-in-Machine-Learning-without-studying-CS-Master-and-PhD/answer/Drac-Smith?srid=oT0p)

- [Como eu consigo um emprego em Machine Learning como um programador de software que auto-estudou  Machine Learning, mas nunca teve a chance de usar isso no trabalho?](https://www.quora.com/How-do-I-get-a-job-in-Machine-Learning-as-a-software-programmer-who-self-studies-Machine-Learning-but-never-has-a-chance-to-use-it-at-work)
    - *"Estou contratando especialistas de Machine Learning para minha equipe e seu MOOC não vai conseguir para você o trabalho (há melhores notícias abaixo). Na verdade, muitas pessoas com um mestrado em Machine Learning não terão o emprego porque eles (e a maioria que tomaram MOOC) não têm uma compreensão profunda que vai me ajudar a resolver os meus problemas."* [Ross C. Taylor](https://www.quora.com/How-do-I-get-a-job-in-Machine-Learning-as-a-software-programmer-who-self-studies-Machine-Learning-but-never-has-a-chance-to-use-it-at-work/answer/Ross-C-Taylor?srid=oT0p)

- [Que habilidades são necessárias para trabalhos de Machine Learning?](http://programmers.stackexchange.com/questions/79476/what-skills-are-needed-for-machine-learning-jobs)
    - *"Primeiramente, você precisa ter um decente background de Ciência da Computação/Matemática. ML é um tópico avançado, então a maioria dos livros didáticos assumem que você tem esse background. Por segundo, Machine Learning é um tema muito geral com várias sub especialidades que exigem habilidades únicas. Você pode querer procurar o currículo de um programa de MS em Machine Learning para ver o curso, o currículo e livro didático."* [Uri](http://softwareengineering.stackexchange.com/a/79717)
    - *"Estatística, propabilidade, computação distribuída e estatística."* [Hydrangea](http://softwareengineering.stackexchange.com/a/79575)

Eu me encontro em tempos difíceis.

AFAIK, [Há dois lados para Machine Learning](http://machinelearningmastery.com/programmers-can-get-into-machine-learning/):
- Prática de Machine Learning: Isto é sobre bancos de dados de consultas, limpeza de dados, escrevendo scripts para transformar dados e colagem de algoritmo e bibliotecas juntos e escrever código personalizado para espremer respostas confiáveis de dados para satisfazer as perguntas difíceis e mal definidas. É a porcaria da realidade.
- Teoria de Machine Learning: Isto é sobre matemática e abstração e cenários idealizados e limites e beleza e informando o que é possível. É muito mais puro e mais limpo e removido da confusão da realidade.

Eu acho que a melhor maneira para metodologia centrada na prática é algo como ['prática - aprendizagem - prática'](http://machinelearningmastery.com/machine-learning-for-programmers/#comment-358985), que significa onde estudantes primeiro vêm com alguns projetos existentes com problemas e soluções (prática) para se familiarizar com os métodos tradicionais na área e talvez também com sua metodologia.Depois de praticar com algumas experiências elementares, podem ir para os livros e estudar a teoria subjacente, que serve para guiar a sua futura prática avançada e reforçará a sua caixa de ferramentas de solução de problemas práticos. Estudar a teoria também melhora ainda mais sua compreensão sobre as experiências elementares e irá ajudá-los a adquirir experiências avançadas mais rapidamente.

É um plano longo. Isso vai demorar anos para mim. Se você já está familiarizado com bastante disso já, você levará muito menos tempo.

## Como usar?
Tudo abaixo é uma estrutura de tópicos, e você deve enfrentar os itens em ordem de cima para baixo.
Não precisa ver todos os links, mas você tem que entender cada um dos tópicos.

## Não sinta que não é inteligente o bastante 
Para aprender machine learning, você terá de aprender matemática, mas não se preocupe, não é tão difícil quanto parece, caso você discorde de mim, leia esse [artigo](https://medium.com/machina-sapiens/aprendendo-ia-se-voc%C3%AA-n%C3%A3o-%C3%A9-bom-em-matem%C3%A1tica-39ac167bc738)

# Assuntos introdutórios
- [O que é machine learning?](https://medium.com/brasil-ai/o-que-%C3%A9-machine-learning-94cc71c2a6e3)
- [Tipos de dados do seu dataset](https://medium.com/brasil-ai/antes-de-come%C3%A7armos-a-falar-sobre-tipos-de-aprendizados-que-veremos-no-pr%C3%B3ximo-artigo-%C3%A9-ea5b04685913)
- [Tipos de aprendizagem](https://medium.com/brasil-ai/tipos-de-aprendizagem-1c1339f73bdf)
- [Uma breve introdução ao Machine Learning](https://www.youtube.com/watch?v=WgUrONLhons)
- [As 10 Principais Arquiteturas de Redes Neurais](http://deeplearningbook.com.br/as-10-principais-arquiteturas-de-redes-neurais/)
- [Machine Learning (Aula 3) - Aprendizado Supervisionado e não Supervisionado](https://www.youtube.com/watch?v=OWt8BW6Tb6o)

## classificação vs predição
- [Machine Learning (Aula 7) - Modelos de Predição](https://www.youtube.com/watch?v=2vRUdnQ1X74&t=278s)
- [Machine Learning em Português (Aula 8) - Modelo de Classificação de Íris Parte 1](https://www.youtube.com/watch?v=WRQmC8QU_YU)

# Machine Learning Supervisionado

## Árvore de Decisão
- [Árvores de Decisão](https://medium.com/machine-learning-beyond-deep-learning/%C3%A1rvores-de-decis%C3%A3o-3f52f6420b69)
- [ÁRVORE DE DECISÃO. EXEMPLO COMPLETO](https://www.youtube.com/watch?v=_ICNdRrl68k)
- [Um tutorial completo sobre modelagem baseada em árvores de decisão (códigos R e Python)](https://www.vooo.pro/insights/um-tutorial-completo-sobre-a-modelagem-baseada-em-tree-arvore-do-zero-em-r-python/)
- [Implementação em Python](https://github.com/arnaldog12/Machine_Learning/blob/master/Decision%20Trees.ipynb)

## KNN - K-Vizinhos Mais Próximos (_K-Nearest Neighbors_)
- [KNN (K-Nearest Neighbors) #1](https://medium.com/brasil-ai/knn-k-nearest-neighbors-1-e140c82e9c4e)
- [KNN (K-Nearest Neighbors) #2](https://medium.com/brasil-ai/knn-k-nearest-neighbors-2-f2ab9e5662b)
- [KNN #3 — Codando nosso classificador de câncer de mama](https://medium.com/brasil-ai/knn-3-codando-nosso-classificador-de-câncer-de-mama-eadd3b41b54b)
- [Machine Learning em Português (Aula 11) - Explicando K-NN (Regressão e Classificação)](https://www.youtube.com/watch?v=bzIsfLgTEQw)
- [Machine Learning em Português (Aula 15) - K-Nearest Neighbors (Regressão - Parte 2)](https://www.youtube.com/watch?v=Cz6NCHSY0Z0)
- [Implementação em Python](https://github.com/arnaldog12/Machine_Learning/blob/master/KNN.ipynb)

## Naive Bayes
- [Teorema de Bayes](https://www.youtube.com/watch?v=9OOZf4klOeM)
- [Teorema de Bayes - Aula 1: Características (Probabilidade a Priori, Condicional e Conjunta)](https://www.youtube.com/watch?v=78R1yNVGnSk&t=244s)
- [Teorema de Bayes - Aula 2: a Posteriori](https://www.youtube.com/watch?v=mTfI6ggVNyQ&list=PL4OAe-tL47sadpBP4atfVFBbKm-Fh160J&index=2)
- [Teorema de Bayes (Aula 3) - Usando o teorema para calcular sorteio de uma roleta](https://www.youtube.com/watch?v=Buvp2kFnIbs&index=3&list=PL4OAe-tL47sadpBP4atfVFBbKm-Fh160J)
- [Teorema de Bayes (Aula 4) - Explicando o cálculo do vídeo anterior](https://www.youtube.com/watch?v=WZLf5sSIzAc&index=4&list=PL4OAe-tL47sadpBP4atfVFBbKm-Fh160J)
- [Teorema de Bayes (Aula 5) - Caminho pela raridade do item no Diablo (Parte 1)](https://www.youtube.com/watch?v=dNLqMphjUjw&index=5&list=PL4OAe-tL47sadpBP4atfVFBbKm-Fh160J)
- [Teorema de Bayes (Aula 6) - Caminho pela raridade do item (Parte 2)](https://www.youtube.com/watch?v=X1I29qqXszs&index=6&list=PL4OAe-tL47sadpBP4atfVFBbKm-Fh160J)
- [Teorema de Bayes (Aula 7) Vídeo Correção - Nomenclaturas](https://www.youtube.com/watch?v=Wcb4_pnADEE&index=7&list=PL4OAe-tL47sadpBP4atfVFBbKm-Fh160J)
- [Teorema de Bayes (Aula 8) - Bayes Sequencial](https://www.youtube.com/watch?v=Y1DnDnCYeQU&list=PL4OAe-tL47sadpBP4atfVFBbKm-Fh160J&index=8)
- [Naive Bayes | Carlos Baldove | Papo Reto](https://www.youtube.com/watch?v=3HJVRBEMwoU)
- [Classificador Naive bayes em 50 linhas](https://imasters.com.br/desenvolvimento/classificador-naive-bayes-em-50-linhas)

## SVM - Máquina de Vetores de Suporte (_Support Vector Machine_)
- [Uma Introdução às Support Vector Machines](https://www.mql5.com/pt/articles/584)
- [Explicar o algoritmo SVR](https://pt.stackoverflow.com/a/40149/20728)
- [Máquina de Vetores de Suporte - SVM](https://www.youtube.com/watch?v=4Zh7UeHqHvc)
- [SVM - Support Vector Machine Linear, Não Linear - Teoria](https://www.youtube.com/watch?v=cB__Oa85htg)

## Regressão Linear
- [Regressão linear simples](https://medium.com/ensina-ai/regress%C3%A3o-linear-simples-4cac67c4488c)
- [Regressão Linear (Parte 1) - Machine Learning em Português (Aula 12)](https://www.youtube.com/watch?v=MgtIdBrf0v8)
- [Regressão Linear (Parte 2) - Machine Learning (Aula 13)](https://www.youtube.com/watch?v=jh4m0WN-n48)
- [Machine Learning (Aula 21) - Regressão Linear no R](https://www.youtube.com/watch?v=Km1HoKVkd6k)
- [Implementação em Python](https://github.com/arnaldog12/Machine_Learning/blob/master/Regressão%20Linear.ipynb)

## Regressão Multivariada
- [Implementação em Python](https://github.com/arnaldog12/Machine_Learning/blob/master/Regressão%20Multilinear.ipynb)

## Regressão Polinomial
- [Implementação em Python](https://github.com/arnaldog12/Machine_Learning/blob/master/Regressão%20Polinomial.ipynb)

## Perceptron
- [Redes neurais roots #1 — introdução](https://medium.com/ensina-ai/redes-neurais-roots-1-introdu%C3%A7%C3%A3o-ffdd6f8b9f01)
- [Redes neurais roots #2— Treinamento](https://medium.com/ensina-ai/redes-neurais-roots-2-treinamento-3161a439c4f3)
- [Redes neurais roots #3 — Show me the code](https://medium.com/ensina-ai/redes-neurais-roots-3-show-me-the-code-e56359310083)
- [Aula - Perceptron e Adaline](https://www.youtube.com/watch?v=6yYUc6nU3Cw&list=PLSZEVLiOtIgF19_cPrvhJC2bWn-dUh1zB&index=2&t=0s)
- [Máquinas de vetores-suporte ](ftp://ftp.dca.fee.unicamp.br/pub/docs/vonzuben/ia353_1s13/topico8_1s2013.pdf)
- [Máquina de vetores de suporte(código)](http://artificiencia.com/aprenda/maquina-de-vetores-de-suporte/)

## Regressão Logística
- [O que é uma regressão logística?](http://carloscollares.blogspot.com/2011/05/o-que-e-uma-regressao-logistica.html)
- [EB - Aula 6 Teórica - Regressão logística](https://www.youtube.com/watch?v=Fs8LhzhEMwI)
- [EB - Aula 6 prática - Regressão Logística](https://www.youtube.com/watch?v=CVL5vj1N1U8)
- [Você sobreviveria no Titanic? Um exemplo de Regressão Logística](http://www.abgconsultoria.com.br/blog/voce-sobreviveria-no-titanic-um-exemplo-de-regressao-logistica/)
- [Regressão Logística na Eleição](https://medium.com/@silviocesar_75950/regress%C3%A3o-log%C3%ADstica-na-elei%C3%A7%C3%A3o-3d8011469712)

## Função de Custo
- [Função de Custo (Regressão Linear) - Machine Learning em Português (Aula 14)](https://www.youtube.com/watch?v=jSaJjshIAUw)
- [Calculando a Função de Custo (Regressão Linear) - Machine Learning (Aula 15)](https://www.youtube.com/watch?v=kHfhMsCoUus)
- [Valor Mínimo da Função de Custo (Regressão Linear) - Machine Learning (Aula 16)](https://www.youtube.com/watch?v=ikmxun1t-HM)

## Gradiente Descendente (_Gradient Descent_)
- [Gradient Descent (Regressão Linear - Parte 1) - Machine Learning (Aula 17)](https://www.youtube.com/watch?v=xdDL_8Sg6JI&t=404s)
- [Calculando Gradient Descent Parte 1 (Regressão Linear) - Machine Learning (Aula 18)](https://www.youtube.com/watch?v=6lbX-MI5B6M)
- [Como verificar o Gradient Descent (Regressão Linear) - Machine Learning (Aula 20)](https://www.youtube.com/watch?v=yraCrOa3mzk)

## Multilayer Perceptron
- [Redes Neurais, Perceptron Multicamadas e o Algoritmo Backpropagation](https://medium.com/ensina-ai/redes-neurais-perceptron-multicamadas-e-o-algoritmo-backpropagation-eaf89778f5b8)

## Redes Neurais Convolucionais
- [Redes Neurais profundas Convolucionais - Parte I - Fundamentos](https://www.youtube.com/watch?v=n4rmrZg1_58&list=PLSZEVLiOtIgF19_cPrvhJC2bWn-dUh1zB&index=5&t=1s)
- [Redes Neurais profundas Convolucionais - Parte II - Arquiteturas Modernas](https://www.youtube.com/watch?v=0XUrLfQXzcw&list=PLSZEVLiOtIgF19_cPrvhJC2bWn-dUh1zB&index=5)
- [Parametrização de redes neurais profundas](https://www.youtube.com/watch?v=qDmKwmkc4vs&list=PLSZEVLiOtIgF19_cPrvhJC2bWn-dUh1zB&index=7)

- Extra: [Arquiteturas de redes neurais profundas para detecção de objetos](https://www.youtube.com/watch?v=BhwppCyV2iI&list=PLSZEVLiOtIgF19_cPrvhJC2bWn-dUh1zB&index=8)
 
 ## Adaboost
- [Estudo do algoritmo adaboost de aprendizagem de máquina aplicado a sensores e sistemas embarcados](http://www.teses.usp.br/teses/disponiveis/3/3152/tde-12062012-163740/pt-br.php)
- [Implementação em Python](https://github.com/arnaldog12/Machine_Learning/blob/master/Adaboost.ipynb)

## Rede Neurais Recorrentes
- [Redes Neurais Recorrentes (RNN) - LSTM, GRU, Seq2seq e Mecanismos de atenção](https://www.youtube.com/watch?v=94hG00EJFNo&list=PLSZEVLiOtIgF19_cPrvhJC2bWn-dUh1zB&index=6)
- [Redes Neurais Recorrentes(tem código)](https://www.youtube.com/watch?v=bDDP0m4jjH0)
- [Keras - Usando redes neurais LSTM para classificar sentimentos](https://www.youtube.com/watch?v=bIcadBu--u8)

# Machine Learning Não-Supervisionado

## PCA - Análise de Componentes Principais (_Principal Component Analysis_)
- [Implementação em Python](https://github.com/arnaldog12/Machine_Learning/blob/master/PCA.ipynb)

## LDA - Análise Discriminante Linear (_Linear Discriminant Analysis_)
- [Implementação em Python](https://github.com/arnaldog12/Machine_Learning/blob/master/LDA.ipynb)

## K-Médias (_K-Means_)
- [Implementação em Python](https://github.com/arnaldog12/Machine_Learning/blob/master/K-Means.ipynb)
