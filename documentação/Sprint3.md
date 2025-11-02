## Sprint 3

# 🗂 Backlog
| Rank | Prioridade | User Story | Estimativa | Sprint |
| --- | --- | --- | --- | --- |
| 8| **Baixa** | Como professor de TG, quero agendar as defesas dos alunos que concluíram o Trabalho de Graduação, para organizar as apresentações e facilitar o acompanhamento das etapas finais do processo. | 5 | 3 |
| 9| **Baixa** |Como professor de TG,quero revisar e aprovar os cadastros realizados por alunos e outros professores no sistema,para garantir que apenas usuários autorizados tenham acesso e evitar cadastros indevidos. | 3 | 3 |

# 📝 Definition of Ready (DoR)

### US08 – Agendamento de Defesas

**Objetivo:**  
Como professor de TG, quero agendar as defesas dos alunos que concluíram o Trabalho de Graduação, para organizar as apresentações e facilitar o acompanhamento das etapas finais do processo.

**Requisitos Específicos:**
- O sistema deve permitir ao professor criar agendamentos de defesa apenas para alunos com o TG no status **“Aceito”**.  
- O professor deve informar obrigatoriamente: **aluno, data, hora, local** e **banca avaliadora**.  
- O sistema deve validar **conflitos de data e horário**, impedindo o agendamento de duas defesas no mesmo local e horário.  
- O agendamento deve registrar automaticamente **data e hora de criação**.  
- Após o agendamento, o sistema deve enviar **notificações** ao aluno e aos membros da banca, informando data, hora e local da defesa.  
- O professor deve poder **editar ou cancelar** o agendamento antes da data da defesa.  
- O aluno deve visualizar em sua área do sistema os detalhes da defesa (data, hora, local e banca).  
- O sistema deve exibir todos os agendamentos em uma **tela de calendário** ou **lista de defesas**, com filtros por aluno, data ou banca.  

---

### US09 – Revisão e Aprovação de Cadastros

**Objetivo:**  
Como professor de TG, quero revisar e aprovar os cadastros realizados por alunos e outros professores no sistema, para garantir que apenas usuários autorizados tenham acesso e evitar cadastros indevidos.

**Requisitos Específicos:**
- O sistema deve listar todos os **cadastros pendentes de aprovação** (alunos e professores).  
- Cada cadastro deve exibir: **nome completo, e-mail institucional, tipo de usuário (aluno ou professor)** e **data do cadastro**.  
- O professor deve ter as opções **“Aprovar”** ou **“Rejeitar”** o cadastro.  
- Ao aprovar, o sistema deve liberar o **acesso ao sistema** para o usuário.  
- Ao rejeitar, o sistema deve permitir incluir um **motivo opcional** e registrar a decisão.  
- O sistema deve registrar **data, hora e autor da ação** (quem aprovou/rejeitou).  
- O usuário deve receber uma **notificação por e-mail** informando o resultado da revisão.  
- Cadastros rejeitados devem permanecer **armazenados para auditoria**, mas sem permissão de acesso.  
- A tela deve permitir **filtrar** e **pesquisar** cadastros por nome, tipo de usuário, status e data.  

---
# 📈 Metas para Sprint

---
# ✅ Definition of Done (DoD)

---

# 📊 Burndown da Sprint
