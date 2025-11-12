# Tutorial: Como Rodar o Fluxo LA Data Consolidation no Langflow

Este tutorial explica o **passo a passo** de como rodar o **fluxo** dentro do **Langflow**, desde a configuração inicial até a execução completa.  
O objetivo é auxiliar usuários a entenderem como importar, configurar e executar o fluxo de maneira correta.

---

## 1. Baixando o Langflow

Antes de começar, é necessário ter o **Langflow** instalado no seu computador. O aplicativo está disponível na loja da IBM.

## 2. Abrindo um fluxo do tipo Basic Prompting

Com o Langflow aberto:
Clique em **“New Flow”** no canto superior direito.
Na janela de modelos, selecione o template chamado “Basic Prompting”.

![Exemplo do template Basic Prompting](imagens/basic_prompting.png)

## 3. Substituindo a LLM pelo modelo IBM Watson AI
O fluxo **“Basic Prompting”** vem com uma caixinha de modelo de linguagem padrão.
Antes de rodar o fluxo, vamos substituí-la pelo componente da IBM watsonx.ai.
Clique sobre a caixa da LLM existente no fluxo e clique em **delete**
No painel lateral esquerdo, vá até a aba Components.
No campo de busca, digite “IBM”.
Arraste o componente chamado **IBM watsonx.ai** para dentro do fluxo. É a segunda caixinha da lista

![Componente IBM watsonx.ai]()

Conecte-o novamente à caixa de entrada (Input) e à caixa de saída (Output), da mesma forma que estava o modelo anterior.
