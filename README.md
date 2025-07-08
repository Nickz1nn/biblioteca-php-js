# 📚 Library-PHP

Um sistema de gerenciamento de biblioteca desenvolvido em **PHP**, com interface em **HTML** e **Bootstrap**, banco de dados **MySQL** e servidor local **Laragon**. Este projeto foi criado para facilitar o cadastro, edição, exclusão e listagem de livros, bibliotecas, categorias, alunos e atendentes.

---

## 🚀 Tecnologias Utilizadas

| Tecnologia                                                                                      | Descrição                                                              |
| ----------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------- |
| ![PHP](https://img.shields.io/badge/-PHP-777BB4?logo=php\&logoColor=white)                      | Linguagem de servidor usada para criar a lógica de negócio do sistema. |
| ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript\&logoColor=black) | Para manipulação dinâmica do frontend.                                 |
| ![HTML](https://img.shields.io/badge/-HTML5-E34F26?logo=html5\&logoColor=white)                 | Para estruturação das páginas do sistema.                              |
| ![Bootstrap](https://img.shields.io/badge/-Bootstrap-7952B3?logo=bootstrap\&logoColor=white)    | Framework para estilização das páginas.                                |
| ![MySQL](https://img.shields.io/badge/-MySQL-4479A1?logo=mysql\&logoColor=white)                | Banco de dados usado para armazenar as informações do sistema.         |
| ![Laragon](https://img.shields.io/badge/-Laragon-0E83CD?logo=laravel\&logoColor=white)          | Ambiente de desenvolvimento local utilizado para rodar o projeto.      |

---

## 🛠️ Pré-requisitos

* **Laragon** instalado e configurado.
* Banco de dados MySQL configurado.
* Navegador moderno para acessar a aplicação.

### 💡 Dicas para Configurar o Laragon

Se você teve dificuldades para configurar o Laragon, aqui estão alguns passos para facilitar:

1. **Instalação:** Baixe e instale o Laragon pelo site oficial ([Laragon.org](https://laragon.org/)).
2. **Configuração do Banco de Dados:** Use o HeidiSQL (ou outro cliente MySQL) para criar as tabelas do banco. Certifique-se de que o nome do banco corresponde ao esperado no arquivo `config.php`.
3. **Configuração do Projeto:** Coloque os arquivos do projeto na pasta `C:\laragon\www\routes\Library-PHP\`.
4. **Iniciando o Servidor:** Use o botão **Start All** no Laragon para iniciar o servidor Apache e o MySQL.

---

## 📂 Estrutura do Projeto

```
Library-PHP/
├── index.php
├── config.php
├── pages/
│   ├── cadastrar-aluno.php
│   ├── cadastrar-livro.php
│   ├── editar-aluno.php
│   ├── listar-aluno.php
│   ├── salvar-aluno.php
│   └── salvar-livro.php
└── assets/
    ├── css/
    └── js/
```

---

## ⚙️ Configuração do Banco de Dados

Crie o banco de dados conforme os scripts fornecidos para as tabelas de alunos, livros, bibliotecas e categorias. Se encontrar erros como `Unknown database` ou `Unknown column`, verifique se as tabelas foram criadas corretamente e se os nomes estão corretos.

---

## 💻 Rodando o Projeto

1. Coloque os arquivos do projeto na pasta do Laragon (`C:\laragon\www\routes\Library-PHP\`).
2. Crie o banco de dados MySQL (`biblioteca5152m`).
3. Inicie o servidor do Laragon.
4. Acesse `http://localhost/routes/Library-PHP` em seu navegador.

---

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para fazer um fork deste repositório e enviar pull requests com melhorias.

---
