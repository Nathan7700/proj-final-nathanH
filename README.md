# 🛒 E-Commerce Project

Este é um projeto de sistema de e-commerce desenvolvido como parte do projeto final, focado em escalabilidade, organização de código e boas práticas de versionamento.

## 🚀 Tecnologias Utilizadas

* **Linguagem:** Python 3.x
* **Banco de Dados:** SQL (PostgreSQL/MySQL)
* **Versionamento:** Git (Git Flow)
* **Ambiente Virtual:** venv / pip

## 🛠️ Estrutura do Projeto

O projeto segue a arquitetura de **Programação Orientada a Objetos (POO)** e manipulação de dados via SQL:

- `/src`: Código-fonte do projeto.
- `/database`: Scripts de criação e modelagem do banco de dados.
- `/docs`: Documentação adicional e evidências.

## 🔄 Fluxo de Trabalho (Git Flow)

Para garantir a integridade do código e a colaboração eficiente entre a equipe, utilizamos o seguinte padrão:

1.  **Main:** Código estável e pronto para produção.
2.  **Develop:** Branch principal de integração.
3.  **Feature/):** Ramos criados para cada funcionalidade específica (ex: `feature/login`, `feature/carrinho`).
4.  **Pull Requests (PR):** Toda alteração passa por revisão de código antes do merge.

## 💻 Como Executar

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/seu-usuario/nome-do-repositorio.git](https://github.com/seu-usuario/nome-do-repositorio.git)
    ```

2.  **Crie e ative o ambiente virtual:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # No Windows: venv\Scripts\activate
    ```

3.  **Instale as dependências:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Execute a aplicação:**
    ```bash
    python main.py
    ```
