# ☕ Serenatto Café

Projeto desenvolvido durante os estudos da **Formação PHP** da [Alura](https://www.alura.com.br/).
Trata-se de uma aplicação para gerenciar o cardápio de uma cafeteria, utilizando PHP e conexão com banco de dados MySQL.

## 🚀 Tecnologias Utilizadas

*   PHP 8+
*   MySQL
*   HTML/CSS
*   PDO (PHP Data Objects)

## ⚙️ Pré-requisitos

Para rodar este projeto localmente, você precisará ter instalado:
*   [PHP](https://www.php.net/)
*   [MySQL Server](https://dev.mysql.com/downloads/mysql/)

## 📝 Configuração do Banco de Dados

1.  Crie um banco de dados no seu MySQL chamado `serenatto`.
2.  Importe o arquivo SQL (ex: `Dump20251201.sql`) localizado na raiz do projeto para popular as tabelas.
3.  Verifique o arquivo de conexão (geralmente em `src/conexao-bd.php`) e certifique-se de que o usuário e senha do banco correspondem à configuração da sua máquina local.

```php
// Exemplo de configuração no arquivo:
$pdo = new PDO('mysql:host=localhost;dbname=serenatto', 'root', 'sua_senha');

```

## ▶️ Como rodar o projeto

Este projeto utiliza o servidor embutido do PHP, não sendo necessário instalar Apache ou Nginx separadamente.

1. Abra o terminal na pasta raiz do projeto.
2. Execute o seguinte comando para iniciar o servidor:

```bash
php -S localhost:8080
```

Nota: Se a porta 8080 estiver ocupada, você pode alterar para outro número, como php -S localhost:8989.
Desenvolvido por Liliane para fins de estudo.
