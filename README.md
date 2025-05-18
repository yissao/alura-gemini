# alura-gemini
# 🎬 Sumarizador Inteligente de Vídeos do YouTube com IA

Transforme vídeos longos em resumos claros, rápidos e úteis — com o poder da IA!  
Ideal para quem quer **aprender mais em menos tempo**. 🚀

---

## ✨ O que este projeto faz?

Este app utiliza **transcrições automáticas de vídeos do YouTube** e a IA do **Gemini (Google AI)** para gerar:

✅ Um **resumo detalhado e corrigido**  
✅ Correção de erros da transcrição automática  
✅ Destaques dos principais tópicos, exemplos e conclusões  
✅ Tudo isso com um clique!

---

## 🧠 Como funciona?

1. Cole a **ID do vídeo** de um vídeo do YouTube.
2. ex: https://www.youtube.com/watch?v=7xco9igjUAQ -> **ID = 7xco9igjUAQ**
3. O sistema entende o contexto e corrige erros de fala, pontuação e digitação.
4. A IA gera um resumo claro e preciso do conteúdo do vídeo.

---

## 💻 Tecnologias usadas

- [Python](https://www.python.org/)
- [Google Generative AI (Gemini)](https://ai.google.dev/)
- [Google Colab](https://colab.research.google.com/) — sem instalação necessária

---

## 🚀 Como usar

1. Crie sua API Key no [Google AI Studio](https://makersuite.google.com/app/apikey)
2. Clone o repositório:

   ```bash
   git clone https://github.com/yissao/alura-gemini.git
   cd alura-gemini
---
---
# Exemplo de resumo:
---
## Anotações e Resumo da Aula 2 da Imersão Alura - Google Gemini: Engenharia de Prompt

**Público-alvo:** Interessados em inteligência artificial, profissionais que desejam otimizar o uso do Gemini para aumentar a produtividade e eficiência, e aqueles que lidam com análise de dados.

**Objetivo do vídeo:** Ensinar os conceitos e técnicas de engenharia de prompt para obter os melhores resultados com o Google Gemini, utilizando exemplos práticos e demonstrações.

### Principais Tópicos Abordados:

1. **O que é Engenharia de Prompt:**
    
    - É o processo de projetar e refinar a mensagem (prompt) enviada a um modelo de linguagem para obter a resposta mais precisa e relevante possível.
    - Envolve a arte de "engenhar" os detalhes do prompt para direcionar o modelo ao resultado desejado.
    - Analogia com um estagiário inteligente: o modelo tem muito conhecimento, mas precisa de direcionamento para entregar a resposta específica que você precisa.
2. **A Importância da Especificidade:**
    
    - Quanto mais específico for o prompt, melhor será a qualidade do resultado.
    - Exemplo prático:
        - Prompt genérico: "Me fale sobre a cidade de São Paulo." (Resposta ampla e genérica)
        - Prompt específico: "Me fale sobre os três maiores clubes de futebol da cidade de São Paulo." (Resposta focada e precisa)
3. **Técnicas de Engenharia de Prompt:**
    
    - **Dividir tarefas complexas em subtarefas:**
        
        - Em vez de pedir tudo de uma vez, dividir o prompt em etapas menores e mais claras.
        - Exemplo: Criação de uma campanha de viagem para a Turquia dividida em: pesquisa de passeios, organização do plano de viagem e criação de posts para o Instagram.
    - **Definir um papel (persona) para o modelo:**
        
        - Atribuir uma persona ao modelo para direcionar a resposta com base em um contexto específico.
        - Exemplo: "Aja como um especialista de redes sociais que trabalha para uma agência de viagens..."
4. **Tipos de Prompts:**
    
    - **Zero-shot prompts:**
        
        - Não fornecem exemplos ao modelo, apenas a instrução.
        - Exemplo: "Me dê os melhores passeios da Turquia com uma avaliação."
    - **Few-shot prompts:**
        
        - Fornecem alguns exemplos (amostras) para guiar o modelo.
        - Os exemplos podem ser do formato desejado para a resposta ou do conteúdo em si.
        - Exemplo: "Me dê os melhores passeios da Turquia com uma avaliação no formato: Nome do passeio - Cidade - Avaliação." (Exemplo de formato)
        - Exemplo: "Aí a Sofia - Istambul - 10/10" (Exemplo de conteúdo)
5. **Chain of Thought (Cadeia de Pensamento):**
    
    - Ensinar o modelo a pensar passo a passo, como você faria.
    - Combinar Chain of Thought com Few-shot para melhores resultados.
    - Exemplo:
        - Definir a persona: "Aja como um gerente de redes sociais..."
        - Dar exemplos do seu tom de escrita (Few-shot).
        - Instruir o modelo a analisar os exemplos e, em seguida, gerar um post com base em uma nova base fornecida.
6. **Geração de Imagens:**
    
    - O Gemini pode gerar imagens a partir de descrições textuais (text-to-image).
    - É possível refinar a imagem gerada através de prompts adicionais.
    - Exemplo: "Gere uma imagem com base no post abaixo."
7. **Análise de Documentos e Geração de Gráficos:**
    
    - O Gemini pode analisar documentos (PDFs, etc.) e extrair informações relevantes.
    - É possível comparar informações de diferentes documentos.
    - O modelo pode gerar gráficos a partir dos dados extraídos.
    - Exemplo: Análise comparativa de relatórios financeiros de dois bancos (Banco do Brasil e Caixa Econômica Federal) e geração de gráficos com os resultados.

### Termos Técnicos:

- **Prompt:** A mensagem ou instrução enviada a um modelo de linguagem.
- **LLM (Large Language Model):** Modelo de linguagem grande, como o Gemini.
- **Zero-shot Prompt:** Prompt sem exemplos.
- **Few-shot Prompt:** Prompt com alguns exemplos.
- **Chain of Thought:** Técnica de engenharia de prompt que ensina o modelo a pensar passo a passo.
- **Text-to-image:** Processo de gerar imagens a partir de descrições textuais.
- **ROA (Return on Assets):** Retorno sobre ativos.
- **ROE (Return on Equity):** Retorno sobre o patrimônio líquido.
- **MOE (Mixture of Experts):** Arquitetura de LLM onde diferentes partes do modelo realizam tarefas diferentes.

### Conclusões:

- A engenharia de prompt é fundamental para obter o máximo do Google Gemini.
- A especificidade, a divisão de tarefas, a definição de personas e o uso de exemplos (few-shot) são técnicas importantes.
- O Gemini pode ser usado para diversas tarefas, desde a criação de conteúdo de marketing até a análise de documentos financeiros e geração de gráficos.
- A combinação de diferentes técnicas de engenharia de prompt pode levar a resultados ainda melhores.
