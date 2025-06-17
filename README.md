# StudyMatch

# Configuração do Projeto React + Node.js

## Pré-requisitos
- Node.js instalado
- XAMPP instalado (para MySQL)
- Aplicação React base já criada (usada para substituição dos arquivos)

## Passo a Passo

### 1. Configurar o ambiente
1. Inicie o XAMPP e ative:
   - Apache
   - MySQL

2. Crie o banco de dados:
   - Acesse http://localhost/phpmyadmin
   - Crie um novo banco de dados com o nome especificado no projeto

### 2. Configurar a rede
1. Descubra seu IP local:
   - Abra CMD e execute `ipconfig`
   - Anote o IPv4 do adaptador de rede sem fio

2. Atualize o IP no projeto:
   - Edite `client/src/App.js`
   - Substitua o IP existente pelo seu IPv4 anotado

### 3. Instalar dependências
Na pasta **server**:
```bash
npm install mysql2 cors nodemon axios express
```
### 4. Iniciar a aplicação
1. Primeiro o servidor (em um terminal):

```bash
cd server
npm start
```

2. Depois o cliente (em outro terminal):

```bash
cd ../client
npm start
```

3. Acesse no navegador:
http://localhost:3000

### Dependências necessárias

Backend: mysql2, cors, nodemon, axios, express

Frontend: axios

### Solução de problemas

Verifique se XAMPP está com Apache e MySQL ativos

Confira se o IP em App.js está correto

Certifique-se que todas dependências foram instaladas

Confira se o banco de dados foi criado corretamente

### Solução de Problemas

```text

Esta versão assume que:
1. O professor já tem uma estrutura React básica criada
2. Ele só precisa substituir pelos seus arquivos (client e server)
3. Foca apenas nos passos essenciais de configuração
```
