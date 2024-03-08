# Processamento de Fala

- Acessar a plataforma de serviços de voz do Azure em https://speech.azure.cn/portal

![](https://github.com/Victor-Ribeiro-Acosta/Bootcamp-Azure-AI-Fundamentals-Processamento-de-Fala-e-Mineracao-Conhecimento/blob/main/Passos/1.png)

- Vamos acessar o serviço de Conversão de fala em texto em tempo real

![](https://github.com/Victor-Ribeiro-Acosta/Bootcamp-Azure-AI-Fundamentals-Processamento-de-Fala-e-Mineracao-Conhecimento/blob/main/Passos/2.png)

- No campo inicial, vamos definir o idioma da fala como protugês

![](https://github.com/Victor-Ribeiro-Acosta/Bootcamp-Azure-AI-Fundamentals-Processamento-de-Fala-e-Mineracao-Conhecimento/blob/main/Passos/3.png)

- Na guia de "Próximos Passos" podemos observar duas formas de inserir arquivos de audio para a conversão:
  
    1. Inserir um arquivo de audio para a aplicação
    2. Gravar um audio imediatamente
  
![](https://github.com/Victor-Ribeiro-Acosta/Bootcamp-Azure-AI-Fundamentals-Processamento-de-Fala-e-Mineracao-Conhecimento/blob/main/Passos/4.png)

- Logo abaixo do menu fica salvo o audio inserido
- Em resultados do teste, a direita, é apresentada a conversão do audio em texto
    - A IA possui dificuldades em transcrever gírias ou formas coloquiais de linguagem
![](https://github.com/Victor-Ribeiro-Acosta/Bootcamp-Azure-AI-Fundamentals-Processamento-de-Fala-e-Mineracao-Conhecimento/blob/main/Passos/5.png)


# Mineracao de Conhecimento e Análise de Sentimentos

## Primeiro Passo: Criar recurso na plataforma do Azure

- Na plataforma do Azure, criaremos um recurso

![](https://github.com/Victor-Ribeiro-Acosta/Bootcamp-Azure-AI-Fundamentals-Processamento-de-Fala-e-Mineracao-Conhecimento/blob/main/Passos/6.png)

- Escolheremos o recurso de análise de texto

![](https://github.com/Victor-Ribeiro-Acosta/Bootcamp-Azure-AI-Fundamentals-Processamento-de-Fala-e-Mineracao-Conhecimento/blob/main/Passos/7.png)

- Na aba seleção de feições, marcaremos todas as opções disponíveis

![](https://github.com/Victor-Ribeiro-Acosta/Bootcamp-Azure-AI-Fundamentals-Processamento-de-Fala-e-Mineracao-Conhecimento/blob/main/Passos/8.png)

- Nas configurações de recurso, selecionaremos:
    - Nossa subscrição
    - O grupo de recursos
    - Região
    - Nome do recurso
    - Tipo de conta

![](https://github.com/Victor-Ribeiro-Acosta/Bootcamp-Azure-AI-Fundamentals-Processamento-de-Fala-e-Mineracao-Conhecimento/blob/main/Passos/9.png)

- Criaremos o recurso

## Segundo passo: Configurar o Language Studio

- Acessaremos a plataforma do Language Studio em https://language.cognitive.azure.com/
- Faremos login
- Definiremos as configurações básicas como:
    - Subscrição
    - Tipo de serviço a ser utilizado
    - Recurso de analise de texto criado na plataforma Azure

![](https://github.com/Victor-Ribeiro-Acosta/Bootcamp-Azure-AI-Fundamentals-Processamento-de-Fala-e-Mineracao-Conhecimento/blob/main/Passos/10.png)

- Acessaremos a guia classificação de texto e escolheremos o serviço de análise de sentimentos em opiniões

![](https://github.com/Victor-Ribeiro-Acosta/Bootcamp-Azure-AI-Fundamentals-Processamento-de-Fala-e-Mineracao-Conhecimento/blob/main/Passos/11.png)

- Definiremos a linguagem do texto a ser analisado e o recurso a ser utilizado (criado na plataforma do Azure)
- Na caixa de texto, vamos inserir o texto a ser analizado

![](https://github.com/Victor-Ribeiro-Acosta/Bootcamp-Azure-AI-Fundamentals-Processamento-de-Fala-e-Mineracao-Conhecimento/blob/main/Passos/12.png)

- Ao executar o algoritmo, poderemos observar a análise em "Examinar Resultados"

![](https://github.com/Victor-Ribeiro-Acosta/Bootcamp-Azure-AI-Fundamentals-Processamento-de-Fala-e-Mineracao-Conhecimento/blob/main/Passos/13.png)

- A primeira informação é os níveis de sentimentos registrados: Positivo, Neutro e Negativo
    - Nesse exemplo, a maioria das opiniões foram classificadas como negativas
    
- Após é apresentada algumas sentenças e as palavras-chave identificadas para a classificação

![](https://github.com/Victor-Ribeiro-Acosta/Bootcamp-Azure-AI-Fundamentals-Processamento-de-Fala-e-Mineracao-Conhecimento/blob/main/Passos/15.png)

- Abaixo vem a classificação da sentença e da opinião apresentada

![](https://github.com/Victor-Ribeiro-Acosta/Bootcamp-Azure-AI-Fundamentals-Processamento-de-Fala-e-Mineracao-Conhecimento/blob/main/Passos/16.png)

- Por último é apresentado o texto completo com as palavras-chave destacas nas sentenças

![](https://github.com/Victor-Ribeiro-Acosta/Bootcamp-Azure-AI-Fundamentals-Processamento-de-Fala-e-Mineracao-Conhecimento/blob/main/Passos/17.png)
