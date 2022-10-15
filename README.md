# [git-fav](https://antoniodebrito.github.io/git-fav/) <= acesse a página online aqui 
Desafio proposto pela [Rocketseat](https://shrinke.me/rocketseat) no seu treinamento Explorer, onde foi criado uma página para listar os usuários favoritos Utilizando a [api pública do GitHub](api.github.com/users/).
---
Funcionalidades:
- Buscar pelo login de usuário no Github
- Botão para adicionar novo Favorito
- Tabela para exibir os favoritos
  - Foto
  - Nome de usuário
  - Login do usuário
  - Quantidade de repositórios
  - Quantidade de seguidores
- Botão para remover usuário

---
Arquitetura CSS
 - somente o styles.css é chamado no HTML, pois ele importar todos os demais estilos, mantendo o head do HTML limpo
 - root.css contém as variáveis como alguns códigos principais para toda a página
 - Estrutura de pastas com conceitos de **atomic css**
 - normalize e reset css para padronizar estilos em diferente navegadores 
 - Alguns conceitos de BEM para nomear classe e dividir funções do arquivo
 

---
JavaScript:  
Modulos para organizar melhor o código:
- **mains.js** chama a classe de visualização
- **favorites.js** possuí duas classes, a Favorites a lógica da aplicação e a FavoritesView cria a visualição dos dados
- **githubUser.js** faz a chamada dos dados na API do GitHub; 

Orientação a objetos em JavaScript  
LocalStorage para pesistir dados no navegador  
Filter, para carregar os usuários corretamente   


---

![image](https://user-images.githubusercontent.com/73064351/195961467-999668e8-3567-4267-9c29-03929391c754.png)


