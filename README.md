# Leinad - Bot para WhatsApp com IA

Bem-vindo ao repositório do **Leinad**, um bot para WhatsApp desenvolvido em Node.js. Este projeto integra o poder da inteligência artificial generativa do Google com a automação do WhatsApp, permitindo interações inteligentes e dinâmicas.

## 📝 Descrição

O **Leinad** é um bot projetado para se conectar a uma conta do WhatsApp e responder a mensagens de forma autônoma. Ele utiliza a biblioteca **`@whiskeysockets/baileys`** para gerenciar a conexão via QR Code e a troca de mensagens, e a API **`@google/generative-ai`** para processar e gerar respostas inteligentes, tornando-o um assistente virtual versátil.

O projeto também inclui o uso de um banco de dados PostgreSQL (`pg`) para persistência de dados, permitindo que o bot armazene informações e mantenha o contexto das conversas.

## ✨ Funcionalidades

- **Conexão via QR Code:** Autenticação simples e rápida escaneando um QR Code no terminal.
- **Inteligência Artificial Generativa:** Respostas criadas dinamicamente pela IA do Google.
- **Comunicação em Tempo Real:** Interage com contatos e grupos no WhatsApp.
- **Persistência de Dados:** Utiliza PostgreSQL para armazenar informações importantes.
- **Estrutura Escalável:** Pronto para receber novas funcionalidades e comandos.

## 🚀 Tecnologias Utilizadas

| Dependência                 | Descrição                                                              |
| --------------------------- | ---------------------------------------------------------------------- |
| **`@whiskeysockets/baileys`** | Biblioteca principal para interagir com a API não oficial do WhatsApp. |
| **`@google/generative-ai`**   | SDK para integrar o bot com os modelos de IA generativa do Google.     |
| **`qrcode-terminal`**         | Gera o QR Code de autenticação diretamente no terminal.                |
| **`pg`**                      | Cliente PostgreSQL para Node.js, usado para conectar ao banco de dados.  |
| **`dotenv`**                  | Carrega variáveis de ambiente (como chaves de API) de um arquivo `.env`. |
| **`pino`**                    | Logger de alta performance para registrar eventos e depurar o bot.      |
| **`sharp`**                   | Biblioteca para processamento de imagens, como stickers e mídias.      |

## ⚙️ Instalação e Execução

Para executar este projeto localmente, você precisará do [Node.js](https://nodejs.org/ ) (versão 18.0 ou superior) instalado.

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/Danielalves33147/Leinadobot-Teste.git
    cd Leinadobot-Teste
    ```

2.  **Instale as dependências:**
    Este comando irá ler o `package.json` e instalar todas as bibliotecas necessárias.
    ```bash
    npm install
    ```

3.  **Inicie o bot:**
    Execute o comando abaixo. Na primeira vez, um QR Code será exibido no terminal. Escaneie-o com o aplicativo do WhatsApp (em *Aparelhos conectados* ) para autenticar.
    ```bash
    npm start
    ```
    Após a autenticação, o bot estará online e pronto para interagir.

## 🤝 Como Contribuir

Contribuições são muito bem-vindas! Se você tem ideias para novas funcionalidades ou melhorias, siga os passos:

1.  Faça um **fork** do projeto.
2.  Crie uma nova **branch** (`git checkout -b feature/nova-feature`).
3.  Faça o **commit** de suas alterações (`git commit -m 'Adiciona nova feature'`).
4.  Envie para a sua branch (`git push origin feature/nova-feature`).
5.  Abra um **Pull Request**.

## 📄 Licença

Este projeto está sob a licença ISC.
