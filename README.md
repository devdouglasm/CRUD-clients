<h1> Sistema CRUD de Clientes </h1>
<p>Este é um projeto de sistema CRUD (Create, Read, Update, Delete) para gerenciamento de clientes, desenvolvido em Java e Spring Boot. 
Ele permite realizar operações básicas de cadastro, consulta, atualização e exclusão de dados de clientes, aplicando boas práticas de desenvolvimento e arquitetura.
</p>

<h2> Tecnologias e Ferramentas Utilizadas</h2>
<ul>
    <li><strong>Java 21</strong></li>
    <li><strong>Spring Boot 3.4.3</strong></li>
    <li><strong>Spring Data JPA</strong> com Hibernate para manipulação de dados</li>
    <li><strong>Banco de Dados H2</strong> em memória para armazenamento dos dados</li>
    <li><strong>Bean Validation</strong> para validação dos dados de entrada</li>
</ul>

<h2> Funcionalidades</h2>
<ul>
    <li>✅ <strong>Cadastro de Clientes:</strong> Permite a criação de um novo cliente com dados como nome, e-mail, telefone, etc.</li>
    <li>✅ <strong>Listagem de Clientes:</strong> Exibe a lista completa dos clientes cadastrados.</li>
    <li>✅ <strong>Consulta de Cliente:</strong> Permite a busca de um cliente específico pelo seu ID.</li>
    <li>✅ <strong>Atualização de Dados do Cliente:</strong> Atualiza informações de um cliente existente.</li>
    <li>✅ <strong>Exclusão de Cliente:</strong> Remove um cliente do sistema pelo ID.</li>
</ul>

<h2> Estrutura do Projeto</h2>
<ul>📁 src/main/java
<li>├── 📂 controllers   # Contém os controladores REST (endpoints)</li>
<li>├── 📂 services      # Camada de serviço com a lógica de negócio</li>
<li>├── 📂 repositories  # Interfaces de repositório para acesso ao banco de dados</li>
<li>├── 📂 entities      # Classes de modelo que representam as entidades do banco de dados</li>
<li>├── 📂 dto           # Classes de Transferência de Dados (Data Transfer Objects)</li>
</ul>


<h2>📝 Exemplos de Uso</h2>
<h3>1️⃣ Cadastro de um novo cliente</h3>
<p><strong>Endpoint:</strong> <code>POST /clients</code></p>

<h3>2️⃣ Listagem de todos os clientes</h3>
<p><strong>Endpoint:</strong> <code>GET /clients</code></p>

<h3>3️⃣ Consulta de cliente por ID</h3>
<p><strong>Endpoint:</strong> <code>GET /clients/{id}</code></p>

<h3>4️⃣ Atualização de dados do cliente</h3>
<p><strong>Endpoint:</strong> <code>PUT /clients/{id}</code></p>
  
<h3>5️⃣ Exclusão de um cliente</h3>
<p><strong>Endpoint:</strong> <code>DELETE /clients/{id}</code></p>

<h2></h2>


<p>📌 <strong>Desenvolvido por <a href="https://github.com/devdouglasm">devdouglasm</a></strong> 🚀</p>
