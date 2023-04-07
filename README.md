# poc_cypress_api
### Automação de API com cy

#### Pré rquisitos

```
  * Node.js (https://nodejs.org/en/download)
  * Certifique-se de ter o Node.js instalado: digitando `node -v`
```

#### Inicializando o projeto
```
  * Execute o camando: `npm init -y` no teminal (VS)
  * Será criado um novo arquivo `package.json` vazio no diretório
```

#### Instalando o cypress
| Como   | Tipo       | Descrição                           |
| :---------- | :--------- | :---------------------------------- |
| linha de comando | `npm install cypress` | Instalará a versão mais recente do Cypress e todas as suas dependências |
| linha de comando | `npm install cypress@11.2.0` | Instalará a versão especifica do Cypress e todas as suas dependências |

#### Instalando o cypress desktop (caso ocorra algum problema proxy )
```
  * Para realizar o download acessar a URL https://download.cypress.io/desktop/12.9.0
  * Será realizado o download do cypress.zip, (não precisa descompactar)
  * Como administrado abra o **Windows PowerShell** e digite o comando:
  ` setx CYPRESS_INSTALL_BINARY c:\Users\**seunome**\Downloads\cypress.zip`
```
#### Via terminal VS Code
```
  * Na raiz do projeto
  * Digite o comando `npx cypress open`
  * Será aberta a infertace do Cypress e a estrutura de configuração **Cypress** e **cypress.config.js** será adicionado ao projeto.

  Obs: verifique no diretório `C:\Users\**seunome**\AppData\Local\Cypress\Cache` se foi criada a pasta com o nome da versão instalada `12.9.0`
```




