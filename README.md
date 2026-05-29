# Restaurante

Sistema de restaurante com Node.js, MySQL e interface web.

## Instalação
1. Instale as dependências:
   ```
npm install
```
2. Ajuste os dados de conexão em `db.js` se necessário.
3. Certifique-se que o banco de dados MySQL está rodando e as tabelas estejam criadas.
4. Inicie o sistema:
   ```
npm start
```
5. Acesse: http://localhost:3000

## Estrutura
- `app.js`: Backend principal Express
- `db.js`: Conexão com o MySQL
- `views/`: Páginas da interface
- `public/style.css`: CSS visual

## Funcionalidades iniciais
- Cadastro e listagem de clientes
- Estrutura pronta para pedidos, pratos, etc.
