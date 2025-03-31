# 📌 Primeiro Site com React

Este é um projeto simples desenvolvido em **React**, que inclui funcionalidades como cadastro de tarefas, personalização de cor de fundo e alteração de nome de usuário.

---

## 🛠 Tecnologias Utilizadas  
- **React.js**  
- **React Hooks (useState e useEffect)**  
- **localStorage** para persistência de dados  

---

## 📂 Estrutura do Projeto  

```
/primeiro-site-master
│── /public
│   ├── favicon.ico
│   ├── index.html
│   ├── logo192.png
│   ├── logo512.png
│   ├── manifest.json
│   ├── robots.txt
│── /src
│   ├── /Componentes
│   │   ├── Cadastro.js
│   │   ├── exemplo.js
│   │   ├── Nome.js
│   ├── App.js
│   ├── index.js
│── .gitignore
│── /assets
│── package-lock.json
│── package.json
│── README.md
│── Projeto-funcionando.png
```

---

## 🚀 Funcionalidades  

### 📋 Cadastro de Tarefas  
- Permite adicionar tarefas a uma lista.  
- As tarefas são salvas no **localStorage** e carregadas automaticamente ao abrir a aplicação.  

### 🎨 Personalização de Cor de Fundo  
- O usuário pode selecionar uma cor de fundo para a página.  
- A escolha é armazenada no **localStorage** para ser mantida ao recarregar a página.  

### 👤 Nome do Usuário  
- O sistema solicita e exibe o nome do usuário.  
- Caso o nome já tenha sido salvo, ele será carregado automaticamente.  

### 🔄 Alteração de Nome  
- No **App.js**, há um botão que altera dinamicamente o nome exibido.  

---

## 🏁 Como Executar o Projeto  

1. Clone este repositório:  
   ```bash
   https://github.com/eduardocintr/marcio-projeto.git
   ```

2. Acesse a pasta do projeto:  
   ```bash
   cd primeiro-site-master
   ```

3. Instale as dependências:  
   ```bash
   npm install
   ```

4. Execute o projeto:  
   ```bash
   npm start
   ```

5. Abra no navegador:  
   O projeto será executado em: **http://localhost:3000**  

---

## 🖼️ Demonstração  
![Projeto em Execução](./mnt/data/Projeto-funcionando.png)

---

📌 *Desenvolvido com React.js* 🚀
