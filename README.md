📋 Formulário Multi-Step com React

Este projeto é um formulário multi-etapas (Multi-Step Form) desenvolvido com React.
O objetivo da aplicação é coletar a avaliação de um usuário sobre um produto através de um fluxo dividido em etapas, melhorando a experiência do usuário durante o preenchimento.

O formulário possui três etapas principais:

1. Identificação do usuário
2. Avaliação do produto
3. Confirmação e envio da avaliação

Cada etapa é renderizada dinamicamente através de componentes React e controlada por um hook personalizado que gerencia a navegação 
entre os passos.

---

# 🚀 Tecnologias utilizadas

Este projeto foi desenvolvido utilizando as seguintes tecnologias:

* React
* JavaScript (ES6+)
* CSS
* React Icons

---


📂 Estrutura do projeto

```
src
 ├── components
 │   ├── UserForm.jsx
 │   ├── ReviewForm.jsx
 │   ├── Thanks.jsx
 │   └── Steps.jsx
 │
 ├── hooks
 │   └── useForm.js
 │
 ├── App.jsx
 ├── App.css
 └── main.jsx
```

---- Components

**UserForm**
Responsável por coletar os dados do usuário:

* Nome
* Email

**ReviewForm**
Responsável pela avaliação do produto e comentários.

**Thanks**
Tela final que apresenta um **resumo da avaliação** antes do envio.

**Steps**
Componente visual que mostra o **progresso das etapas do formulário**.

---

▶️ Como executar o projeto

Clone o repositório:

```bash
git clone https://github.com/seu-usuario/seu-repositorio
```

Entre na pasta do projeto:

```bash
cd nome-do-projeto
```

Instale as dependências:

```bash
npm install
```

Execute o projeto:

```bash
npm run dev
```

O projeto será executado em:

```
http://localhost:5173
```

---

 📸 Funcionalidades

✔ Formulário dividido em múltiplas etapas
✔ Navegação entre passos
✔ Visualização do progresso do formulário
✔ Resumo final da avaliação
✔ Interface simples e intuitiva

---

 📌 Objetivo do projeto

Este projeto foi desenvolvido com o objetivo de **praticar conceitos fundamentais do React**, principalmente:

* organização de componentes
* gerenciamento de estado
* criação de hooks personalizados
* construção de interfaces interativas

---

# 👨‍💻 Autor

**Gabriel Figueiredo**

🔗 GitHub
[https://github.com/Gabriel-Figueiredo06](https://github.com/Gabriel-Figueiredo06)

🔗 Portfólio
[https://gabriel-figueiredo06.github.io/Portfolio-Gabriel-Figueiredo/](https://gabriel-figueiredo06.github.io/Portfolio-Gabriel-Figueiredo/)


