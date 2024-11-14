# ATIVIDADE GIT E NODE.JS

## Exercício: Configuração do Projeto com Node.js e Git

1. **Criação da Pasta**
   - Primeiramente, foi criada uma pasta chamada **git-test** usando o comando:
     ```bash
     mkdir git-test
     ```
   
2. **Instalação do Node.js e npm**
   - Após a instalação do **Node.js** e **npm**, configuramos o projeto com o comando:
     ```bash
     npm init
     ```
   - Esse comando gerou o arquivo **package.json**, que contém as configurações do projeto, como nome, versão e dependências.

3. **Instalação do Lite-Server**
   - Instalamos o **lite-server** com o comando:
     ```bash
     npm install lite-server --save-dev
     ```
   - O lite-server é uma ferramenta que facilita a execução de um servidor web de desenvolvimento.

4. **Configuração do package.json**
   - Editamos o arquivo **package.json** para incluir as instruções recomendadas na aula 3, garantindo que o projeto esteja configurado para rodar com o lite-server.

5. **Criação do Arquivo index.html**
   - Criamos o arquivo **index.html** com o código HTML básico. 

6. **Execução do Servidor**
   - Executamos o servidor de desenvolvimento com o comando:
     ```bash
     npm start
     ```

7. **Criação do Arquivo .gitignore**
   - Criamos o arquivo **.gitignore** e adicionamos o diretório **node_modules** para evitar que as dependências instaladas pelo npm sejam enviadas ao GitHub.

8. **Envio dos Arquivos para o GitHub**
   - Por fim, fizemos o upload dos arquivos para o repositório GitHub, seguindo os comandos de commit e push.

---


