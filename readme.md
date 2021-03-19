## Guia para Chatbot com Rasa
Versão Rasa
Versão Spacy

- [x] NLP
- [x] NLU
- [ ] sPacy
- [ ] Rasa
- [ ] Pré-requisitos
- [ ] Instalação

**O que é NLP:** 
Processamento de Linguagem Natural (do inglês *Natural Language Processing - NLP*) é uma subárea da IA que envolve programação de computadores  para processa um grande volume de dados de linguagem. É considerado o cérebro do chatbot (1) e envolve inúmeras tarefas que dividem a linguagem natural em elementos menores, a fim de compreender as relações entre esses elementos e como eles funcionam juntos. As tarefas comuns incluem análise, reconhecimento de fala, marcação de classes gramaticais e extração de informações. A NLP se concentra principalmente na conversão de texto em dados estruturados.

**O que é NLU:**
NLU (de *Natural Language Understanting*), em termos simples, é uma subárea da grande área NLP, assim como machine learning, deep learning são subáreas da inteligência artificial (1). Tem como um dos principais objetivos ensinar as máquinas a interpretar e compreender a linguagem inserida por humanos. Tem como objetivo ensinar aos computadores o que significa um corpo de texto ou fala falada. A NLU aproveita algoritmos de IA para reconhecer atributos de linguagem, como sentimento, semântica, contexto e intenção. Ele permite que os computadores entendam as sutilezas e variações da linguagem. Por exemplo, as perguntas "como está o tempo lá fora?" e "como está o tempo?" ambos estão perguntando a mesma coisa. A pergunta "como está o tempo lá fora?" pode ser feito de centenas de maneiras. Com a NLU, os aplicativos de computador podem reconhecer as muitas variações nas quais os humanos dizem as mesmas coisas.

**NLP x NLU**
NLP é sobre o que foi dito, NLU sobre o que significou.
**NLP** analisa o texto e a fala, focando primariamente na estrutura da linguagem. **NLU** permite que o computador consiga inferir a intenção da linguagem, mesmo quando a escrita ou a fala apresentem falhas.
Se a necessidade é um chatbot simples que produz uma série de respostas programadas, apenas o NLP é necessário. Já se a necessidade é um chatbot inteligente que consiga usar o contexto, capaz de ter conversas naturais e sofisticadas com o usuário, também é necessário o uso da NLU. É importante entender essa diferença, pois isso impacta o que aplicativo interpreta do que foi dito pelo usuário.

## spaCy
É uma biblioteca open-source para NLP avançado, escrita em Python e Cython. Ela fornece acesso a APIs intuitivas de métodos trainados de modelos de deep learnig. O spaCy oferece modelos estatísticos de redes neurais para uma ampla variedade de linbguagens como português, inglês, francês, italiano, alemão, espanhol. spaCy é uma das melhores bibliotecas disponíveis na comunidade de código aberto para processar
texto para algoritmos de aprendizado profundo. Ele colabora perfeitamente com TensorFlow, PyTorch,
scikit-learn, Gensim e o resto das tecnologias relacionadas ao Python. Aprendizagem profunda
os desenvolvedores podem construir facilmente modelos estatísticos linguisticamente sofisticados para uma gama de problemas de NLP/NLU (1).
**Características do sPacy:**  
(checar o quanto isso está atualizado)
• Tokenização não destrutiva
• Reconhecimento de entidade nomeada
• Suporte para mais de 28 idiomas
• 13 modelos estatísticos para 8 idiomas
• Vetores de palavras pré-treinados
• Fácil integração de aprendizagem profunda
• Marcação de parte da fala
• Análise de dependência rotulada
• Segmentação de frase baseada em sintaxe
• Visualizadores integrados para sintaxe e NER
• Mapeamento conveniente de string para hash
• Exportar para matrizes de dados numpy
• Serialização binária eficiente
• Fácil embalagem e implantação do modelo
• Velocidade de última geração
• Precisão robusta e avaliada com rigor
(1)

**Modelos spaCy**
Os modelos spaCy são como qualquer outro modelo de machine ou deep learning. 

## Rasa
### Rasa NLU
Os modelos Rasa NLU tem próprios componentes personalizados (analisador de sentimento, verificador ortográfico, tokenizador de nível de caractere, codificador de par de bytes, etc)

**Rasa NLU Pipeline**
Um pipeline de processamento é o bloco de construção principal do modelo Rasa NLU.

## Pré-requisitos para Instalação
O básico: Python. 
Aqui estamos usando Python 3 na versão 3.8.5

## Instalação


Actions:

Detalhes de implementação de actions customizadas ver em [SDK Documentation](https://rasa.com/docs/action-server/running-action-server). 
Qualquer ação personalizada que é usada nos stories deve ser adicionada na seção de ações do domain. 

1. Sumit Raj; Building Chatbots with Python.