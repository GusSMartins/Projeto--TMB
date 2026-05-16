# 🏋️‍♂️ Fitness Calculator Pro

O **Fitness Calculator Pro** é uma aplicação web moderna, responsiva e de alta performance projetada para ajudar entusiastas do mundo fitness, atletas e iniciantes a calcularem suas métricas metabólicas, gerenciarem macronutrientes e acompanharem planejamentos de treino e dieta de forma totalmente personalizada.

Este projeto foi portado e evoluído a partir de um sistema legado robusto escrito em linguagem C, recebendo uma interface de usuário premium baseada no conceito de *Glassmorphic Dark Dashboard*.

---

## 🚀 Funcionalidades

O ecossistema do projeto é dividido em módulos dinâmicos e fáceis de navegar através da barra lateral:

*   **Metabolismo (TMB/GET):** Cálculos biológicos precisos da Taxa Metabólica Basal e Gasto Energético Total baseados nas fórmulas clássicas de Harris-Benedict (com distinção de gênero, idade, peso e altura).
*   **Macronutrientes Dinâmicos:** Cálculo exato de gramas e calorias necessárias para Proteínas, Gorduras e Carboidratos baseado no objetivo selecionado (Ganho de Massa, Perda de Gordura ou Manutenção).
*   **Módulo IMC:** Diagnóstico imediato do Índice de Massa Corporal com tabela de referência integrada que destaca automaticamente a sua faixa atual.
*   **Guias de Treino:** Divisão completa de treinos de academia (Ficha ABCDE) e protocolos de Cardio (como HIIT) adaptados aos objetivos do usuário.
*   **Dietas & Nutrição:** Sugestões estruturadas de cardápios diários (Café, Almoço e Jantar) e uma linha do tempo metrificada com os horários ideais para se alimentar.
*   **Acompanhamento de Progresso:** Um plano estratégico detalhado focado em uma jornada de evolução para 12 semanas.
*   **Exportação de Relatórios:** Sistema nativo capaz de gerar e baixar um arquivo de texto (`.txt`) compilando todos os dados informados e resultados do usuário.

---

## 🎨 Design & Visual Premium

*   **Interface Dark Mode:** Cores profundas (`#0f172a` e `#1e293b`) que reduzem o cansaço visual e dão uma estética moderna.
*   **Totalmente Responsivo:** Menu lateral inteligente que se recolhe em dispositivos móveis, transformando-se em um app mobile fluído.
*   **Arquitetura Vanilla:** Construído utilizando apenas HTML5, CSS3 moderno (com variáveis e CSS Grid/Flexbox) e JavaScript Puro (Vanilla JS). **Zero frameworks ou dependências pesadas.**

---

## 📂 Estrutura de Arquivos

O projeto é limpo e direto, composto por apenas três arquivos principais:

```bash
├── index.html      # Estrutura semântica e esqueleto das abas do dashboard
├── style.css       # Estilização completa, variáveis de cor e regras de responsividade
└── script.js       # Toda a lógica matemática e manipulação dinâmica do DOM
