# Brazilian Tales (Projeto de Teste)

Este é um guia para configurar e rodar o projeto em um ambiente de desenvolvimento Windows.

## Como Rodar o Projeto no Windows

Siga os passos abaixo para executar a aplicação localmente.

### Pré-requisitos

-   **Node.js**: Você precisa ter o Node.js instalado. Ele já vem com o `npm` (gerenciador de pacotes). Você pode baixá-lo em nodejs.org.

### Passos para Execução

1.  **Abra o Terminal:**
    Abra seu terminal de preferência (PowerShell, CMD, ou o terminal do VS Code).

2.  **Navegue até a Pasta da Aplicação:**
    O código-fonte deste projeto está dentro da pasta `my-app`. É crucial que você execute os comandos de dentro dela.
    ```sh
    cd my-app
    ```

3.  **Instale as Dependências:**
    Este comando irá baixar todas as bibliotecas necessárias para o projeto, que estão listadas no arquivo `package.json`.
    ```sh
    npm install
    ```

4.  **Inicie o Servidor de Desenvolvimento:**
    Este comando inicia a aplicação em modo de desenvolvimento.
    ```sh
    npm run dev
    ```
    
5.  **Acesse a Aplicação:**
    Após o comando anterior, o terminal mostrará uma mensagem indicando que o servidor está rodando. Geralmente, você poderá acessar a aplicação em seu navegador no endereço `http://localhost:3000`.



