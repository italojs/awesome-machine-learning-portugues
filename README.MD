Créditos: Essa awesome foi inspirado em [machine-learning-for-software-engineers](https://github.com/ZuzooVn/machine-learning-for-software-engineers/blob/master/README-pt-BR.md).
A diferença é aqui aqui você encontrará conteúdos em português para seus estudos.

_Se você gostou deste projeto, por favor me dê uma estrela_ &#9733; _e ajude a divulgar o material._ ;)

<a href="https://twitter.com/intent/tweet?text=Plano%20de%20estudos%20para%20Machine%20Learning%20com%20cont%C3%BAdos%20em%20portugu%C3%AAs%20https://github.com/ZuzooVn/guia-estudos-machine-learning-portgues" target="_blank">
Compartilhe no Twitter</a>

## O que é?

Este é um plano de estudos com conteúdos em português para aquels que não é conhecedor da língua inglesa.

Por favor, sinta-se livre para fazer qualquer contribuição que você achar que pode o tornar melhor.

---

## Tabela de conteúdo

- [O que é?](#o-que-é)
- [Por que usar?](#por-que-usar)
- [Como usar](#como-usar)
- [Não sinta que não é inteligente o bastante](#não-sinta-que-não-é-inteligente-o-bastante)
- [Machine learning superviosionado](#Machine-learning-superviosionado)
    - [Arvore de decisão](#Arvore-de-decisão)
    - [KNN](#KNN)
    - [Naive bayes](#Naive-bayes)
    - [Suport vector machine(SVM)](#Suport-vector-machine(SVM))
    - [Perceptron](#Perceptron)
    - [Multlayer perceptron](#Multlayer-perceptron)
    - [Redes neurais convolucionais](#Redes-neurais-convolucionais)
    - [Rede neurais recorrentes](#Rede-neurais-recorrentes)
---

## Por que usar?

Muito das pessoas que querem entra no mundo de machine learning começam pelo mais avançado que há, redes neurais com algum framwork(tensorflow, CNTK, pytorch e etc), mas antes de chegar em redes neurais é importante que você passe por outros assuntos mais básicos para então chegar a desenvolver uma rede neural de fato, ou pelo menos entender o que vocÇE está fazendo.

Aqui você encontrará um lista já pronta de assunos a serem estudados, tudo na ordem correta, assim você não terá de gastar tempo aprendendo a aprender machine learning.

Pense sobre meu interesse em Machine Learning:

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

## Como usar
Tudo abaixo é uma estrutura de tópicos, e você deve enfrentar os itens em ordem de cima para baixo.

## Não sinta que não é inteligente o bastante
Para aprender machine learning, vocÇe terá de aprender matemica, mas não se preocupe, não é tão difícil quanto parece, caso você descorde de mim, leia esse [artigo](https://medium.com/machina-sapiens/aprendendo-ia-se-voc%C3%AA-n%C3%A3o-%C3%A9-bom-em-matem%C3%A1tica-39ac167bc738)

# Machine learning superviosionado

## Arvore de decisão

## KNN
- [KNN (K-Nearest Neighbors) #1](https://medium.com/brasil-ai/knn-k-nearest-neighbors-1-e140c82e9c4e)
- [KNN (K-Nearest Neighbors) #2](https://medium.com/brasil-ai/knn-k-nearest-neighbors-2-f2ab9e5662b)
- [KNN #3 — Codando nosso classificador de câncer de mama](https://medium.com/brasil-ai/knn-3-codando-nosso-classificador-de-câncer-de-mama-eadd3b41b54b)

## Naive bayes
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
-[Classificador Naive bayes em 50 linhas](https://imasters.com.br/desenvolvimento/classificador-naive-bayes-em-50-linhas)

## Suport vector machine(SVM)

## Perceptron
- [Redes neurais roots #1 — introdução](https://medium.com/ensina-ai/redes-neurais-roots-1-introdu%C3%A7%C3%A3o-ffdd6f8b9f01)
- [Redes neurais roots #2— Treinamento](https://medium.com/ensina-ai/redes-neurais-roots-2-treinamento-3161a439c4f3)
- [Redes neurais roots #3 — Show me the code](https://medium.com/ensina-ai/redes-neurais-roots-3-show-me-the-code-e56359310083)

## Multlayer perceptron

## Redes neurais convolucionais

## Rede neurais recorrentes





