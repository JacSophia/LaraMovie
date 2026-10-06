# LaraMovie

## Objetivos
o sistema vai escolher um filme através de uma roleta, pode se fazer roletas com filtros baseados no seu gosto do usuário. Além de ajudar os usuários com listas de filmes e compartilhar suas opiniões e resenhas sobre diversos filmes.

### Stack tecnológico
Backend:php estruturado com sessão nativa 
Banco de dados:  MYSQL (POD para segurança)
frontend: HTML5, CSS, Tailwind CSS

#### Regras de negócio (CORE)
Tratar senhas de usuários com hash bcript 

Opção de lista, onde encontraremos uma lista de filmes separada por gênero do banco de dados.
Clicar no botão: Lista	
	Aparecer uma Lista com os filmes do Banco de Dados.
Clicar no filme	
	Abre ficha técnica do filme

Opção de roleta, onde encontramos uma roleta com todos os filmes e podendo ser filtrada por gênero. Quando utilizar ela o filme será roletado e aparecerá como ganhador, retirando-o da roleta.
Clicar no botão: Rodar Filme	
	Aparece a roleta com todas as opções e um botão de filtrar a roleta.
Clicar no botão de Filtro:	
	Filtrar por gênero, ano, diretor, série, filme...
Clicar no botão: Girar
	Sorteia um filme ou série de forma aleatória seguindo os critérios estabelecidos.

Opção de perfil, onde encontramos um compilado de informações sobre o usuário.
Clicar no botão: Perfil	
	Ao clicar, aparecerá um compilado de informações sobre o usuário, como nome, foto, filmes assistidos, resenhas, lista de favoritos, comentários, amigos e lista de desejos.
Clicar em Amigos	
	Abre lista de amigos e o sistema de adicionar amigo pelo usuário.
Clicar em um Amigo em especifico	
	Aparece o perfil dele
Clicar em Favoritos	
	Lista de filmes que assistiu e gostou
Clicar em Resenha	
	Aparece resenhas sobre filmes que o usuário assistiu junto de um botão de Adicionar Resenha.
Clicar em Adicionar Resenha	
	Abrir uma página que permite o usuário de expor sua opinião sobre um filme.
