## Guia para Chatbot com Rasa

**O que é NLP:** 
Processamento de Linguagem Natural (do inglês *Natural Language Processing - NLP*) é uma subárea da IA que envolve programação de computadores  para processa um grande volume de dados de linguagem.  Envolve inúmeras tarefas que dividem a linguagem natural em elementos menores, a fim de compreender as relações entre esses elementos e como eles funcionam juntos. As tarefas comuns incluem análise, reconhecimento de fala, marcação de classes gramaticais e extração de informações. A NLP se concentra principalmente na conversão de texto em dados estruturados.

**O que é NLU:**
NLU (de *Natural Language Understanting*) tem como um dos principais objetivos ensinar as máquinas a interpretar e compreender a linguagem inserida por humanos. Tem como objetivo ensinar aos computadores o que significa um corpo de texto ou fala falada. A NLU aproveita algoritmos de IA para reconhecer atributos de linguagem, como sentimento, semântica, contexto e intenção. Ele permite que os computadores entendam as sutilezas e variações da linguagem. Por exemplo, as perguntas "como está o tempo lá fora?" e "como está o tempo?" ambos estão perguntando a mesma coisa. A pergunta "como está o tempo lá fora?" pode ser feito de centenas de maneiras. Com a NLU, os aplicativos de computador podem reconhecer as muitas variações nas quais os humanos dizem as mesmas coisas.

**NLP x NLU**
NLP é sobre o que foi dito, NLU sobre o que significou.
**NLP** analisa o texto e a fala, focando primariamente na estrutura da linguagem. **NLU** permite que o computador consiga inferir a intenção da linguagem, mesmo quando a escrita ou a fala apresentem falhas.
Se a necessidade é um chatbot simples que produz uma série de respostas programadas, apenas o NLP é necessário. Já se a necessidade é um chatbot inteligente que consiga usar o contexto, capaz de ter conversas naturais e sofisticadas com o usuário, também é necessário o uso da NLU. É importante entender essa diferença, pois isso impacta o que aplicativo interpreta do que foi dito pelo usuário.

## Rasa
### Rasa NLU
Os modelos Rasa NLU tem próprios componentes personalizados (analisador de sentimento, verificador ortográfico, tokenizador de nível de caractere, codificador de par de bytes, etc)

**Rasa NLU Pipeline**
Um pipeline de processamento é o bloco de construção principal do modelo Rasa NLU. 

Actions: 

Detalhes de implementação de actions customizadas ver em [SDK Documentation](https://rasa.com/docs/action-server/running-action-server). 
Qualquer ação personalizada que é usada nos stories deve ser adicionada na seção de ações do domain. 