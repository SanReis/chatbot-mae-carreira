# Maternidade em Ação: Desbloqueando Seu Potencial Profissional

## ✨ Sobre o Projeto

**Finalidade e Utilidade:** Muitas mães desenvolvem um conjunto incrível de habilidades durante a maternidade – pense em resiliência sob pressão, negociação constante, gestão de projetos complexos (rotina da família!), empatia e liderança situacional. No entanto, essas competências valiosas muitas vezes não são formalmente reconhecidas ou facilmente traduzidas para o mercado de trabalho, criando barreiras na progressão ou no retorno à carreira.

O projeto **Maternidade em Ação** nasceu para resolver esse problema. É um chatbot projetado para ser uma **aliada inteligente** na sua jornada, ajudando a **identificar, articular e valorizar** esse tesouro de competências desenvolvidas fora do ambiente corporativo tradicional.

## 💡 Como Funciona (Eficácia e Criatividade)

**Criatividade na Interação:** Longe de ser um formulário ou uma lista genérica, o chatbot **Maternidade em Ação** interage através de uma conversa guiada. Ele te convida a refletir sobre situações *reais* e *específicas* do seu dia a dia como mãe.

**Eficácia na Análise e Tradução:**
1.  **Exploração Narrativa:** O chatbot faz perguntas estratégicas sobre como a mãe lidou com desafios na maternidade (gerenciar múltiplas tarefas, resolver conflitos entre filhos, planejar eventos familiares, etc.).
2.  **Análise Inteligente:** Utiliza **Inteligência Artificial (Google Gemini)** para analisar a *essência* das respostas e identificar as habilidades profissionais subjacentes que demonstrou naquela situação. Não apenas busca palavras-chave, mas compreende o contexto da "ação" e "resultado".
3.  **Tradução para a Carreira:** As habilidades identificadas são traduzidas para o vocabulário do mercado de trabalho. O chatbot sugere frases e exemplos que pode usar diretamente no **currículo, perfil do LinkedIn, ou como resposta em entrevistas**, conectando a experiência materna às exigências profissionais.

Essa abordagem criativa transforma a própria narrativa da maternidade em uma fonte poderosa e validada de desenvolvimento profissional.

## ✅ Funcionalidades Principais

* Conversa interativa para explorar experiências de maternidade.
* Identificação de habilidades profissionais (como Multitarefa, Resiliência, Negociação, Liderança, etc.) usando IA.
* Tradução e reformulação de experiências em linguagem de carreira.
* Sugestões de frases prontas para currículo e LinkedIn.
* Preparação para articular experiências em entrevistas.
* Reconhecimento e valorização do potencial das mães.

## 🚀 Como Rodar o Chatbot

Para executar o **Maternidade em Ação** na sua máquina ou ambiente (como Google Colab), siga os passos abaixo:

1.  **Clone ou baixe** o código deste repositório para o seu computador.
2.  Certifique-se de ter o **Python 3** instalado.
3.  Instale a biblioteca necessária:
    ```bash
    pip install google-generativeai
    ```
4.  Obtenha uma **Chave de API para o Google Gemini** no [Google AI Studio](https://aistudio.google.com/app/apikey).
5.  Configure sua Chave API como uma **variável de ambiente** com o nome `GOOGLE_API_KEY`.
    * **No Google Colab:** Use o painel "Secrets" (ícone de chave 🔑 no menu lateral esquerdo) e adicione um novo "segredo" chamado `GOOGLE_API_KEY` com o valor da sua chave.
    * **Localmente (Linux/Mac):** Abra o terminal e execute `export GOOGLE_API_KEY='SUA_CHAVE_AQUI'` (substitua `SUA_CHAVE_AQUI` pela sua chave). Para tornar permanente, adicione essa linha ao seu arquivo de perfil (como `~/.bashrc` ou `~/.zshrc`).
    * **Localmente (Windows):** Configure a variável de ambiente através das Configurações do Sistema (procure por "variáveis de ambiente").
    **⚠️ Aviso de Segurança: Nunca cole sua chave API diretamente no código-fonte (`.py`) que você pretende compartilhar publicamente no GitHub!**
6.  Abra o terminal ou prompt de comando na pasta onde você salvou o arquivo Python do chatbot.
7.  Execute o script Python:
    ```bash
    python nome_do_seu_arquivo_chatbot.py
    ```
    (Substitua `nome_do_seu_arquivo_chatbot.py` pelo nome real do arquivo Python que você salvou).
8.  Interaja com o chatbot diretamente no terminal.

## 💻 Tecnologias Utilizadas

* **Python:** Linguagem de programação principal.
* **Google Generative AI (Gemini 2.5 Flash):** Modelo de IA utilizado para análise e identificação de habilidades.
