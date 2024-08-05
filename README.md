# Instalação

Siga os passos abaixo para instalar o sistema no servidor e fazer as devidas configurações.

## 1. Banco de Dados

1. Na pasta `mysql/model`, execute o arquivo `EER Diagram.mwb` para criar o modelo do banco de dados.
2. Insira o usuário `admin` manualmente na base de dados, configurando o campo `admin_mode` para `1` para habilitar o modo admin e conceder os demais privilégios necessários.

## 2. Instalação das Dependências

Execute o comando abaixo para instalar todas as dependências necessárias do projeto:

```bash
npm install



## Testado como se fosse na vercel
npm i -g vercel
vercel login
vercel dev