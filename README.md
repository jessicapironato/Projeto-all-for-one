# Projeto All For One

Seja bem-vindo ao repositório do projeto All For One! Neste projeto, você terá a oportunidade de praticar todos os conceitos de SQL utilizando o banco de dados Northwind.

## Configuração do Projeto

Antes de começar, verifique se você possui o Docker Compose na versão 1.29 ou superior instalado. Caso contrário, consulte a documentação para realizar a instalação.

Para iniciar o projeto utilizando o Docker, siga as orientações abaixo:

1. Execute o comando para iniciar os serviços `node` e `db` utilizando o Docker Compose:
   ```
   docker-compose up -d
   ```

2. Verifique se o serviço MySQL local, caso esteja em execução na porta padrão (3306), foi parado. Caso contrário, adapte as configurações de porta para evitar conflitos com os containers.

## Utilização do Container

Após iniciar o ambiente com o Docker Compose, você pode executar os seguintes comandos:

- Para acessar o terminal interativo do container `all_for_one`, execute o comando:
  ```
  docker exec -it all_for_one bash
  ```

- Dentro do terminal do container, você pode instalar as dependências específicas do projeto com o comando:
  ```
  npm install
  ```

- Importante: Todos os comandos definidos no arquivo `package.json` (como `npm start`, `npm test`, `npm run dev`, etc.) devem ser executados dentro do container. Certifique-se de utilizar o terminal do container para executar esses comandos.

- Lembre-se de que as credenciais de acesso ao banco de dados estão definidas no arquivo `docker-compose.yml` e são acessíveis no container por meio das variáveis de ambiente `MYSQL_USER` e `MYSQL_PASSWORD`.

## Clonando o Repositório

Para clonar o repositório e iniciar o projeto, execute os seguintes passos:

1. Clone o repositório

2. Acesse o diretório do projeto:
   ```
   cd all-for-one
   ```

3. Instale as dependências:
   ```
   npm install
   ```

4. Restaure a tabela do banco de dados Northwind e execute as queries para consultar os dados necessários.

## Habilidades Desenvolvidas

Ao trabalhar neste projeto, você terá a oportunidade de aprimorar suas habilidades em:

- Utilização de SQL para consultas e manipulação de dados em um banco de dados.
- Uso do Docker e Docker Compose para configurar e executar o ambiente do projeto.
- Prática de consultas complexas utilizando a base de dados Northwind.

## Contribuição

Contribuições para este projeto são bem-vindas! Se você tiver sugestões de melhorias, correções de bugs ou novas funcionalidades, sinta-se à vontade para contribuir seguindo as etapas abaixo:

1. Crie um fork do repositório.
2. Crie uma branch para sua feature/correção: `git checkout -b minha-feature`.
3. Faça as alterações desejadas.
4. Faça o commit das suas alterações: `git commit -m 'Minha nova feature'`.
5. Envie para o repositório remoto: `git push origin minha-feature`.
6. Abra um pull request explicando suas alterações.

Agradecemos ant

ecipadamente pelo seu interesse em contribuir para este projeto!

## Contato

Em caso de dúvidas ou sugestões, sinta-se à vontade para entrar em contato:

- E-mail: jessicapmaximo@gmail.com
- GitHub: [https://github.com/jessicapironato](https://github.com/jessicapironato)
- LinkedIn: [https://www.linkedin.com/in/jessica-pironato/](https://www.linkedin.com/in/jessica-pironato/)

---

Esperamos que você aproveite o projeto All For One e aprimore suas habilidades em SQL e manipulação de dados com o banco de dados Northwind!
