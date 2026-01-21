CRUD Angular + Spring Boot

Este projeto é uma aplicação fullstack desenvolvida durante o curso da Loiane Training. A aplicação consiste em um sistema de gerenciamento de cursos (CRUD), utilizando Angular para o front-end e Spring Boot para o back-end.
🚀 Tecnologias Utilizadas
Front-end

    Angular (v12+ ou a que você estiver usando)

    Angular Material (Componentes de UI)

    RxJS (Programação reativa)

Back-end

    Java (v11 ou 17)

    Spring Boot (Web, Data JPA, Validation)

    H2 Database (Banco de dados em memória para desenvolvimento)

    Lombok (Para produtividade no Java)

📋 Funcionalidades

    [x] Listagem de cursos.

    [x] Cadastro de novos cursos.

    [x] Edição de cursos existentes.

    [x] Exclusão de cursos.

    [x] Validação de formulários.

    [x] Tratamento de erros no front e back-end.

🔧 Como rodar o projeto
Pré-requisitos

    Node.js e Angular CLI instalados.

    JDK (Java Development Kit) instalado.

    Uma IDE (VS Code, IntelliJ ou Eclipse).

Passo a passo

    Clonar o repositório:
    Bash

    git clone https://github.com/seu-usuario/nome-do-repositorio.git

    Configurar o Back-end:

        Navegue até a pasta do servidor (geralmente spring-boot).

        Execute o projeto usando sua IDE ou via terminal:
        Bash

        ./mvnw spring-boot:run

        O servidor rodará por padrão na porta 8080.

    Configurar o Front-end:

        Navegue até a pasta do cliente (geralmente angular).

        Instale as dependências:
        Bash

        npm install

        Inicie o servidor de desenvolvimento:
        Bash

        ng serve

        Acesse http://localhost:4200/ no seu navegador.

📚 Aprendizados

Neste projeto, pude colocar em prática conceitos como:

    Criação de APIs RESTful com Spring Boot.

    Integração entre Front e Back via HTTP (HttpClient).

    Uso de Standalone Components e Angular Material.

    Configuração de Proxy no Angular para evitar erros de CORS durante o desenvolvimento.
