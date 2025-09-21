# Projeto de ChatBot - Indústria, Inovação e Infraestrutura

## 1. Repositório do Projeto no GitHub



## 2. Planejamento para a TP2 no GitHub Projects
**Título do Projeto:** ChatBot Inteligente para Informações sobre ODS 9  


**Backlog da TP2 (Próxima Entrega):**
| Tarefa                                                         | Responsável | Status      |
|----------------------------------------------------------------|-------------|-------------|
| Definir arquitetura do chatbot (NLP, fluxos de conversação)    |        | To Do       |
| Criar protótipo da interface de chat                           |      | To Do       |
| Coletar e estruturar base de conhecimento sobre ODS 9          |       | To Do       |
| Configurar ambiente de desenvolvimento com bibliotecas de NLP  |       | To Do       |
| Implementar integração com API de tradução (se necessário)     |       | To Do       |
| Documentar decisões técnicas e fluxos de conversação           |      | To Do       |

## 3. Definição de Requisitos do Projeto (em markdown)

### i) Objetivo do Trabalho
Desenvolver um chatbot inteligente que forneça informações especializadas sobre o ODS 9 (Indústria, Inovação e Infraestrutura) da ONU, capaz de responder perguntas, explicar conceitos e orientar usuários sobre como contribuir para essas metas.

### ii) Problema a Ser Resolvido
Dificuldade de acesso a informações claras e centralizadas sobre o ODS 9, seus objetivos, metas e formas de contribuição, tanto para cidadãos comuns quanto para profissionais e gestores públicos.

### iii) Tipo de Aplicação
Chatbot conversacional com interface web e mobile, utilizando processamento de linguagem natural (NLP) para compreender perguntas em linguagem coloquial e fornecer respostas contextualizadas.

### iv) Requisitos Funcionais
- RF01: Sistema de reconhecimento de intenções e entidades em perguntas dos usuários
- RF02: Base de conhecimento sobre ODS 9 com informações atualizadas
- RF03: Múltiplos fluxos de conversação (metas, indicadores, como contribuir)
- RF04: Sistema de aprendizado contínuo com feedback das interações
- RF05: Integração com APIs de informações complementares (dados estatísticos)
- RF06: Geração de relatórios de interações para análise de uso

### v) Requisitos Não Funcionais
- RNF01: Tempo de resposta inferior a 1 segundo para perguntas
- RNF02: Precisão mínima de 85% no entendimento das intenções
- RNF03: Suporte a pelo menos 100 usuários simultâneos
- RNF04: Dados de conversas criptografados em trânsito e em repouso
- RNF05: Interface acessível seguindo diretrizes WCAG 2.1

### vi) Dados de Uso Previstos
- Público-alvo: Estudantes, profissionais, gestores públicos e cidadãos interessados em ODS
- Estimativa de usuários: 1000+ interações/mês
- Canais: Web, mobile (com possível expansão para WhatsApp e Telegram)
- Idiomas: Português (com possibilidade de expansão para espanhol e inglês)

## 4. Tecnologias Previstas
- Framework de NLP: Rasa ou Dialogflow
- Backend: Python + FastAPI
- Frontend: React.js para interface web
- Banco de dados: MongoDB para armazenar conversas e conhecimentos
- Deploy: Docker containers em AWS ou Google Cloud
- Monitoramento: ELK Stack para análise de logs e interações

## 5. Metodologia de Desenvolvimento
- Processo: Scrum com sprints de 2 semanas
- Versionamento: Git com GitFlow
- Documentação: Wiki do GitHub para documentação técnica
- Integração contínua: GitHub Actions para testes automatizados
- Implantação contínua: Deploy automático em ambientes de staging

## 6. Cronograma Preliminar
- TP2 (2 semanas): Definição de arquitetura e coleta de conhecimento
- TP3 (2 semanas): Implementação do motor de NLP e fluxos básicos
- TP4 (2 semanas): Desenvolvimento da interface e integrações
- TP5 (2 semanas): Testes de usabilidade e refinamento
- TP6 (2 semanas): Implantação em produção e treinamento do modelo

Este projeto utilizará técnicas de processamento de linguagem natural para criar um assistente virtual especializado no ODS 9, capaz de responder perguntas complexas e guiar os usuários em sua jornada de understanding e contribuição para as metas de indústria, inovação e infraestrutura sustentáveis.
