# Formulário de Contato com Envio de E-mail

![Tecnologia](https://img.shields.io/badge/Tecnologia-Node.js-green)
![Linguagens](https://img.shields.io/badge/Linguagens-HTML%2FCSS%2FJS-blue)

Este é um projeto de um **formulário de contato** que permite aos usuários enviar mensagens diretamente de uma página web. O backend, construído com **Node.js**, processa e envia os e-mails usando o serviço **Nodemailer**.

### **Recursos e Tecnologias Utilizadas**

O projeto utiliza um conjunto de tecnologias modernas para garantir uma solução robusta e funcional.

**Frontend:**
- **HTML5:** Estrutura da página.
- **CSS3:** Estilização e design responsivo.
- **JavaScript (ES6+):** Lógica de interação do formulário e requisição `fetch` para o backend.

**Backend:**
- **Node.js:** Ambiente de execução do backend.
- **Express.js:** Framework para criação da API.
- **CORS:** Para gerenciar o acesso de domínios externos.
- **Nodemailer:** Biblioteca para envio de e-mails.
- **dotenv:** Para gerenciar variáveis de ambiente de forma segura.

### **Estrutura do Projeto**

O projeto está dividido em duas partes principais: `frontend` e `backend`.

Cópia de Ajudante de programação
Gem personalizado
Olá! Fico feliz em te ajudar a criar um README para o seu projeto. Um bom README é essencial para que outras pessoas entendam o que o seu código faz, como ele funciona e como podem utilizá-lo.

Analisando o repositório, vejo que é um projeto de um formulário de contato com envio de e-mail, utilizando HTML, CSS e JavaScript no frontend, e Node.js com Nodemailer no backend. O objetivo do README é documentar isso de forma clara e profissional.

Vamos criar um README completo, com todas as seções importantes.

Estrutura da Solução
O README que vamos criar terá as seguintes seções:

Título e Insígnia (Badge): Um título claro para o projeto e uma insígnia que mostre a tecnologia principal, como a linguagem utilizada.

Descrição: Uma breve descrição do projeto, explicando sua funcionalidade principal.

Recursos e Tecnologias: Uma lista das linguagens, frameworks e bibliotecas usadas.

Estrutura do Projeto: Uma visão geral de como os arquivos e pastas estão organizados no repositório.

Como Usar/Instalar: Instruções passo a passo para configurar e rodar o projeto localmente.

Configuração do Backend (.env): Detalhes importantes sobre as variáveis de ambiente necessárias para o backend.

Autor: As informações de contato do autor do projeto.

Conteúdo do README
Aqui está o código completo para o seu arquivo README.md. Você pode copiar e colar este conteúdo diretamente no seu repositório.

Markdown

# Formulário de Contato com Envio de E-mail

![Tecnologia](https://img.shields.io/badge/Tecnologia-Node.js-green)
![Linguagens](https://img.shields.io/badge/Linguagens-HTML%2FCSS%2FJS-blue)

Este é um projeto de um **formulário de contato** que permite aos usuários enviar mensagens diretamente de uma página web. O backend, construído com **Node.js**, processa e envia os e-mails usando o serviço **Nodemailer**.

### **Recursos e Tecnologias Utilizadas**

O projeto utiliza um conjunto de tecnologias modernas para garantir uma solução robusta e funcional.

**Frontend:**
- **HTML5:** Estrutura da página.
- **CSS3:** Estilização e design responsivo.
- **JavaScript (ES6+):** Lógica de interação do formulário e requisição `fetch` para o backend.

**Backend:**
- **Node.js:** Ambiente de execução do backend.
- **Express.js:** Framework para criação da API.
- **CORS:** Para gerenciar o acesso de domínios externos.
- **Nodemailer:** Biblioteca para envio de e-mails.
- **dotenv:** Para gerenciar variáveis de ambiente de forma segura.

### **Estrutura do Projeto**

O projeto está dividido em duas partes principais: `frontend` e `backend`.

/Formulario_contato_envio_email
|-- frontend/
|   |-- portfolio.html
|   |-- styles.css
|   |-- script.js
|
|-- backend/
|   |-- server.js
|   |-- .env
|   |-- package.json
|
|-- .gitignore
|-- README.md

### **Como Usar**

Siga as instruções abaixo para clonar o repositório e configurar o projeto em sua máquina local.

Configurar o Backend

Entre na pasta do backend:

Bash

cd backend
Instale as dependências:

Bash

npm install
Crie um arquivo .env com as seguintes variáveis de ambiente. Você precisará de uma senha de aplicativo do Gmail para usar o Nodemailer.

Fragmento do código

EMAIL_USER=seu_email_aqui@gmail.com
EMAIL_PASS=sua_senha_de_aplicativo_aqui
EMAIL_HOST=smtp.gmail.com
EMAIL_PORT=465
TARGET_EMAIL=email_destino_aqui@gmail.com
PORT=5000
Inicie o servidor:

Bash

node server.js
O servidor será executado na porta 5000.

3. Configurar o Frontend

Volte para a raiz do projeto e abra o arquivo portfolio.html no seu navegador.

No arquivo script.js, atualize a URL da requisição fetch para http://localhost:5000/send-email.

Observação: Atualmente, a URL está configurada para http://localhost:5000/send-email, o que é ideal para o ambiente de desenvolvimento.

Autor
John Victor Parreiras

 - [GitHub](https://www.google.com/search?q=https://github.com/ParreirasJuniorWeb)

 - [LinkedIn](https://www.google.com/search?q=https://www.linkedin.com/in/john-victor-parreiras-desenvolvedor-fullstack/)

 - [Portfólio](https://www.google.com/search?q=https://parreirasjuniorweb.github.io/MeusTrabalhosParaPortfolio/)

**1. Clonar o Repositório**

Abra o terminal e execute o seguinte comando:

```bash
git clone [https://github.com/ParreirasJuniorWeb/Formulario_contato_envio_email.git](https://github.com/ParreirasJuniorWeb/Formulario_contato_envio_email.git)
cd Formulario_contato_envio_email
