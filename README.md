# Leinadobot-Teste

Um bot multifuncional para Discord, desenvolvido em Node.js, criado para testar e implementar novas funcionalidades de automação e interação.

## 📝 Descrição

O **Leinadobot-Teste** é um projeto de bot para Discord que serve como um ambiente de desenvolvimento e aprendizado. Seu principal objetivo é explorar as capacidades da API do Discord e da biblioteca `discord.js`, implementando desde comandos simples até funcionalidades mais complexas de moderação e interação com usuários.

## ✨ Funcionalidades Potenciais

Este bot está preparado para ter funcionalidades como:
- **Comandos de Interação:** Respostas automáticas a comandos específicos (ex: `!ping`, `!ajuda`).
- **Moderação de Servidor:** Gerenciamento de cargos, mensagens e usuários.
- **Notificações:** Alertas automáticos para eventos específicos no servidor.
- **Integração com APIs Externas:** Busca de dados em outras plataformas para exibir no Discord.

## 🚀 Tecnologias Utilizadas

- **Node.js:** Ambiente de execução de JavaScript no lado do servidor.
- **discord.js:** Biblioteca poderosa para interagir com a API do Discord de forma simples e eficiente.
- **dotenv:** Módulo para carregar variáveis de ambiente a partir de um arquivo `.env`, mantendo tokens e chaves seguras.

## ⚙️ Instalação e Execução

Para executar este projeto localmente, você precisará do [Node.js](https://nodejs.org/ ) (versão 16.9.0 ou superior) instalado em sua máquina.

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/Danielalves33147/Leinadobot-Teste.git
    cd Leinadobot-Teste
    ```

2.  **Instale as dependências:**
    Este comando irá baixar e instalar todas as bibliotecas necessárias para o projeto, como o `discord.js`.
    ```bash
    npm install discord.js dotenv
    ```
    *Este comando também criará o arquivo `package.json` e `package-lock.json` se eles não existirem.*

3.  **Configure as variáveis de ambiente:**
    - Crie um arquivo chamado `.env` na pasta principal do projeto.
    - Dentro deste arquivo, adicione o token do seu bot, que pode ser obtido no Portal de Desenvolvedores do Discord:
      ```
      BOT_TOKEN=COLE_O_SEU_TOKEN_AQUI
      ```

4.  **Inicie o bot:**
    Execute o comando abaixo para colocar o bot online. Certifique-se de que o arquivo principal do seu bot se chama `index.js` ou ajuste o comando conforme necessário.
    ```bash
    node index.js
    ```

## 🤝 Como Contribuir

Contribuições são sempre bem-vindas. Se você deseja melhorar este projeto, siga os passos abaixo:

1.  Faça um **fork** do repositório.
2.  Crie uma nova **branch** para sua funcionalidade (`git checkout -b feature/nova-feature` ).
3.  Faça o **commit** de suas alterações (`git commit -m 'Adiciona nova feature'`).
4.  Envie suas alterações para a branch (`git push origin feature/nova-feature`).
5.  Abra um **Pull Request**.

## 📄 Licença

Este projeto é distribuído sob a licença MIT. Consulte o arquivo `LICENSE` para mais detalhes.
