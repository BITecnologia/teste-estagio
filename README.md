
# Teste para Estágio - BI Tecnologia

### Sobre o teste

O teste consta em desenvolver uma aplicação de controle de cliente e seus respectivos projetos, para um empresa de desenvolvimento.

### Requisitos

**[Obrigatório]**
- Sistema deve ser desenvolvido com a linguagem de programação que desejar
- Armazenar as informações em um banco de dados
- O Sistema deve conter um CRUD (listagem, cadastro, edição  e exclusão) de **Cliente** com os seguintes campos obrigatório:
	- id: identificador interno do sistema [int e autoincremente];
	- razão social: string
	- cnpj: string
	- nome do contato: string
	- email do contato: string
	- telefone do contato: string
	- endereço: string
- O Sistema deve conter um CRUD (listagem, cadastro, edição e exclusão) de **Projetos** com os seguintes campos obrigatório:
	- id: identificador interno do sistema [int e autoincremente];
	- nome do projeto: string
	- descrição do projeto: text
	- valor: float
	- prazo: date
	- status do projeto (em analise, reprovado, aprovado): string ou enum
	- cliente: um **Projeto** deve conter uma relação com um **Cliente**, assim como um **Cliente** pode ter varios **Projeto**

**[Desejável]**

- Utilizar POO (Programação orientada a objetos).
- Validação do cadastro não permitindo cadastrar sem os campos obrigatórios informado.
- Validação do número de CNPJ.
- Verificar a data de prazo do **Projeto**, para informar ao usuário se o mesmo se encontra atrasado.
- Ter um sistema de autenticação para ter acesso as páginas da aplicação.
- Relatório, ter a opção de exportar a listagem de clientes em PDF e XLS.
- Utilizar GIT para controle de versionamento do código da aplicação.

***Obs:** Você está livre para adicionar novos campos e funcionalidades a aplicação caso ache necessário*
