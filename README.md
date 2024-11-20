# Ceep - Gerenciador de Tarefas

Este é um gerenciador de tarefas web chamado **Ceep**, desenvolvido durante um curso de **"JS na Web"**. Ele permite criar, listar, concluir e deletar tarefas de forma dinâmica, armazenando os dados no navegador utilizando o `localStorage`.

---

## 🛠️ Funcionalidades

- **Adicionar Tarefas**:
  - Insira o nome e a data da tarefa para adicionar à lista.
- **Listar Tarefas**:
  - Exibe as tarefas organizadas por data.
  - Exibe o horário e status (pendente ou concluído) de cada tarefa.
- **Concluir Tarefas**:
  - Marca uma tarefa como concluída.
- **Deletar Tarefas**:
  - Remove tarefas da lista.
- **Persistência de Dados**:
  - Utiliza `localStorage` para salvar as tarefas no navegador.

---

## 🚀 Como Executar o Projeto

### Pré-requisitos

- Navegador moderno (Google Chrome, Mozilla Firefox, etc.).

### Passos

1. Clone o repositório:
   ```bash
   git clone <https://github.com/gianmalfate/taskmanager_ceep>
   cd ceep
2. Abra o arquivo `index.html` no navegador.

## 🔑 Detalhes de Implementação

### 1. Organização por Data

As tarefas são agrupadas por data utilizando a biblioteca `moment.js` para manipulação e formatação de datas.

### 2. Componentização

Cada funcionalidade está implementada em arquivos JavaScript separados, promovendo organização e reutilização de código.

### 3. Persistência com `localStorage`

Todas as tarefas são salvas no `localStorage`, permitindo que os dados permaneçam após recarregar a página.

## ✨ Demonstração

1.  **Adicionar Tarefa**:
    -   Preencha o nome e a data, clique em "Novo Item".
2.  **Concluir Tarefa**:
    -   Clique no botão "Concluir" para marcar a tarefa como feita.
3.  **Deletar Tarefa**:
    -   Clique em "Deletar" para remover a tarefa da lista.
4.  **Listagem**:
    -   As tarefas são exibidas organizadas por data.

## 🧑‍💻 Contato

Dúvidas ou sugestões? Entre em contato pelo email: **seuemail@exemplo.com**.
