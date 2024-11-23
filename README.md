# Projeto de Banco de Dados OracleSQL 📊

---

## Descrição do Projeto

Este projeto consiste na criação e gerenciamento de um banco de dados utilizando OracleSQL, integrado com uma aplicação desenvolvida em Java. O objetivo é fornecer uma base sólida e eficiente para armazenar e manipular dados, garantindo a integridade e a performance da aplicação. Através de um modelo relacional bem estruturado, o banco de dados atende às necessidades específicas da aplicação, oferecendo suporte para operações complexas e um gerenciamento eficiente dos dados.

### Funcionalidades principais:

- **Modelo de Dados Relacional**: Estrutura de dados bem definida, com tabelas normalizadas para evitar redundâncias e garantir a integridade referencial.
- **Conexão com Java**: Integração com uma aplicação Java, permitindo operações CRUD (Create, Read, Update, Delete) através de interfaces de usuário intuitivas.
- **Procedures e Triggers**: Implementação de procedures e triggers para automatizar tarefas e garantir a consistência dos dados.
- **Consultas Otimizadas**: Utilização de índices e otimizações de consultas para melhorar a performance do banco de dados.

---

## Links
- **Modelo Conceitual**: [Diagrama ER no Figma](https://www.figma.com/design/Ir8V7KPSws9gH2ncECyi20/Global-Solution-FIGMA?node-id=0-1&t=lP467r4AvsqUzDdJ-1)
- **Documentação do Projeto**: [Miro Board](https://miro.com/welcomeonboard/V2NOUThhVkZWb3F5YVhPcHlKZ1lEYjMxdVF6bzBFbDJDL21wdE5OcFAzb1M4SSt1cm5uNTFldGI2SE1tZGo2ZFNMbTZIcUx0ZzBwdGlWemtQSjNVamVTblNRd0hWWWw2clpGd0Rwd0JXMmQ0S1RHelhxMHZ2VUZwdHFUWWJuTGwhZQ==?share_link_id=468499909302)
- **Apresentação do Projeto**: [Vídeo no YouTube](https://www.youtube.com/watch?v=8bzh6oU2oPI)
- **Demonstração da Aplicação**: [Vídeo de Demonstração](https://youtu.be/RvuU1Ag9UnY)

---

## Integrantes do Projeto 👥

- **Luis Henrique** - RM 552692  
- **Matheus Duarte** - RM 554199  
- **Sabrina Café** - RM 553568  

---

## Configuração do Projeto ⚙️

Para rodar o projeto, siga as etapas abaixo:

1. **Configuração do Banco de Dados**:
   - Crie o banco de dados OracleSQL utilizando o script `create_db.sql` fornecido.
   - Execute os scripts de criação de tabelas e inserção de dados iniciais.

2. **Configuração da Aplicação Java**:
   - Certifique-se de ter o JDK instalado.
   - Configure a conexão com o banco de dados no arquivo `dbconfig.properties`:
     ```properties
     db.url=jdbc:oracle:thin:@localhost:1521:xe
     db.username=seu_usuario
     db.password=sua_senha
     ```
   - Compile e execute a aplicação Java.

---

## Estrutura do Projeto 📁

- **src**: Código-fonte Java.
- **sql**: Scripts SQL para criação e manipulação do banco de dados.
- **docs**: Documentação do projeto, incluindo diagramas e especificações técnicas.
- **resources**: Arquivos de configuração e outros recursos necessários para a execução do projeto.

---

Este projeto foi desenvolvido como parte do curso de Banco de Dados, visando a aplicação prática dos conceitos aprendidos em sala de aula e a integração de tecnologias modernas para a solução de problemas reais.
