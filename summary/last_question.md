<h1 align="center">Last Question</h1>

[back to index](../README.md)

## Rules of Conduct
 * The contributors are sorted by first commit on the question.
 * The question in each topic are sorted from most recent (newest) to least recent (oldest). If same topic and same year, then ascending order of `Question_number`
 * Answers may be improved
 * Different answers can be given
 * If possible upload missing PDFs to the [exams folder](../exames/)
 * Do not use big headings in answers
 * Avoid large images to make this printable

## Question and Answer Template:

```markdown
### 20XX/20YY - [Normal|Recurso] - Question_number [pdf](../exames/20XX_N.pdf)
#### Question:
This is the Question

#### Answer 1:
This is the first answer. If there is doubt then multiple can exist

[[source1](...), [source2](...)] by [@contributor_to_answer_1, @contributor_to_answer_2, ...]

---
```

---


# Topic 1 - Search Methods


# Topic 2 - Evolutionary Algorithms


# Topic 3 - Uncertain Reasoning


# Topic 4 - Natural Language Processing (NLP)


# Topic 5 - Artificial Neural Networks (ANN)

### 2015/2016 - Normal - g) [pdf](../exames/2016_N.pdf)
#### Question:
Construiu-se uma rede neuronal com **30** neurónios de entrada, 1 camada escondida com 20 neurónios, e 2 neurónios na camada de saída. Os neurónios de cada camada ligam a todos os neurónios da camada seguinte. Em termos teóricos, quantos exemplos de treino são necessários para que a rede consiga generalizar? 

#### Answer 1:
Se considerarmos o paralelismo entre arquitetura e treino de redes neuronais para com sistemas de equações, em que:
 1. o número de ligações independentes = nº variáveis
 2. nº saídas x nº exemplos = nº equações
 
Então, tentando verificar a equação `nº saídas x nº exemplos >= nº ligações independentes`, temos que `nº exemplos >= (nº ligações independentes / nº saídas)`. No caso concreto: `nº ligações independentes = 30*20 + 20*2 = 640`, ou seja, `NE >= (640/2) >= 320`. 

Em termos teóricos, são necessários pelo menos 320 exemplos de treino para que a rede consiga generalizar.

[[slide 42](https://web.fe.up.pt/~eol/IA/1718/APONTAMENTOS/7_RN_DL.pdf)] by [@msramalho]

---