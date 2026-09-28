💼 Portfólio / Currículo Web

Página de Portfólio / Currículo Web desenvolvida em HTML5, com foco na utilização de uma estrutura limpa, semântica e organizada.

O projeto apresenta informações pessoais, habilidades, projetos desenvolvidos e um formulário de contato, seguindo os requisitos propostos no desafio.

🎯 Objetivo

Criar uma página web utilizando HTML5 puro, aplicando corretamente elementos semânticos para estruturar um portfólio profissional.

O projeto tem como objetivo demonstrar conhecimentos em:

Estruturação de páginas HTML5

HTML semântico

Links internos com âncoras

Criação e organização de tabelas

Formulários HTML

Utilização de fieldset e legend

Associação entre label e campos de formulário

Inserção e dimensionamento de imagens

Utilização de caracteres especiais em HTML

🖥️ Estrutura do Projeto

A página é dividida nas seguintes seções:

📌 Cabeçalho e Navegação

O cabeçalho contém:

Nome e/ou cargo do desenvolvedor

Menu de navegação

Links para as seções:

Sobre

Projetos

Contato

A navegação utiliza âncoras internas, como:

<a href="#sobre">Sobre</a>
<a href="#projetos">Projetos</a>
<a href="#contato">Contato</a>

👨‍💻 Sobre Mim

A seção apresenta informações sobre o desenvolvedor, incluindo:

Foto de perfil

Texto de apresentação

Lista de habilidades

A imagem de perfil possui as dimensões solicitadas:

<img src="..." width="150" height="150" alt="Foto de perfil">

🚀 Meus Projetos

Os projetos são apresentados em uma tabela HTML contendo quatro colunas:

Projeto	Tecnologias	Status	Link
Projeto 1	HTML, CSS	Concluído	Acessar
Projeto 2	HTML, JavaScript	Em desenvolvimento	Acessar

A tabela utiliza as tags semânticas:

<table>
    <thead>
        <tr>
            <th>Projeto</th>
            <th>Tecnologias</th>
            <th>Status</th>
            <th>Link</th>
        </tr>
    </thead>

    <tbody>
        <!-- Projetos -->
    </tbody>
</table>

📩 Entre em Contato

A seção de contato possui um formulário agrupado através de fieldset e legend.

O formulário contém:

Campo para nome

Campo para e-mail

Menu suspenso para assunto

Campo de texto para mensagem

Botão de envio

Exemplo da estrutura:

<fieldset>
    <legend>Dados do Contato</legend>

    <label for="nome">Nome:</label>
    <input type="text" id="nome" name="nome">

    <label for="email">E-mail:</label>
    <input type="email" id="email" name="email">

    <label for="assunto">Assunto:</label>
    <select id="assunto" name="assunto">
        <option value="duvida">Dúvida</option>
        <option value="projeto">Projeto</option>
        <option value="outro">Outro</option>
    </select>

    <label for="mensagem">Mensagem:</label>
    <textarea id="mensagem" name="mensagem"></textarea>

    <button type="submit">Enviar</button>
</fieldset>

🧱 Tecnologias Utilizadas

HTML5

Elementos semânticos

Formulários HTML

Tabelas HTML

Links e âncoras internas

Não são necessárias bibliotecas ou frameworks externos.

📂 Estrutura de Arquivos

Uma possível organização do projeto:

portfolio/
│
├── index.html
├── README.md
│
└── img/
    └── perfil.jpg

🏆 Requisitos Atendidos

✅ Estrutura HTML5

✅ Uso de <header>

✅ Uso de <nav>

✅ Uso de <main>

✅ Uso de <section>

✅ Seção "Sobre Mim"

✅ Foto de perfil com 150x150px

✅ Lista de habilidades

✅ Tabela de projetos com 4 colunas

✅ <thead> e <tbody>

✅ Links funcionais para os projetos

✅ Formulário de contato

✅ <fieldset> e <legend>

✅ Campos com <label> associado

✅ <select> para assunto

✅ <textarea> para mensagem

✅ Botão de envio

✅ <footer> com informações de contato

✅ Uso do caractere especial &copy;

✅ Navegação através de âncoras internas

▶️ Como Executar

Clone ou baixe este repositório.

Abra a pasta do projeto.

Abra o arquivo index.html em qualquer navegador.

Navegue pelas seções utilizando o menu.

Não é necessário instalar dependências.

📱 Resultado

O projeto apresenta uma página de currículo/portfólio organizada, com navegação entre seções, apresentação profissional, projetos, habilidades e formulário de contato.

📄 Licença

Este projeto foi desenvolvido para fins educacionais e de prática em HTML5.

Desenvolvido com 💻 e 🚀 utilizando HTML5.
