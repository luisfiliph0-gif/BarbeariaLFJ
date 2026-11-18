# 💈 Sistema de Gestão e Agendamentos — Barbearia LFJ

> Projeto prático desenvolvido para a disciplina de **Linguagem de Programação** (Prof. Allanyo Santos), implementando um sistema CRUD completo em Python integrado a um banco de dados relacional MySQL.

---

## 1. Descrição e Objetivo do Sistema
# BarbeariaLFJ
Desenvolver um sistema computacional utilizando a linguagem Python, CRUD, aplicando os conceitos de programação estudados durante a disciplina. O sistema deverá implementar as quatro operações fundamentais de um CRUD (Create, Read, Update e Delete), permitindo cadastrar, consultar, atualizar e excluir informações.

---

## 2. Problema que o Sistema Busca Resolver
O controle manual de horários em agendas de papel ou mensagens soltas frequentemente gera conflitos de agendamento, esquecimento de atendimentos, dificuldade para localizar o histórico de serviços de um cliente e falta de clareza sobre os valores cobrados. O sistema resolve esse problema centralizando todos os agendamentos em um banco de dados estruturado, garantindo consulta rápida, atualização ágil de status (Agendado, Concluído, Cancelado) e integridade das informações.

---

## 3. Integrantes da Equipe
* **[Nome Completo do Integrante 1]** — GitHub: `[@joasbispo-ai](https://github.com/joasbispo-ai)`
* **[Nome Completo do Integrante 2 (caso seja em dupla)]** — GitHub: `[@luisfiliph0-gif](https://github.com/luisfiliph0-gif)`

---

## 4. Tecnologias Utilizadas
* **Linguagem:** Python 3.x
* **Banco de Dados:** MySQL Server & MySQL Workbench
* **Driver de Conexão:** `mysql-connector-python`
* **Versionamento:** Git e GitHub

---

## 5. Funcionalidades Implementadas
* **RF01 — Cadastro (Create):** Registro de novos agendamentos contendo nome do cliente, telefone/WhatsApp, tipo de serviço, barbeiro responsável, data/horário e valor.
* **RF02 — Consulta (Read):** Visualização da agenda completa ordenada por ID ou busca individual filtrada por ID ou nome do cliente.
* **RF03 — Atualização (Update):** Edição pontual de agendamentos existentes (alteração de data/horário, serviço/valor ou status do atendimento).
* **RF04 — Exclusão (Delete):** Remoção de registros pelo ID com exibição prévia dos dados e solicitação de confirmação (`S/N`) antes de apagar definitivamente.
* **RF05 — Menu Interativo:** Navegação contínua via terminal com tratamento para opções inválidas.
* **RF06 — Validação de Dados:** Bloqueio de campos vazios, validação de valores monetários positivos e verificação de IDs numéricos.
* **RF07 — Persistência de Dados:** Armazenamento permanente em banco de dados MySQL.

---

## 6. Instruções para Instalação e Execução

### Pré-requisitos
* [Python 3](https://www.python.org/downloads/) instalado na máquina.
* [MySQL Server e MySQL Workbench](https://dev.mysql.com/downloads/workbench/) instalados e em execução.

### Passo 1: Clonar o repositório
```bash
git clone [https://github.com/](https://github.com/)[joasbispo-ai]/barbearia-lfj-crud.git
cd barbearia-lfj-crud
