# CulturaLocal

## Descrição

O Cultura Local App é um aplicativo Java desenvolvido para disponibilizar livros nacionais gratuitos ao público. Com uma interface amigável, os usuários podem explorar uma vasta coleção de livros, promovendo a leitura e o acesso à cultura literária brasileira. O aplicativo está integrado a um banco de dados que armazena e gerencia os livros, proporcionando uma experiência de uso eficiente e prática.

## Dependências

O Cultura Local App possui as seguintes dependências:

- Java JDK 11+
- JavaFX: Para a interface gráfica.
- MySQL: Para o banco de dados.
- Hibernate: ORM para facilitar o mapeamento objeto-relacional.
- Apache Tomcat: Servidor web para a API REST.
- Apache Maven: Para gerenciamento de dependências e construção do projeto.
- Configuração e Instalação

### Passo 1: Clone o Repositório

Clone o repositório do GitHub para a sua máquina local:

git clone https://github.com/seu-usuario/cultura-local-app.git

### Passo 2: Configure o Banco de Dados

 - Crie um banco de dados MySQL para o aplicativo:

CREATE DATABASE cultura_local;

- Importe o esquema do banco de dados que está no arquivo schema.sql no diretório do repositório clonado:

mysql -u seu-usuario -p cultura_local < path/to/schema.sql

- Atualize o arquivo src/main/resources/hibernate.cfg.xml com suas credenciais do MySQL.


### Passo 3: Compile o Projeto

Navegue até o diretório do projeto e compile usando Maven:

cd cultura-local-app
mvn clean install

### Passo 4: Execute o Aplicativo

Inicie o servidor Tomcat e execute o aplicativo:

mvn tomcat7:run

### Passo 5: Acesse o Aplicativo

Abra seu navegador e acesse:

http://localhost:8080/cultura-local-app

## Diagrama de Classe
O diagrama de classe do aplicativo pode ser visualizado no link abaixo:

[Diagrama de Classe - draw.io](https://drive.google.com/file/d/1-AQ9ti8JQ_kXp2ZRGPz3aR4RHEpQUlHD/view?usp=sharing)

## Prints das Telas
Tela Principal
<img src="data:image/png;base64,{base64_image_1}" alt="Tela Principal" width="400"/>
Tela de Detalhes do Livro
<img src="data:image/png;base64,{base64_image_2}" alt="Tela Detalhes Livro" width="400"/>
Tela de Favoritos
<img src="data:image/png;base64,{base64_image_3}" alt="Tela de Favoritos" width="400"/>


## Funcionamento do Sistema

### Contribuição

Se você deseja contribuir com o desenvolvimento do Cultura Local App, siga os passos abaixo:

- Fork o repositório
- Crie uma nova branch (git checkout -b feature/nova-feature)
- Faça suas modificações
- Commit suas alterações (git commit -m 'Adiciona nova feature')
- Envie para o repositório remoto (git push origin feature/nova-feature)
- Abra um Pull Request

## Licença
Este projeto está licenciado sob os termos da licença MIT. Veja o arquivo 'LICENSE' para mais detalhes.
