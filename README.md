<h1 align='center'>Criando o Relacionamento do Banco para um Hospital</h1>

<h3>🔹Parte 1 - Diagrama Entidade Relacionamento</h3>
<p>
*O hospital necessita de um sistema para sua área clínica que ajude a controlar consultas realizadas. Os médicos podem ser generalistas, especialistas ou residentes e têm seus dados pessoais cadastrados em planilhas digitais. Cada médico pode ter uma ou mais especialidades, que podem ser pediatria, clínica geral, gastroenterologia e dermatologia. Alguns registros antigos ainda estão em formulário de papel, mas será necessário incluir esses dados no novo sistema.*

*Os pacientes também precisam de cadastro, contendo dados pessoais (nome, data de nascimento, endereço, telefone e e-mail), documentos (CPF e RG) e convênio. Para cada convênio, são registrados nome, CNPJ e tempo de carência.*

*As consultas também têm sido registradas em planilhas, com data e hora de realização, médico responsável, paciente, valor da consulta ou nome do convênio, com o número da carteira. Também é necessário indicar na consulta qual a especialidade buscada pelo paciente.*

*Deseja-se ainda informatizar a receita do médico, de maneira que, no encerramento da consulta, ele possa registrar os medicamentos receitados, a quantidade e as instruções de uso. A partir disso, espera-se que o sistema imprima um relatório da receita ao paciente ou permita sua visualização via internet.*
</p>
<br>

![DER - Inicio](https://github.com/KaiqueTeruel/Banco-de-Dados-Hospital/assets/82835307/e59fd9f4-609d-42d3-b2c8-b583a8e0dfed)

<hr>
<h3>🔹Parte 2 - Diagrama Entidade Relacionamento</h3>
<p>
*No hospital, as internações têm sido registradas por meio de formulários eletrônicos que gravam os dados em arquivos.*

*As internações precisam ser vinculadas a quartos, com a numeração e o tipo.*

*Cada tipo de quarto tem sua descrição e o seu valor diário (a princípio, o hospital trabalha com apartamentos, quartos duplos e enfermaria).*

*Também é necessário controlar quais profissionais de enfermaria estarão responsáveis por acompanhar o paciente durante sua internação. Para cada enfermeiro(a), é necessário nome, CPF e registro no conselho de enfermagem (CRE).*

Por último, crie um script SQL para a geração do banco de dados

![DER - Final](https://github.com/KaiqueTeruel/Banco-de-Dados-Hospital/assets/82835307/f3436920-4b08-41cb-a0b2-4232aefc90cd)

<hr>
