# Agentes_Entrevistador_planejador_carreiras
prompts prontos para ajuda a definir sua carreira.
# AI Career Path Finder - Multi-Agent System 🚀

Este projeto apresenta um sistema de dois agentes de IA projetado para conduzir entrevistas profissionais, analisar perfis técnicos e gerar planos de estudos personalizados.

O sistema foi desenhado para simular um fluxo de consultoria real, utilizando técnicas avançadas de **Prompt Engineering** e **Handoff de Contexto**.

## 🤖 Os Agentes

1.  **Agente 1 (O Entrevistador):** Especialista em extração de perfil. Utiliza uma entrevista estruturada de 7 perguntas para avaliar motivações, stack técnica e objetivos (Ex: Transição de carreira para o setor bancário).
2.  **Agente 2 (O Estrategista):** Especialista em educação e carreira. Recebe os dados do Agente 1 e gera um cronograma híbrido (Teoria + Prática) com foco em eficiência.

## 🛠️ Tecnologias e Técnicas Aplicadas

*   **Prompt Engineering:** Uso de instruções de sistema (System Instructions) complexas, delimitadores de seção e regras de comportamento rigorosas.
*   **Handoff de Contexto:** Protocolo definido para transferência de variáveis entre modelos ou sessões.
*   **Persona Design:** Atribuição de tons específicos para cada fase da jornada do usuário.
*   **Foco em Setor Bancário/Fintech:** Otimizado para identificar oportunidades em SQL Server e Automação.

## 📊 Fluxo de Funcionamento (Handoff)

O projeto utiliza um gatilho de transferência chamado `HANDOFF`. Quando o usuário escolhe uma carreira, o Agente 1 consolida:
- `Horas/Semana`
- `Nível de Experiência`
- `Objetivo (Transição/Promoção)`
- `Stack de Interesse (Python/SQL/IA)`

## 🚀 Como Utilizar

Os prompts estruturados estão disponíveis na pasta `/prompts`. Eles podem ser utilizados em LLMs como:
- GPT-4o
- Claude 3.5 Sonnet
- Google Gemini 1.5 Pro

---
**Autor:** Filipe Cabral
*Atualmente em transição para Tech/Analytics | Especialista em Processos Bancários*

