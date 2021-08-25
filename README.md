# ReckogBot
> Chatbot desenvolvido utilizando Python. Esse chatbot utilizou técnicas de aprendizado de máquina para proporcionar a capacidade de reconhecer contextos. A intenção é reconhecer um padrão no texto escrito em Inglês pelo usuário (“fala do usuário”) e classifica-lo em uma determinada categoria, para responder de forma apropriada. Vale destacar que a “inteligência” do sistema está na detecção de contexto, resultando em uma resposta pre-existente na base de conhecimento. Assim, o chatbot não é um gerador de textos, e sim um reconhecedor de texto.

## Instalação dos componentes necessários

Ferramentas que utilizei para implementação e teste da API:

1. [PyCharm](https://www.jetbrains.com/pt-br/pycharm/download/#section=windows)

2. [Python](https://www.python.org/downloads/)

3. [TensorFlow](https://www.tensorflow.org/)


## Funções implementadas no chatbot:


- `clean_up_sentences`: responsável por limpar as frases e transformá-las na sua forma mais enxuta possível;


- `get_response`: percorre a lista de possíveis tags e retorna a resposta correspondente;


- `bag_of_words`: responsável por converter uma sentença em uma lista de palavras e verificar se essa lista de palavras se encaixa no modelo pré-treinado;

- `predict_class`: para prever em qual tag a “bag_of_words” se encaixa, utilizando as duas funções anteriores.


## Autor 👦🏻

Feito com muito ☕ e ❤ por mim, Leonardo .