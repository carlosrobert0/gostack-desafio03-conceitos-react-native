🚀 Sobre o desafio - Conceitos React Native

Nesse desafio, você deve criar uma aplicação para treinar o que você aprendeu até agora no React Native!

Agora você deve continuar desenvolvendo a aplicação que irá armazenar repositórios do seu portfólio, que você já desenvolveu o backend
utilizando o Node.js, e no último desafio em ReactJS.

### Template da aplicação

Para te ajudar nesse desafio, criamos para você um modelo que você deve utilizar como um template do Github.

O template está disponível na seguinte url: **[Acessar Template](https://github.com/Rocketseat/gostack-template-conceitos-react-native)**

### Funcionalidades da aplicação

Agora que você já está com o template clonado, e pronto para continuar, você deve abrir o arquivo **src/App.js**, e completar onde não possui código com o código para atingir os objetivos de cada funcionalidade.

- [x]  **`Listar os repositórios da sua API`**
- **`Listar os repositórios da sua API`**: Deve ser capaz de criar uma lista de todos os repositórios que estão cadastrados na sua API com os campos **title**, **techs** e número de curtidas seguindo o padrão `${repository.likes} curtidas`, apenas alterando o número para ser dinâmico.
Listando com o useEffect(() ⇒ {}, []), useState, e mostrando o setRepositories utilizando o conceito de estado e imutabilidade
- [x]  **`Curtir um repositório listado da API`**
- **`Curtir um repositório listado da API`**: Deve ser capaz de curtir um item na sua API através de um botão com o texto **Curtir** e deve atualizar o número de likes na listagem no mobile.

    Curtindo com um metodo post na rota do like e apenas alterando atualizando o valor de likedRepository
    
    ![gif](https://user-images.githubusercontent.com/45858897/82743432-b860ad00-9d41-11ea-8e6e-a4b85c2530b4.gif)
