# 📘 Manual do Usuário – TG CONTROL

## 🎯 Sobre o Sistema

O TG CONTROL é uma plataforma desenvolvida para centralizar e organizar todo o processo de envio, correção e acompanhamento dos Trabalhos de Graduação da modalidade Portfólio.

### Objetivos do Sistema

- ✅ Facilitar o envio de seções do TG pelos alunos
- ✅ Agilizar o processo de correção e feedback dos orientadores
- ✅ Manter histórico completo de versões e correções
- ✅ Notificar automaticamente alunos e professores
- ✅ Gerar automaticamente o TG final em formato Markdown (MD)
- ✅ Permitir o acompanhamento do progresso pela coordenação

---

## 🖥️ Como Usar

Para garantir o sucesso na utilização do sistema, aqui está uma lista das tecnologias e ferramentas necessárias para os próximos passos:

### 🔧 Tecnologias Necessárias

- **Git** - Sistema de controle de versão
- **Java 18+** - Linguagem de programação do backend
- **Maven** - Gerenciador de dependências
- **IntelliJ IDEA** - IDE recomendada para desenvolvimento
- **MySQL Workbench** - Gerenciador do banco de dados

---

## 🚀 Como Executar o Projeto

### 1. Clonar o Repositório

Abra o terminal e execute o seguinte comando:

```bash
git clone https://github.com/Fatec-TechForce/API-2-Semestre.git
cd API-2-Semestre
```

### 2. Configurar o Banco de Dados

#### 2.1. Abrir o MySQL Workbench

1. Abra o MySQL Workbench
2. Conecte-se ao seu servidor MySQL local
3. Crie um novo banco de dados:

```sql
CREATE DATABASE tg_management;
USE tg_management;
```

#### 2.2. Executar o Script de Criação de Tabelas

1. Localize o arquivo de script SQL na pasta `database/` do projeto
2. Execute o script no MySQL Workbench para criar as tabelas necessárias

#### 2.3. Configurar a Conexão no Projeto

1. Navegue até o arquivo `application.properties` em `src/main/resources/`
2. Configure as credenciais do banco de dados:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/tg_management
spring.datasource.username=seu_usuario
spring.datasource.password=sua_senha
spring.jpa.hibernate.ddl-auto=update
```

### 3. Abrir o Projeto no IntelliJ IDEA

1. Abra o IntelliJ IDEA
2. Vá em **File > Open...** e selecione a pasta do projeto clonado
3. Certifique-se de que o projeto está configurado com Java 18+:
   - Vá em **File > Project Structure**
   - Verifique o **Project SDK** e o **Language Level**
4. Aguarde o IntelliJ indexar o projeto e baixar as dependências do Maven

### 4. Executar o Backend

#### 4.1. Localizar a Classe Principal

Localize a classe principal `Application.java` em:

```
src/main/java/com/techforce/tgmanagement/Application.java
```

#### 4.2. Executar a Aplicação

1. Clique com o botão direito em `Application.java`
2. Selecione **Run 'Application.main()'**
3. Aguarde a aplicação iniciar

#### 4.3. Verificar se está Rodando

Verifique no console do IntelliJ se aparece uma mensagem similar a:

```
Started Application in X.XXX seconds
Server is running on port 8080
```

### 5. Acessar o Sistema

#### 5.1. Frontend Web

Abra o navegador e acesse:

```
http://localhost:8080
```

#### 5.2. Testar a API (Opcional)

Para desenvolvedores, teste os endpoints da API usando ferramentas como:

- Postman
- Insomnia
- cURL

Exemplo de endpoint de teste:

```
GET http://localhost:8080/api/health
```

---

## 👤 Perfis de Usuário

### 🎓 Aluno

**Funcionalidades disponíveis:**

- Enviar seções do TG para o orientador
- Visualizar feedback e correções
- Acompanhar o status de cada seção (Pendente, Em Revisão, Aceita)
- Receber notificações de novos feedbacks
- Acessar histórico de versões enviadas
- Gerar TG consolidado em formato Markdown

### 👨🏫 Professor Orientador

**Funcionalidades disponíveis:**

- Receber seções dos alunos orientados
- Realizar correções e enviar feedback
- Atualizar o status das seções
- Acessar versões anteriores dos trabalhos
- Receber notificações de novos envios
- Visualizar dashboard com progresso dos orientandos

### 👔 Professor de TG

**Funcionalidades disponíveis:**

- Visualizar panorama geral de todos os TGs
- Acompanhar progresso dos alunos e orientadores
- Aprovar cadastros de novos usuários
- Agendar defesas dos trabalhos
- Gerar relatórios gerenciais

---

## 📊 Fluxo de Trabalho

### 1️⃣ Envio de Seção (Aluno)

1. Acesse o sistema com suas credenciais
2. Navegue até "Minhas Seções"
3. Clique em "Nova Seção"
4. Preencha os campos obrigatórios:
   - Título da seção
   - Conteúdo
   - Anexos (se necessário)
5. Clique em "Enviar para Orientador"
6. Aguarde a notificação de feedback

### 2️⃣ Correção e Feedback (Professor)

1. Acesse "Seções Pendentes"
2. Selecione a seção do aluno
3. Leia o conteúdo enviado
4. Adicione seus comentários e correções
5. Atualize o status:
   - **"Em Revisão"** - Necessita correções
   - **"Aceita"** - Aprovada
6. Clique em "Enviar Feedback"
7. O aluno receberá notificação automaticamente

### 3️⃣ Acompanhamento de Progresso

#### Para Alunos

Acesse o Dashboard para ver:
- Seções pendentes
- Seções em revisão
- Seções aceitas
- Próximos prazos

#### Para Professores Orientadores

Acesse "Meus Orientandos" para visualizar:
- Progresso individual de cada aluno
- Seções aguardando revisão
- Histórico de feedbacks

#### Para Coordenadores

Acesse "Painel Gerencial" para:
- Visualizar estatísticas gerais
- Identificar TGs em atraso
- Acompanhar distribuição de orientandos

### 4️⃣ Geração do TG Final (Aluno)

1. Após todas as seções serem aprovadas
2. Acesse "Gerar TG Final"
3. O sistema consolidará automaticamente todas as seções
4. Faça o download do arquivo `.md`
5. Revise o documento gerado
6. Submeta para a defesa final

---

## 🔔 Sistema de Notificações

### Notificações para Alunos

- ✉️ Novo feedback do orientador
- ✉️ Seção aprovada
- ✉️ Seção necessita revisão
- ✉️ Prazo próximo do vencimento
- ✉️ Defesa agendada

### Notificações para Professores

- ✉️ Nova seção enviada pelo aluno
- ✉️ Nova versão de seção enviada
- ✉️ Lembrete de seções pendentes de revisão

### Notificações para Coordenadores

- ✉️ Novo usuário aguardando aprovação
- ✉️ TG completo aguardando agendamento de defesa
- ✉️ Relatório semanal de progresso

---

## 🎯 Dicas para Melhor Experiência

### Para Alunos

- ✅ Envie suas seções com antecedência
- ✅ Mantenha as notificações ativadas
- ✅ Salve rascunhos frequentemente
- ✅ Revise o feedback antes de enviar nova versão

### Para Professores

- ✅ Estabeleça prazos claros de revisão
- ✅ Seja específico nos feedbacks
- ✅ Use o sistema de status para organizar seu trabalho
- ✅ Verifique notificações diariamente

### Para Coordenadores

- ✅ Aprove cadastros rapidamente
- ✅ Monitore o painel regularmente
- ✅ Agende defesas com antecedência
- ✅ Gere relatórios periodicamente

---

## 📝 Informações do Projeto

**Versão do Manual:** 1.0  
**Última Atualização:** Novembro 2025  
**Desenvolvido por:** TechForce

---

## 📄 Licença

Este projeto está sob licença da Fatec TechForce.

---

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests.

---

## 📧 Contato

Para mais informações, entre em contato com a equipe TechForce.
