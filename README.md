# 🎓 MVC Web - Cadastro de Alunos

Projeto desenvolvido como atividade prática da disciplina, com o objetivo de
demonstrar na prática o padrão arquitetural **MVC (Model-View-Controller)**
utilizando **Spring Boot** e **Thymeleaf**.

---

## 📐 O que é MVC?

MVC é um padrão de arquitetura de software que separa a aplicação em 3 camadas:

| Camada | Responsabilidade |
|---|---|
| **Model** | Contém as regras de negócio e os dados. Não sabe nada sobre HTTP ou HTML. |
| **View** | Apenas exibe os dados para o usuário. Não contém lógica de negócio. |
| **Controller** | Recebe as requisições, chama o Model e decide qual View exibir. |

---
## 📁 Estrutura do Projeto

    mvc-web-alunos/
    └── src/
        └── main/
            ├── java/
            │   └── com/exemplo/mvc/
            │       ├── model/
            │       │   └── Aluno.java           → Model (regra de negócio)
            │       ├── controller/
            │       │   └── AlunoController.java → Controller (coordena o fluxo)
            │       └── MvcApplication.java      → Classe principal
            └── resources/
                └── templates/
                    ├── alunos-form.html         → View (formulário de cadastro)
                    └── alunos-lista.html        → View (lista de alunos)

## 🚀 Como executar o projeto

### Pré-requisitos
- Java 21 instalado
- VS Code com as extensões:
  - Extension Pack for Java
  - Spring Boot Extension Pack

### Passos
1. Clone o repositório
2. Abra no VS Code: **File → Open Folder**
3. Aguarde o VS Code importar o projeto (barra inferior: *"Java: Ready"*)
4. Abra o arquivo `MvcApplication.java`
5. Clique em ▶ **Run**
6. Acesse no navegador: `http://localhost:8080/alunos`
