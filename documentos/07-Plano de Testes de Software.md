# Plano de Testes de Software

<span style="color:red">Pré-requisitos: <a href="https://github.com/ICEI-PUC-Minas-PMV-ADS/ads-e1-exemplo-vida-de-estudante/tree/main/documentos/02-Especificação%20do%20Projeto.md"> Especificação do Projeto</a></span>, <a href="https://github.com/ICEI-PUC-Minas-PMV-ADS/ads-e1-exemplo-vida-de-estudante/tree/main/documentos/04-Projeto%20de%20Interface.md"> Projeto de Interface</a>

Os requisitos para realização dos testes de software são:
<ul><li>Site publicado na internet;</li>
<li>Navegador da internet: Chrome, Firefox ou Edge.</li>
</ul>

Os testes funcionais a serem realizados na aplicação são descritos a seguir.

|Caso de Teste    | CT-01: Verificar o funcionamento dos links da página Home |
|:---|:---|
| Requisitos Associados | <ul><li>RF-001:	O site deve permitir ao usuário cadastrar uma conta.</li><li>RF-002:	O site deve permitir ao usuário fazer o login da sua conta.</li><li>RF-005:	O site deve permitir ao usuário disponibilizar informações das disciplinas de tutoria e suas informações para contato.</li><li>RF-007:	O site deve permitir ao usuário visualizar os detalhes do livro.</li></ul>|
| Objetivo do Teste | Verificar se os links da página Home estão encaminhando para as respectivas páginas corretamente  |
| Passos | <ol><li>Acessar o navegador.</li><li>Informar o endereço do site.</li><li>Visualizar a página Home.</li><li>Clicar nos links da página Home.</li></ol> |
| Critérios de êxito | Todos os links da página Home devem encaminhar os usuários para as páginas descritas.  |
| Responsável pela elaborar do caso de Teste | Maria |


|Caso de Teste    | CT-02: Verificar o funcionamento do filtro de pesquisa |
|:---|:---|
| Requisitos Associados | <ul><li>RF-003:	O site deve oferecer uma funcionalidade de filtro/pesquisa para permitir ao usuário localizar livros e disciplinas das tutorias disponíveis.</li></ul>|
| Objetivo do Teste | Verificar se o filtro de pesquisa está recuperando os dados inseridos pelo usuário  |
| Passos | <ol><li>Acessar o navegador.</li><li>Informar o endereço do site.</li><li>Visualizar a página Home.</li><li>Clicar na página Livros.</li><li>Digitar no filtro de pesquisa algum dado presente na página Livros e verificar se o resultado é exibido  página.</li></ol> |
| Critérios de êxito | Os dados inseridos no filtro de pesquisa devem mostrar o livro onde há o dado informado.  |
| Responsável pela elaborar do caso de Teste | Maria |

|Caso de Teste    | CT-03: Verificar detalhes dos livros |
|:---|:---|
| Requisitos Associados | <ul><li>RF-006:	O site deve apresentar, para cada livro, uma imagem correspondente à capa.</li><li>RF-007:	O site deve permitir ao usuário visualizar os detalhes do livro.</li></ul>|
| Objetivo do Teste | Verificar se todas as informações referentes aos livros estão disponíveis na página Livros  |
| Passos | <ol><li>Acessar o navegador.</li><li>Informar o endereço do site.</li><li>Visualizar a página Home.</li><li>Clicar na página Livros.</li><li>Visualizar as informações referentes aos livros disponíveis na página.</li></ol> |
| Critérios de êxito | Todas as informações, incluindo imagens das capas, referentes aos livros estão disponíveis na página Livros.  |
| Responsável pela elaborar do caso de Teste | João |

|Caso de Teste    | CT-04: Verificar o cadastro de usuários |
|:---|:---|
| Requisitos Associados | <ul><li>O site deve permitir ao usuário cadastrar uma conta.</li></ul>|
| Objetivo do Teste | Verificar se o cadastro está sendo feito corretamente. |
| Passos | <ol><li>Acessar o navegador.</li><li>Informar o endereço do site.</li><li>Visualizar a página Home.</li><li> Clicar em "Cadastre-se", no Menu.</li><li>Preencher o formulário e clicar em “Cadastrar”.</li></ol> |
| Critérios de êxito | Deve ocorrer uma validação das informações fornecidas pelo usuário, e ao clicar em "Cadastrar", deve aparecer a mensagem "Usuário cadastrado com sucesso".  |
| Responsável pela elaborar do caso de Teste | Silvia |

|Caso de Teste    | CT-05: Verificar o login de usuários |
|:---|:---|
| Requisitos Associados | <ul><li>RF-002: O site deve permitir ao usuário fazer o login da sua conta.</li></ul>|
| Objetivo do Teste | Verificar se o login está sendo feito corretamente. |
| Passos | <ol><li>Acessar o navegador.</li><li>Informar o endereço do site.</li><li>Visualizar a página Home.</li><li>Clicar em “Entrar”, no menu.</li><li>Preencher seus dados e clicar em “Entrar”.</li></ol> |
| Critérios de êxito | Após o login, o usuário deverá ser redirecionado para a sua página de perfil.  |
| Responsável pela elaborar do caso de Teste | Maria |

|Caso de Teste    | CT-06: Verificar o cadastro de livros |
|:---|:---|
| Requisitos Associados | <ul><li>RF-004	O site deve permitir ao usuário fazer o cadastro de livros.</li></ul>|
| Objetivo do Teste | Verificar se o cadastro de livros está sendo feito corretamente. |
| Passos | <ol><li>Acessar o navegador.</li><li>Informar o endereço do site.</li><li>Visualizar a página Home.</li><li>Clicar em “Entrar”, no menu.</li><li>Preencher seus dados e clicar em “Entrar”.</li><li>Visualizar a página Perfil.</li><li>Clicar em “Cadastro de livros”, no menu.</li><li>Visualizar a página Cadastro de Livros.</li><li>Inserir as informações sobre o livro.</li><li>Clicar em “Cadastrar”.</li></ol></li></ol> |
| Critérios de êxito | Deve ocorrer uma validação das informações fornecidas pelo usuário, e ao clicar em "Cadastrar", deve aparecer a mensagem "Livro cadastrado com sucesso".  |
| Responsável pela elaborar do caso de Teste | João |

|Caso de Teste    | CT-07: Verificar o cadastro de tutores |
|:---|:---|
| Requisitos Associados | <ul><li>RF-005	O site deve permitir ao usuário disponibilizar informações das disciplinas de tutoria e suas informações para contato.</li></ul>|
| Objetivo do Teste | Verificar se o cadastro de tutores está sendo feito corretamente. |
| Passos | <ol><li>Acessar o navegador.</li><li>Informar o endereço do site.</li><li>Visualizar a página Home.</li><li>Clicar em “Entrar”, no menu.</li><li>Preencher seus dados e clicar em “Entrar”.</li><li>Visualizar a página Perfil.</li><li>Clicar em “Cadastro de tutores”, no menu.</li><li>Visualizar a página Cadastro de Tutores.</li><li>Inserir as informações sobre o tutor.</li><li>Clicar em “Cadastrar”.</li></ol> |
| Critérios de êxito | Deve ocorrer uma validação das informações fornecidas pelo usuário, e ao clicar em "Cadastrar", deve aparecer a mensagem "Tutoria cadastrada com sucesso".  |
| Responsável pela elaborar do caso de Teste | Beatriz |

|Caso de Teste    | CT-08: Verificar a página de Tutores |
|:---|:---|
| Requisitos Associados | <ul><li>RF-008	O site deve permitir ao usuário visualizar os detalhes dos tutores.</li></ul>|
| Objetivo do Teste | Verificar os detalhes dos Tutores e visualizar seus respectivos perfis. |
| Passos | <ol><li>Acessar o navegador.</li><li>Informar o endereço do site.</li><li>Visualizar a página Home.</li><li>Clicar em “Tutores”, no menu.</li><li>Visualizar a página "Tutores".</li><li>Na página "Tutores", é possível visualizar os perfis com foto e informações dos tutores, além da barra de pesquisa acima dos perfis.</li></ul></ol> |
| Critérios de êxito | Deve ser possível visualizar todos os perfis de Tutores, com suas respectivas fotos e informações, além da visualização da barra de pesquisa acima dos perfis.  |
| Responsável pela elaborar do caso de Teste | Pedro |

|Caso de Teste    | CT-09: Verificar a página de perfil de usuários cadastrados |
|:---|:---|
| Requisitos Associados | <ul><li>RF-009	O site deve permitir ao usuário verificar as informações registradas no cadastro na página Perfil, após fazer seu login.</li></ul>|
| Objetivo do Teste | Verificar se a página Perfil está apresentando as informações cadastradas pelo usuário corretamente. |
| Passos | <ol><li>Acessar o navegador.</li><li>Informar o endereço do site.</li><li>Visualizar a página Home.</li><li>Clicar em "Cadastre-se", no Menu.</li><li>Preencher o formulário e clicar em “Cadastrar”.</li><li>Visualizar a página Login.</li><li>Preencher seus dados e clicar em “Entrar”.</li><li>Visualizar a página Perfil.</li></ol> |
| Critérios de êxito | As informações registradas pelo usuário no momento do cadastro devem estar disponibilizadas na página Perfil.  |
| Responsável pela elaborar do caso de Teste | Silvia |


