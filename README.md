# SalesWebMvc

Este repositório contém um Sistema Web com ASP .NET Core MVC e Entity Framework. O sistema faz o controle de vendas de um vendedor, associado a um determinado departamento. Foram implementados o CRUD para cada domínio, como o controle de integridade referencial. Foi implementado também relatório de vendas.

<h1>Pré-Requisito</h1>
Visual Studio e Mysql
</br></br>
<p>Para instalar o Mysql e o banco de dados, siga os passos abaixo:</p>
                <ul>
                    <li>Entre no site<a href="https://dev.mysql.com/downloads/">dev.mysql.com/downloads</a></li>
                    <li>Escolha a versão MySQL Community Server</li>
                    <li>Clique em Go to Download Page</li>
                    <li>Escolha o instalador</li>
                    <li>Na próxima página escolha o link paa iniciar o download</li>
                    <li>Execute o arquivo</li>
                    <li>Aceite o termo de licença</li>
                    <li>Escolha a opção Developer Default(contém algumas ferramente, entre as principais o workbanch)</li>
                    <li>O conector Python não é necessário para este projeto, então clique em next</li>
                    <li>Clique em Execute</li>
                    <li>Clique em Next</li>
                    <li>Nas opções de replicação, escolha a opção Standalone e clique em next</li>
                    <li>Na próxima página, pode deixar o tipo de configuração como de desenvolvedor e a porta 3306</li>
                    <li>Escolha a opção compatível com o MySQL 5.x e clique em next</li>
                    <li>Digite a senha de root</li>
                    <li>Aproveite para criar o usuário developer, com acesso de administrador e digite a senha 1234567</li>
                    <li>É importante manter esse usuários, pois a string de conexão do projeto está configurada assim/li>
                    <li>Clique em Ok e Next</li>
                    <li>Escolha a opção de sua preferência para inicialização do MySQL, junto com a inicialização do sistema ou não</li>
                    <li>Deixe as opções Standard System Acoount e o MySQL Server as a Windows Service habilitadas e clique em next</li>
                    <li>Clique em Execute e Finish em seguida</li>
                    <li>Clique em Next</li>
                    <li>Faça um teste com a senha recém criada para o root e clique em next</li>
                    <li>Clique em Execute e Finish em seguida</li>
                    <li>Clique em Next e Finish em seguida</li>
                    <li>Entre no painel de controles e procure por ferramentes administrativas</li>
                    <li>Entre em serviços e procure por MySQL</li>
                    <li>Caso o serviço não esteja em execução inicie o mesmo</li>
                    <li>Inicie o MySQL Workbench e entre com os dados recém criados</li>
                    <li>Faça o clone do repositório na sua máquina</li>
                    <li>Abra-o utilizando o Visual Studio</li>
                    <li>Abra o Package Manager Console (View -> Other Windows -> Package Manager Console</li>
                    <li>Execute o comando Update-Database (Para gerar a estrutura da base de dados)</li>
                    <li>A inserção inicial de dados foi feita pela Classe SeedingService, que foi registrada no Startup</li>
                    <li>Sendo assim execute o programa para fazer a inserção dos dados. Isso em ambiente de desenvolvimento e caso não tenha dados na base de dados, conforme as classes Startup e SeedingService</li>
                </ul>
<h1>Conceitos</h1>
Foram utilizados conceitos de Orientação a Objetos, Delegação de Serviços, Injeção de dependência, Banco de dados SQL, Linq, padrão MVC, Entity Framework (ORM), Migrations, Code-First(banco de dados é gerado a partir das classes) e Bootstrap.
