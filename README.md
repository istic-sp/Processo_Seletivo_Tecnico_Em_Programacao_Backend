# Técnico em Programação - Backend

### **Desafio: Criação de uma API RESTful para Gerenciamento de Tarefas**

### **Objetivo:**

O objetivo deste desafio é avaliar suas habilidades em desenvolvimento backend utilizando .NET, criação de uma API RESTful, e documentação da API com Swagger. Você terá 1h30min para completar o desafio.

### **Descrição do Desafio:**

Você foi contratado para desenvolver uma API que gerencie tarefas de um sistema simples de gerenciamento de tarefas (To-Do List). A API deve permitir que os usuários possam criar, listar, atualizar e excluir tarefas.

### **Requisitos Funcionais:**

1. **Cadastro de Tarefa:**
    - Endpoint: `POST /api/tasks`
    - A API deve permitir a criação de uma nova tarefa com os seguintes atributos:
        - **Id**: identificador único da tarefa (gerado automaticamente)
        - **Título**: título da tarefa (string, obrigatório)
        - **Descrição**: descrição da tarefa (string, opcional)
        - **Data de Criação**: data em que a tarefa foi criada (gerado automaticamente)
        - **Data de Conclusão**: data em que a tarefa foi concluída (nullable, opcional)
        - **Status**: status da tarefa (pendente, concluída)
2. **Listagem de Tarefas:**
    - Endpoint: `GET /api/tasks`
    - A API deve permitir listar todas as tarefas cadastradas, com a possibilidade de filtrar por status (pendente/concluída).
3. **Atualização de Tarefa:**
    - Endpoint: `PUT /api/tasks/{id}`
    - A API deve permitir atualizar uma tarefa existente com base no seu Id. Deve ser possível atualizar o título, descrição, data de conclusão e status.
4. **Exclusão de Tarefa:**
    - Endpoint: `DELETE /api/tasks/{id}`
    - A API deve permitir excluir uma tarefa existente com base no seu Id.

### **Requisitos Não Funcionais:**

- **Documentação da API:** Utilize o Swagger para documentar todos os endpoints criados.
- **Persistência de Dados:** Utilize uma abordagem em memória para armazenar as tarefas (não é necessário um banco de dados).
- **Boas Práticas:** Escreva código limpo e utilize boas práticas de desenvolvimento, como validações de entrada e tratamento de erros.

### **Entregáveis:**

- Código-fonte da API desenvolvido em .NET (pode ser em .NET Core ou .NET 5+).
- Documentação Swagger acessível através do endpoint `/swagger`.

### **Critérios de Avaliação:**

- **Funcionalidade:** A API atende aos requisitos funcionais descritos?
- **Qualidade do Código:** O código é legível, bem organizado e segue boas práticas?
- **Uso do Swagger:** A documentação está completa e clara?
- **Gestão do Tempo:** O candidato conseguiu entregar uma solução funcional no tempo estipulado?

### **Entrega:**

- Atente-se com a entrega, crie o repositório já no início da execução da prova;
- Encaminhar um email com o link do repositório **público** para: [**paulo.brandao@sp.senai.br**](mailto:paulo.brandao@sp.senai.br), com cópia para: [**oliver.silva@sp.senai.br**](mailto:oliver.silva@sp.senai.br);
- Assunto: Processo Seletivo Backend Jr.
- Mensagem contendo: nome completo;
