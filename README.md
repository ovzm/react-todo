# 📝 React ToDo

Aplicação de **lista de tarefas (ToDo List)** desenvolvida em **React** que permite criar, visualizar, concluir e remover tarefas.  
A aplicação consome uma **API local** para persistência dos dados.

---

# 🚀 Funcionalidades

- ➕ Criar novas tarefas
- 📋 Listar todas as tarefas
- ✅ Marcar tarefas como concluídas
- ❌ Remover tarefas
- ⏱ Adicionar tempo estimado de duração para cada tarefa
- 🔄 Integração com API usando **Fetch API**

---

# 🛠 Tecnologias Utilizadas

- React
- JavaScript (ES6+)
- React Hooks
  - useState
  - useEffect
- Fetch API
- React Icons
- CSS

---

# 📂 Estrutura do Projeto

```
src
 ├── App.js
 ├── App.css
 └── main.jsx
```

---

# 🔌 API

A aplicação utiliza uma API local:

```
http://localhost:5000
```

### Endpoints utilizados

| Método | Endpoint | Descrição |
|------|------|------|
| GET | /todos | Lista todas as tarefas |
| POST | /todos | Cria uma nova tarefa |
| PUT | /todos/:id | Atualiza uma tarefa |
| DELETE | /todos/:id | Remove uma tarefa |

---

# 📦 Instalação

Clone o repositório:

```bash
git clone https://github.com/seu-usuario/react-todo.git
```

Entre na pasta do projeto:

```bash
cd react-todo
```

Instale as dependências:

```bash
npm install
```

---

# ▶️ Executando o Projeto

Inicie o projeto:

```bash
npm run dev
```

O projeto estará disponível em:

```
http://localhost:5173
```

---

# 📡 Executando a API

Para simular a API, você pode utilizar **json-server**.

Instale globalmente:

```bash
npm install -g json-server
```

Crie um arquivo `db.json`:

```json
{
  "todos": []
}
```

Execute a API:

```bash
json-server --watch db.json --port 5000
```

---

# 🖥 Interface

A aplicação possui:

- Formulário para criação de tarefas
- Lista dinâmica de tarefas
- Botões de ação para **concluir** e **remover**

---

# 📚 Conceitos aplicados

- Gerenciamento de estado com React Hooks
- Comunicação com API REST
- Manipulação de listas em React
- Atualização imutável de estado
- Componentização básica

---

# 📄 Licença

Este projeto foi desenvolvido para fins de estudo.
