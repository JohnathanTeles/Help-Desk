# 📌 Sistema de Chamados - PHP & Bootstrap
🚀 Este projeto faz parte do curso de Desenvolvimento Web na Udemy.

Este é um projeto simples de um **Sistema de Chamados** desenvolvido com **PHP, HTML, CSS e Bootstrap**. O objetivo é permitir que usuários registrem chamados relacionados a problemas técnicos, como falhas de hardware ou software.

## 🛠️ Funcionalidades
- 🔒 **Autenticação de Usuário** (cadastro manual no código, sem banco de dados)
- 📝 **Registro de Chamados** (título, categoria e descrição)
- 📋 **Listagem de Chamados** para consulta posterior
- 📱 **Interface Responsiva** utilizando Bootstrap

## 🚀 Tecnologias Utilizadas
- **PHP**: Processamento do back-end
- **HTML & CSS**: Estrutura e estilização das páginas
- **Bootstrap**: Design moderno e responsivo

## 📂 Estrutura do Projeto
```
/meu-projeto  
│── index.php        # Página de login  
│── home.php         # Página principal após login  
│── abrir_chamado.php # Formulário para abrir um chamado  
│── consultar.php    # Listagem de chamados  
│── validar_login.php # Validação de usuários  
│── assets/          # Arquivos CSS, JS e imagens  
```

1. Inicie um servidor local com suporte a PHP, como o **XAMPP** ou **PHP Built-in Server**:
   ```bash
   php -S localhost:8000
   ```
2. Acesse `http://localhost:8000` no navegador.
3. Faça login utilizando as seguintes credenciais:
   - **Email:** adm@teste.com.br
   - **Senha:** 123456
4. Registre e consulte chamados.

## 📝 Observações
- O login é realizado sem banco de dados, os usuários estão cadastrados manualmente no código.
- O projeto pode ser facilmente expandido para incluir um banco de dados no futuro.

💻 **Desenvolvido por [Seu Nome](https://github.com/johnathanTeles)**
