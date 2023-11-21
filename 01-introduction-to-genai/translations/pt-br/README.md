# Introdução à IA Generativa e Modelos de Linguagem de Grande Porte

[![Introdução à IA Generativa e Modelos de Linguagem de Grande Porte](../../images/01-lesson-banner.png?WT.mc_id=academic-105485-koreyst)](https://youtu.be/YtUwjD-FFBY)

*(Clique na imagem acima para assistir ao vídeo desta aula)

A IA generativa é uma inteligência artificial capaz de gerar texto, imagens e outros tipos de conteúdo. O que a torna uma tecnologia fantástica é que ela democratiza a IA, qualquer pessoa pode usá-la com apenas um prompt de texto, uma frase escrita em linguagem natural. Não é necessário aprender uma linguagem como Java ou SQL para realizar algo valioso, tudo o que você precisa é usar sua linguagem, dizer o que deseja, e uma sugestão de um modelo de IA é gerada. As aplicações e impactos disso são enormes, você pode escrever ou entender relatórios, criar aplicativos e muito mais, tudo em questão de segundos.

Neste currículo, exploraremos como nossa startup utiliza a IA generativa para desbloquear novos cenários no mundo da educação e como lidamos com os desafios inevitáveis associados às implicações sociais de sua aplicação e às limitações tecnológicas.

    
## Introdução

Esta aula abordará:

Introdução ao cenário de negócios: nossa ideia de startup e missão.
IA generativa e como chegamos à paisagem tecnológica atual.
Funcionamento interno de um modelo de linguagem de grande porte.
Principais capacidades e casos de uso práticos de Modelos de Linguagem de Grande Porte.

## Metas de Aprendizado

AApós completar esta aula, você compreenderá:

O que é IA generativa e como os Modelos de Linguagem de Grande Porte funcionam.
Como você pode aproveitar modelos de linguagem de grande porte para diferentes casos de uso, com foco em cenários educacionais.

## Cenário: nossa startup educacional

A Inteligência Artificial Generativa (IA) representa o ápice da tecnologia de IA, ultrapassando os limites do que era considerado impossível. Modelos de IA generativa têm diversas capacidades e aplicações, mas neste currículo exploraremos como ela está revolucionando a educação por meio de uma startup fictícia. Nos referiremos a essa startup como nossa startup. Nossa startup atua no domínio da educação com a missão ambiciosa de

> *melhorar a acessibilidade na aprendizagem, em escala global, garantindo acesso equitativo à educação e proporcionando experiências de aprendizagem personalizadas a cada aluno, de acordo com suas necessidades.*.

A equipe da nossa startup está ciente de que não será capaz de alcançar esse objetivo sem aproveitar uma das ferramentas mais poderosas dos tempos modernos - os Modelos de Linguagem de Grande Porte (LLMs).

A IA generativa espera revolucionar a forma como aprendemos e ensinamos hoje, com alunos tendo à disposição professores virtuais 24 horas por dia, fornecendo vastas quantidades de informações e exemplos, e professores sendo capazes de aproveitar ferramentas inovadoras para avaliar seus alunos e fornecer feedback.

![Five young students looking at a monitor - image by DALLE2](../../images/students-by-DALLE2.png?WT.mc_id=academic-105485-koreyst)

Para começar, vamos definir alguns conceitos e terminologia básicos que usaremos ao longo do currículo.

## Como chegamos à IA Generativa?

Apesar da extraordinária *expectativa* criada ultimamente pelo anúncio de modelos de IA generativa, essa tecnologia está em desenvolvimento há décadas, com os primeiros esforços de pesquisa datando dos anos 60. Agora, estamos em um ponto em que a IA possui capacidades cognitivas humanas, como a capacidade de conversação, como mostrado, por exemplo, pelo [OpenAI ChatGPT](https://openai.com/chatgpt) ou pelo [Bing Chat](https://www.microsoft.com/edge/features/bing-chat?WT.mc_id=academic-105485-koreyst), que também utiliza um modelo GPT para as conversas na busca web do Bing.

Dando um passo para trás, os primeiros protótipos de IA consistiam em chatbots datilografados, dependendo de uma base de conhecimento extraída de um grupo de especialistas e representada em um computador. As respostas na base de conhecimento eram acionadas por palavras-chave que apareciam no texto de entrada.
No entanto, logo ficou claro que tal abordagem, usando chatbots datilografados, não escalava bem.

### Uma abordagem estatística para a IA: Aprendizado de Máquina

Um ponto de virada chegou durante os anos 90, com a aplicação de uma abordagem estatística para a análise de texto. Isso levou ao desenvolvimento de novos algoritmos - conhecidos com o nome de aprendizado de máquina - capazes de aprender padrões a partir de dados, sem serem programados explicitamente. Essa abordagem permite que uma máquina simule a compreensão da linguagem humana: um modelo estatístico é treinado em pares de texto e rótulo, permitindo que o modelo classifique um texto de entrada desconhecido com um rótulo predefinido representando a intenção da mensagem.

### Redes neurais e assistentes virtuais modernos

Em tempos mais recentes, a evolução tecnológica do hardware, capaz de lidar com quantidades maiores de dados e cálculos mais complexos, incentivou pesquisas nos campos de IA, levando ao desenvolvimento de algoritmos avançados de aprendizado de máquina - chamados de redes neurais ou algoritmos de aprendizado profundo.

As redes neurais (e em particular as Redes Neurais Recorrentes - RNNs) aprimoraram significativamente o processamento natural de linguagem, possibilitando a representação do significado do texto de uma maneira mais significativa, valorizando o contexto de uma palavra em uma frase.

Esta é a tecnologia que impulsionou os assistentes virtuais nascidos na primeira década do novo século, muito proficientes em interpretar a linguagem humana, identificando uma necessidade e realizando uma ação para satisfazê-la - como responder com um roteiro predefinido ou consumir um serviço de terceiros.

### Atualmente, IA Generativa

Então, é assim que chegamos à IA Generativa hoje, que pode ser vista como um subconjunto de aprendizado profundo.

![IA, ML, DL e IA Generativa](../../images/AI-diagram.png?WT.mc_id=academic-105485-koreyst)

Após décadas de pesquisa no campo da IA, uma nova arquitetura de modelo - chamada *Transformer* - superou os limites das RNNs, sendo capaz de obter sequências de texto muito mais longas como entrada. Os Transformers são baseados no mecanismo de atenção, permitindo que o modelo atribua diferentes pesos às entradas que recebe, 'prestando mais atenção' onde as informações mais relevantes estão concentradas, independentemente de sua ordem na sequência de texto.

A maioria dos modelos recentes de IA generativa - também conhecidos como Modelos de Linguagem Grandes (MLGs), pois trabalham com entradas e saídas textuais - são de fato baseados nessa arquitetura. O que é interessante sobre esses modelos - treinados com uma enorme quantidade de dados não rotulados de fontes diversas como livros, artigos e sites - é que podem ser adaptados a uma ampla variedade de tarefas e gerar texto gramaticalmente correto com uma semelhança de criatividade. Portanto, não apenas aumentaram incrivelmente a capacidade de uma máquina 'entender' um texto de entrada, mas também possibilitaram sua capacidade de gerar uma resposta original em linguagem humana.

## Como os grandes modelos de linguagem funcionam?

No próximo capítulo, vamos explorar diferentes tipos de modelos de IA generativa, mas por enquanto, vamos dar uma olhada em como os grandes modelos de linguagem funcionam, com foco nos modelos OpenAI GPT (Generative Pre-trained Transformer).

* **Tokenizer, texto para números**: Os Modelos de Linguagem Grandes recebem um texto como entrada e geram um texto como saída. No entanto, sendo modelos estatísticos, eles funcionam muito melhor com números do que com sequências de texto. É por isso que cada entrada no modelo é processada por um tokenizador, antes de ser usada pelo modelo principal. Um token é um trecho de texto - consistindo em um número variável de caracteres, então a principal tarefa do tokenizador é dividir a entrada em uma matriz de tokens. Em seguida, cada token é mapeado com um índice de token, que é a codificação inteira do trecho de texto original.


!![Exemplo de Tokenização](../../images/tokenizer-example.png?WT.mc_id=academic-105485-koreyst)

* **Previsão de tokens de saída**: Dados n tokens como entrada (com n máximo variando de um modelo para outro), o modelo é capaz de prever um token como saída. Esse token é então incorporado à entrada da próxima iteração, em um padrão de janela expansiva, permitindo uma melhor experiência do usuário ao obter uma (ou várias) sentenças como resposta. Isso explica por que, se você já brincou com o ChatGPT, pode ter percebido que às vezes parece parar no meio de uma frase.

* **Processo de seleção, distribuição de probabilidade**: O token de saída é escolhido pelo modelo de acordo com sua probabilidade de ocorrer após a sequência de texto atual. Isso ocorre porque o modelo prevê uma distribuição de probabilidade sobre todos os 'próximos tokens' possíveis, calculados com base em seu treinamento. No entanto, nem sempre o token com a maior probabilidade é escolhido na distribuição resultante. Um grau de aleatoriedade é adicionado a essa escolha, de modo que o modelo age de maneira não determinística - não obtemos a mesma saída exata para a mesma entrada. Esse grau de aleatoriedade é adicionado para simular o processo de pensamento criativo e pode ser ajustado usando um parâmetro do modelo chamado temperatura.

## Como nossa startup pode aproveitar os Modelos de Linguagem Grandes?

Agora que temos uma compreensão melhor do funcionamento interno de um modelo de linguagem grande, vamos ver alguns exemplos práticos das tarefas mais comuns que eles podem realizar muito bem, com um olhar para o nosso cenário de negócios.
Dissemos que a principal capacidade de um Modelo de Linguagem Grande é *gerar um texto do zero, a partir de uma entrada textual, escrita em linguagem natural*.

Mas que tipo de entrada e saída?
A entrada de um modelo de linguagem grande é conhecida como prompt, enquanto a saída é conhecida como conclusão, termo que se refere ao mecanismo do modelo de gerar o próximo token para completar a entrada atual. Vamos nos aprofundar no que é um prompt e como projetá-lo de maneira a obter o máximo do nosso modelo. Mas por enquanto, vamos apenas dizer que um prompt pode incluir:

* Uma **instrução** especificando o tipo de saída que esperamos do modelo. Essa instrução às vezes pode incorporar alguns exemplos ou alguns dados adicionais.

    1. Resumo de um artigo, livro, avaliações de produtos e mais, juntamente com a extração de insights de dados não estruturados.

    ![Exemplo de resumo](../../images/summarization-example.png?WT.mc_id=academic-105485-koreyst)

    <br>
    
    2. Ideação criativa e design de um artigo, uma redação, uma tarefa ou mais.
    
    ![Exemplo de escrita criativa](../../images/creative-writing-example.png?WT.mc_id=academic-105485-koreyst)

    <br>
    
* Uma **pergunta**, feita na forma de uma conversa com um agente.

![Exemplo de conversa](../../images/conversation-example.png?WT.mc_id=academic-105485-koreyst)

<br>

* Um trecho de **texto para completar**, que implicitamente é um pedido de assistência na escrita.

![Exemplo de conclusão de texto](../../images/text-completion-example.png?WT.mc_id=academic-105485-koreyst)

<br>

* Um trecho de **código** juntamente com a solicitação de explicá-lo e documentá-lo, ou um comentário pedindo para gerar um trecho de código que execute uma tarefa específica.

![Exemplo de codificação](../../images/coding-example.png?WT.mc_id=academic-105485-koreyst)

<br>

Os exemplos acima são bastante simples e não pretendem ser uma demonstração exaustiva das capacidades dos Modelos de Linguagem Grandes. Eles apenas querem mostrar o potencial de usar a IA generativa, em particular, mas não limitada ao contexto educacional.

Além disso, a saída de um modelo de IA generativa não é perfeita e, às vezes, a criatividade do modelo pode trabalhar contra ele, resultando em uma saída que é uma combinação de palavras que o usuário humano pode interpretar como uma mistificação da realidade, ou pode ser ofensiva. A IA generativa não é inteligente - pelo menos na definição mais abrangente de inteligência, incluindo raciocínio crítico e criativo ou inteligência emocional; não é determinística e não é confiável, pois fabricações, como referências, conteúdo e declarações errôneas, podem ser combinadas com informações corretas e apresentadas de maneira persuasiva e confiante. Nas próximas lições, lidaremos com todas essas limitações e veremos o que podemos fazer para mitigá-las.

## Tarefa

Sua tarefa é ler mais sobre [IA generativa](https://en.wikipedia.org/wiki/Generative_artificial_intelligence?WT.mc_id=academic-105485-koreyst) e tentar identificar uma área onde você adicionaria IA generativa hoje que ainda não a possui. Como o impacto seria diferente de fazer isso da "maneira antiga", você pode fazer algo que não podia antes ou é mais rápido? Escreva um resumo de 300 palavras sobre como seria sua startup de IA dos sonhos e inclua títulos como "Problema", "Como eu usaria a IA", "Impacto" e, opcionalmente, um plano de negócios.

Se você fez esta tarefa, talvez esteja pronto até para se inscrever no incubador da Microsoft, [Microsoft for Startups Founders Hub](https://www.microsoft.com/startups?WT.mc_id=academic-105485-koreyst), oferecemos créditos para Azure, OpenAI, mentoria e muito mais, confira!


## Verificação de Conhecimento

O que é verdadeiro sobre os grandes modelos de linguagem?

1. Você obtém exatamente a mesma resposta toda vez.
1. Eles fazem tudo perfeitamente, são ótimos em somar números, produzir código funcional, etc.
1. A resposta pode variar, apesar de usar o mesmo prompt. Também é ótimo para fornecer um primeiro esboço de algo, seja texto ou código. Mas você precisa melhorar os resultados.

A: 3, um LLM é não-determinístico, a resposta varia, no entanto, você pode controlar sua variância por meio de uma configuração de temperatura. Você também não deve esperar que ele faça as coisas perfeitamente, ele está aqui para fazer o trabalho pesado para você, o que muitas vezes significa que você obtém uma boa primeira tentativa de algo que precisa melhorar gradualmente.

## Ótimo Trabalho! Continue a Jornada

Após concluir esta lição, confira nossa [Coleção de Aprendizado sobre IA Generativa](https://aka.ms/genai-collection?WT.mc_id=academic-105485-koreyst) para continuar a aprimorar seus conhecimentos em IA Generativa!

Vá para a Lição 2, onde vamos aprender como [explorar e comparar diferentes tipos de LLMs](../02-exploring-and-comparing-different-llms/README.md?WT.mc_id=academic-105485-koreyst)!
