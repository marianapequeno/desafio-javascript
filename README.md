# Desafio do módulo final de JavaScript da <a href="https://reprograma.com.br/">{reprograma}</a>.

## Desafio de API - Github Search

:construction: *Não finalizado*

Neste projeto, foi criada uma aplicação de pesquisa que usa a API GitHub para recuperar informações do usuário quando um nome de usuário válido é inserido. Ele deve exibir avatar, nome de usuário, contagem de seguidores, contagem de repositórios.

# Links

- [Layout do projeto](https://www.figma.com/file/UjuUSqwVpb7OtbWysQZffj/github-search?node-id=0%3A1)
- [Documentação - API GitHub](https://docs.github.com/pt/rest)


## Fase 1
- [ ] Criar o layout seguindo o Figma disponibilizado.
- [ ] O Input recebe o username de um usuário. Quando clicar no botão de pesquisa, caso o usuário exista dentro da base de dados da API, a aplicação deve mostrar os dados desta forma: 
   - Exibir o avatar.
   - Nome do usuário.
   - Username
   - Bio
   - Total de seguidores
   - Total de repositórios

**Exemplo**: 
<p align="center">
  <img src="./images/profile.png" />
</p>

- [ ] Validar campo de texto para não entrar texto vazio
- [ ] Limpar campo de texto depois que inserir o nome de usuário
- [ ] O usuário deve receber um alerta se o nome de usuário não for válido 
  

**Exemplo**: 
<p align="center">
  <img src="./images/not-found.png" />
</p>



## Fase 2 - Extra

- [ ] Exibir todos repositórios do usuário, com as informações:
    - Titulo
    - Descrição
    - Linguagem utilizada
    - Total de estrelas
- [ ] A página deve exibir um alerta caso o usuário pesquisado não tenha repositórios públicos  

**Exemplo**: 
<p align="center">
  <img src="./images/profile-repos.png" />
</p>
<p align="center">
  <img src="./images/repos-nao-encontrado.png" />
</p>

## Como vou entregar o projeto?
- Por Pull Request. 


