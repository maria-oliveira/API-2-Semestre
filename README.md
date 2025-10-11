# 🎯 TechForce - TG Control

<img width="1366" height="768" alt="Imagem do Sistema" src="https://github.com/user-attachments/assets/adb62b93-78c0-4436-8ff7-2d5fe202f5f4" />

---

## 🗂 Tópicos  

[Descrição do projeto](#descrição) | [Tecnologias](#tecnologias-utilizadas) | [Funcionalidades](#funcionalidades) | [Backlog do Produto](#backlog-do-produto) | [Backlog da Sprint](#backlog-da-sprint) | [User Stories](#user-stories) | [Sprints](#sprints) | [Documentação](#documentação-do-projeto) | [Equipe](#equipe)

---

## 📖 Descrição
Gerenciar o ciclo dos Trabalhos de Graduação (TG) da modalidade Portfólio é um desafio para alunos, professores orientadores e coordenação, pois o processo de envio, correção e acompanhamento das seções ocorre de forma descentralizada em plataformas pouco adequadas (como e-mail institucional e MS Teams), o que gera atrasos, falha de notificações e risco de perda de mensagens; para os alunos, a dor está na demora dos feedbacks e na dificuldade de entregar o TG final em formato MD, enquanto os professores orientadores enfrentam problemas para manter histórico claro das correções e versões, e a coordenação tem dificuldade em monitorar o progresso dos trabalhos, o que torna essencial uma plataforma centralizada que organize, registre e acompanhe cada etapa, garantindo comunicação eficiente, rastreabilidade e geração facilitada do TG final.

---

## 🛠 Tecnologias Utilizadas

[![Java](https://img.shields.io/badge/Java-007396?logo=java&logoColor=white)](https://www.java.com/) 
[![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)](https://github.com/) 
[![Figma](https://img.shields.io/badge/Figma-F24E1E?logo=figma&logoColor=white)](https://www.figma.com/) 
[![Jira](https://img.shields.io/badge/Jira-0052CC?logo=jira&logoColor=white)](https://www.atlassian.com/software/jira) 
[![Scene Builder](https://img.shields.io/badge/Scene%20Builder-0091EA?logo=java&logoColor=white)](https://gluonhq.com/products/scene-builder/) 
[![JavaFX](https://img.shields.io/badge/JavaFX-FF0000?logo=openjdk&logoColor=white)](https://openjfx.io/)

---

## 📌 Backlog do Produto

| Rank | Prioridade | User Story | Estimativa | Sprint |
|------|------------|------------|------------|--------|
| 1 | **Alta** | Visualizar protótipo funcional com principais funcionalidades. | 2 | 1 |
| 2 | **Alta** | Envio de seções do TG diretamente para o orientador. | 6 | 2 |
| 3 | **Alta** | Correção e feedback direto no sistema. | 6 | 2 |
| 4 | **Alta** | Acesso a versões anteriores das seções. | 5 | 2 |
| 5 | **Alta** | Notificações automáticas para aluno e professor. | 6 | 2 |
| 6 | **Alta** | Visualização e atualização do status das seções. | 3 | 2 |
| 7 | **Média** | Histórico completo de seções, versões e feedbacks. | 12 | 2 |
| 8 | **Média** | Geração automática do TG consolidado em Markdown. | 8 | 3 |
| 9 | **Baixa** | Estatísticas sobre tempo médio de correção e interações. | 5 | 3 |
| 10 | **Baixa** | Visualizar alunos que concluíram todas as seções. | 3 | 3 |
| 11 | **Baixa** | Gerenciar cadastros de professores. | 4 | 3 |

---

## 🗓 Cronograma das Sprints

| Sprint | Período | Entrega |
|--------|---------|---------|
| 1 | 08/09 – 29/09 | Protótipos |
| 2 | 06/10 – 26/10 | Envio de Seções, Feedback, Histórico, Notificações, Status, Geração de TG |
| 3 | 03/11 – 23/11 | Gerenciamento de Cadastros, Estatísticas |

---

## Sprint 2 
# Backlog

| Rank | Prioridade | User Story | Estimativa | Sprint |
|------|------------|------------|------------|--------|
| 2 | **Alta** | Envio de seções do TG pelo aluno. | 6 | 2 |
| 3 | **Alta** | Correção e feedback pelo professor. | 6 | 2 |
| 4 | **Alta** | Acesso a versões anteriores das seções. | 5 | 2 |
| 5 | **Alta** | Notificações automáticas aluno/professor. | 6 | 2 |
| 6 | **Alta** | Visualização e atualização de status. | 3 | 2 |
| 7 | **Média** | Histórico completo de seções, versões e feedbacks. | 12 | 2 |

---

## 📄Definition of Ready (DoR)

| ID | User Story | Objetivo | Requisitos Específicos |
|----|------------|----------|-----------------------|
| US01 | Envio de Seções | Enviar seções do TG para o orientador. | Upload .docx/.pdf/.md, nome da seção, salvar data/hora, validação de tamanho, campos Selecionar Seção/Arquivo, botão “Enviar”, confirmação. |
| US02 | Correção e Feedback | Professor envia feedback sem alterar o arquivo. | Visualização do arquivo, campo de comentário, botão “Enviar Feedback”, feedback visível ao aluno, registro de data/autor. |
| US03 | Acesso a Versões Anteriores | Visualizar histórico de versões. | Nova versão a cada upload, número da versão, download, botão/aba “Histórico de Versões”. |
| US04 | Notificações | Alertar aluno e professor sobre novas interações. | Notificações no sistema/email, textos padrão, geradas automaticamente, painel de notificações. |
| US05 | Status e Progresso | Mostrar status das seções. | Status: Pendente/Em Revisão/Com Feedback/Aceito, cores e ícones, apenas professor altera, confirmação e atualização em tempo real. |
| US06 | Banco de Dados | Armazenar seções, versões e feedbacks. | Tabelas: Alunos, Seções, Versões, Feedbacks, Notificações, histórico completo, filtros, nenhuma versão apagada. |
| US07 | TG Consolidado | Gerar TG final em Markdown. | Juntar seções aceitas, converter para Markdown, gerar arquivo .md único, botão “Gerar TG Consolidado”, mensagem de sucesso e download. |

---

## Definition of Done (DoD)

| Categoria | Critérios | Status |
|-----------|----------|--------|
| 💻 Código & Desenvolvimento | Funcionalidades implementadas, regras de negócio respeitadas, telas navegáveis e integradas, banco de dados funcional, código revisado, integração sem regressões. | ⬜ |
| 🧪 Testes & Qualidade | Testes manuais/automatizados realizados, critérios de aceitação validados, sem erros críticos, performance adequada. | ⬜ |
| 🎨 Usabilidade & Interface | Layout consistente, intuitivo e funcional, botões e feedbacks corretos, protótipo respeitado, ícones e cores aplicados. | ⬜ |
| 📚 Documentação & Entregáveis | README/documentação atualizados, estrutura de banco registrada, US marcadas como Done com evidências, sistema pronto para apresentação. | ⬜ |

---

## 📁 Documentação do Projeto
Toda documentação disponível na pasta [`documentacao`](./documentação).  

Conteúdo:  
- Definition of Ready (DoR)  
- Definition of Done (DoD)  
- Estratégia de Branch  
- Padrão de Commits  
- Modelagem do Banco de Dados  

---

## 👥 Equipe

| Função | Nome | GitHub |
|--------|------|--------|
| Scrum Master | Leonardo Amon Sumiyoshi Hashimoto | [![GitHub](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/Leonardo1022) |
| Product Owner | Maria Eduarda Teixeira Miller de Oliveira | [![GitHub](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/maria-oliveira) |
| Team Member | Gabriel Valente Belarmino | [![GitHub](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/gabrielvalentesjc) |
| Team Member | Guilherme Almeida de Arruda | [![GitHub](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/guiggaaz) |
| Team Member | Natália Pereira da Silva | [![GitHub](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/nataliapersis) |
| Team Member | Niuan Spolidorio da Rocha Souza | [![GitHub](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/NiuanSouza) |
| Team Member | Vitor Samuel Ribeiro de Souza | [![GitHub](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/VitorRibeiro09) |




