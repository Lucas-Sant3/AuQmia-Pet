Sistema web completo para gerenciamento de petshop com funcionalidades para clientes, pets, serviços e agendamentos.

📋 Funcionalidades
1. Gerenciamento de Clientes
Cadastro, edição e exclusão de clientes

Listagem com busca

Campos: Nome, CPF, Email, Telefone, Endereço, Data de Nascimento

2. Gerenciamento de Pets
Cadastro de pets vinculados a clientes

Espécies pré-definidas (Cachorro, Gato, Pássaro, Coelho, etc.)

Raças pré-cadastradas

Visualização de pets por cliente

3. Gerenciamento de Serviços
Catálogo de serviços (Banho, Tosa, Consulta Veterinária, etc.)

Preços e durações configuráveis

Descrições detalhadas

4. Agendamentos
Agendamento completo com:

Seleção de cliente

Seleção de pet (filtrado por cliente)

Escolha de serviço

Data e hora

Status (Pendente, Concluído, Cancelado)

Listagem com JOIN para visualização completa

Edição e exclusão de agendamentos

🛠️ Tecnologias Utilizadas
PHP 7.4+

MySQL 5.7+

Bootstrap 5 (para interface)

JavaScript (para interatividade)

HTML5/CSS3

🗄️ Estrutura do Banco de Dados
Tabelas Principais:
cliente - Informações dos clientes

pet - Pets vinculados a clientes

servico - Catálogo de serviços oferecidos

agendamento - Agendamentos com relacionamentos

categoria e produto (para futuras expansões)

Relacionamentos:
Um cliente pode ter vários pets

Um agendamento pertence a um cliente, um pet e um serviço