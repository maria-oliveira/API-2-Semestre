# ✅ Definition of Done – Sprint 2 (US01 a US07)

## 1. Escopo da Sprint
Esta sprint cobre as funcionalidades principais do sistema **TG Control**, incluindo:
- Envio de seções do TG pelo aluno.
- Correção e feedback pelo professor.
- Controle de versões anteriores.
- Sistema de notificações.
- Exibição de status e progresso.
- Estrutura inicial do banco de dados.
- Geração automática do TG consolidado em formato Markdown.

---

## 2. Critérios de Conclusão da Sprint

### 2.1 💻 Código e Desenvolvimento
- O código de todas as funcionalidades foi implementado **seguindo boas práticas** e **padrões da equipe**.  
- Todas as **regras de negócio descritas no DoR** das US01–US07 foram respeitadas.  
- As telas principais (envio, feedback, histórico, status e geração de TG) estão **navegáveis e integradas**.  
- O **banco de dados foi criado e está funcional**, armazenando corretamente alunos, seções, versões, feedbacks e notificações.  
- O código foi **revisado e aprovado** em *code review*.  
- Integração das features concluída sem causar **regressões** nas partes já implementadas.

---

### 2.2 🧪 Testes e Qualidade
- Testes manuais foram executados para **todos os fluxos principais** (envio, feedback, geração, notificações).  
- Testes unitários básicos foram criados para as funções de controle e persistência de dados.  
- Todos os **critérios de aceitação das US01–US07** foram validados com sucesso.  
- Nenhum **erro crítico ou de bloqueio** permanece aberto.  
- A performance e estabilidade estão adequadas para uso interno e demonstração.  

---

### 2.3 🎨 Usabilidade e Interface
- As telas possuem layout consistente, intuitivo e funcional.  
- Botões, mensagens de erro e feedback ao usuário estão implementados corretamente.  
- A interface reflete o **protótipo definido** na documentação.  
- Ícones e cores de status estão aplicados conforme padrão visual (ex.: Pendente, Em Revisão, Aceito).   


---

# ✅ Definition of Done (DoD) – US08 e US09

## 1. Escopo da Sprint
Esta sprint cobre as novas funcionalidades do sistema **TG Control**, incluindo:  
- Agendamento de defesas de TCC pelos professores.  
- Revisão e aprovação de cadastros de alunos e professores.  

---

## 2. Critérios de Conclusão da Sprint

### 2.1 💻 Código e Desenvolvimento
- O código das funcionalidades de agendamento de defesas e aprovação de cadastros foi implementado conforme as regras de negócio descritas no DoR das US08 e US09.  
- O módulo de agendamento permite selecionar aluno, data, hora, local e banca, com verificação de conflitos de horário e gravação correta no banco de dados.  
- A funcionalidade de revisão de cadastros permite listar, aprovar e rejeitar usuários, registrando data, hora e responsável pela ação.  
- O sistema envia notificações automáticas para alunos, professores e banca conforme definido.  
- O código foi revisado e aprovado em code review sem falhas críticas.  
- As novas features foram integradas ao sistema principal sem quebrar funcionalidades anteriores.  
- O banco de dados foi atualizado para incluir as novas tabelas e relações necessárias (Defesas, Aprovações de Usuários, etc.).  

---

### 2.2 🧪 Testes e Qualidade
- Testes manuais confirmam o funcionamento completo do agendamento de defesas, incluindo criação, edição, cancelamento e notificação.  
- Testes manuais e unitários garantem a aprovação e rejeição de cadastros, com bloqueio correto de acesso para usuários não aprovados.  
- Todos os critérios de aceitação das US08 e US09 foram validados com sucesso.  
- Nenhum erro crítico permanece aberto nas novas implementações.  
- O sistema mantém estabilidade e performance adequadas após a integração das novas features.  
- Logs de auditoria são gerados corretamente para ações de aprovação, rejeição e agendamento.  

---

### 2.3 🎨 Usabilidade e Interface
- As telas de Agendamento de Defesas e Revisão de Cadastros seguem o mesmo padrão visual das demais partes do sistema.  
- Campos obrigatórios (aluno, data, hora, local, banca, status de aprovação) possuem validação visual e mensagens de erro adequadas.  
- O layout das telas é intuitivo, consistente e responsivo, garantindo boa experiência tanto para professores quanto alunos.  
- Ícones, cores e mensagens refletem corretamente os status de ações:  
  - Agendado, Editado, Cancelado (para defesas).  
  - Pendente, Aprovado, Rejeitado (para cadastros).  
- Mensagens de confirmação e sucesso aparecem após cada ação concluída (ex.: “Defesa agendada com sucesso”, “Cadastro aprovado com sucesso”).  



