# 🎯 Copiloto de Vendas com IA para Atendimento ao Cliente — Caso FYS (Grupo HEINEKEN)

Este repositório contém o desenvolvimento de uma solução de Inteligência Artificial voltada para a otimização de vendas B2B e atendimento comercial da marca **FYS**, o refrigerante do Grupo HEINEKEN. O objetivo do projeto é equipar a força de vendas com um agente comercial inteligente capaz de entender as necessidades dos pontos de venda (PDVs), gerenciar objeções de balcão e aplicar o tom de voz único da marca.

## 💡 A Sacada do Projeto
Uma inteligência artificial performa muito melhor quando possui um contexto mercadológico rico. Utilizando insights práticos de negócios, dores reais dos pontos de venda e o posicionamento de mercado da FYS, estruturamos uma instrução de sistema (system prompt) de alta densidade que transforma qualquer IA em um especialista comercial de campo.

---

## 🧭 Desafios de Negócio Mapeados & Solucionados

A solução foi projetada sob uma abordagem ampla e objetiva, atacando diretamente os principais gargalos comerciais da marca:

1. **Reconhecimento de Marca ("Quem é FYS mesmo?"):** O copiloto traz argumentos imediatos conectando a marca à robustez logística e de qualidade do Grupo HEINEKEN para gerar confiança.
2. **Incentivo à Experimentação ("Me dá uma chance aí"):** Geração automática de scripts de abordagem focados em kits de teste iniciais e de baixo risco financeiro para o lojista.
3. **Foco em Canais Estratégicos ("Cadê a FYS na padaria?"):** Direcionamento tático para padarias e varejos de proximidade com checklists rápidos de trade marketing.
4. **Contorno de Objeções de Balcão:** Matrizes de decisão prontas para combater as desculpas mais comuns, como falta de espaço na geladeira ou medo de o produto ficar parado no estoque.
5. **Manutenção do Tom de Voz:** Respostas e mensagens calibradas de forma natural usando o humor inteligente, leve e autoirônico da marca, sem parecer robótico.

---

## 🛠️ Arquitetura do Sistema de IA

O agente comercial opera sob um fluxo estruturado dividindo sua inteligência em módulos práticos:

*   **Matriz de Classificação de PDV (Arquétipos):** Rotas específicas para padarias (ARC-01), minimercados (ARC-02), bares (ARC-03) e conveniências (ARC-04).
*   **LPSS (Lead Propensity Scoring System):** Sistema matemático interno que pontua de 0 a 10 a viabilidade comercial do lead com base em abertura, volume e espaço refrigerado disponível.
*   **Protocolo de Destruição de Objeções:** Argumentações prontas focadas em riscos financeiros e de real estate visual no PDV.
*   **Auditoria de Visibilidade (Trade Marketing):** Checklists práticos para implementação de micro-ativações locais de baixo custo.

---

## 📦 Como Utilizar o Prompt do Agente

1. Abra o arquivo de instruções do sistema contido neste projeto (ou acesse o documento gerado).
2. Copie a diretriz completa (`COGNITIVE SYSTEM INSTRUCTION`).
3. Cole na área de instruções do seu modelo de IA de preferência (ChatGPT, Gemini, Claude, etc.).
4. Insira os inputs rápidos do campo de vendas seguindo o modelo:
   * **Tipo do PDV:** *[Ex: Padaria de Bairro]*
   * **Objeção do Lojista:** *[Ex: "Não coloco na geladeira porque os clientes só pedem a marca concorrente líder"]*

---

## 🚀 Tecnologias Aplicadas
*   **Engenharia de Prompts Avançada** (Chain-of-Thought e Guardrails de Contexto)
*   **Modelos de Linguagem de Grande Porte (LLMs)**
*   **Frameworks de Soluções Comerciais B2B**

---
*Este projeto foi desenvolvido como um Desafio de Projeto prático para criar soluções reais e contextualizadas de mercado utilizando Inteligência Artificial aplicada a Vendas.*
