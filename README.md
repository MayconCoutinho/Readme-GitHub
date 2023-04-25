<p align="center">
  <img src="https://user-images.githubusercontent.com/60453269/233516295-acd066c4-dc18-404d-b479-48db92859de8.png" alt="Logo" width="200" height="200" />
</p>

<h1 align="center"> Readme </h1>

<a id="Sumário"></a>


<p align="center">
  <b> Readme Legal </b></br>
  <sub> Uma readme bonita, pratica e eficiente para usar em todos projeto e padronizar as readmes.
  <sub>
</p>


[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#table-of-contents)

<p align="center">
  <a href="#Introdução"> 🧩 Introdução </a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#Resultados"> 🚀 Resultados</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#Dependências"> 🧪 Dependências</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#Ideias">💡 Possíveis Melhorias </a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#Creditos"> 🏆 Créditos </a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</p>
 
<br/>


### 🚧 PROJETO EM ANDAMENTO 🚧

<br/>

<a id="Introdução"></a>
## 🧩 Introdução 

  ***⠀⠀⠀⠀Bem-vindo ao meu projeto de padronização de READMEs no GitHub! Ao longo dos anos, percebi que muitos dos meus projetos no GitHub tinham READMEs inconsistentes e mal formatados. Para resolver esse problema, desenvolvi um modelo de README que atende a todos os requisitos necessários e padroniza a apresentação de informações importantes.***

<br/>


<a id="Resultados"></a>
## 🚀 Resultados 
  > Todos os resultados foram alcançados com sucesso. De modo geral são esses os resultados de cada requisição. 

<br/> 

## Front-end

<br />   

  ### ***⠀⠀⠀⠀⭐ Basta arrastar a imagem desseja para a readme copiar a url e substituir a imagem antiga pela nova***

<br />   


⭐ Login | ⭐ Registro | ⭐ Feed | ⭐ Menu |
|---|---|---|---|
![HomePagePhone](https://user-images.githubusercontent.com/60453269/216195912-079d82a0-0ab7-49f3-aa71-414a60b2f767.png) | ![DetalhesPhone](https://user-images.githubusercontent.com/60453269/216195909-5373005a-2e93-488f-959d-619260fc76a4.png)| ![DetalhesPhone](https://user-images.githubusercontent.com/60453269/216195906-bb69cd37-12bb-4deb-aa7f-bbe9c3873bef.png)| ![DetalhesPhone](https://user-images.githubusercontent.com/60453269/216195904-c6210dc9-2323-474b-8d70-8cda655f1ccc.png)
  
  
[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#table-of-contents)


### 💻 Desktop 
  
 ⭐ Login | ⭐ Registro | ⭐ Feed |
|---|---|---|
![HomePage](https://user-images.githubusercontent.com/60453269/216196816-732e76cb-ad41-499f-80fd-2cfa04f52ad5.png) | ![Detalhes](https://user-images.githubusercontent.com/60453269/216196824-69b5b6d2-cce1-4b08-9b03-ff5b5fcb8a12.png) | ![Detalhes](https://user-images.githubusercontent.com/60453269/216196822-5008a618-bf21-4bb3-8c0e-579131d771fa.png)


<br/>

## Back-end
>
  
<br/>

### ***⠀⠀⠀⠀⭐ Caso seu projeto seja um backend Aqui tem uma boa forma de demostra como que faz as requisições e oque retorna***

  
### 🎯 PEGAR TODOS OS DADOS DE UM USER ATRAVES DO ID 
  
### ```GET``` 
```URL
 http://localhost:3003/users/perfil
 
  {
    "authorization" : "aa670248-dbd3-402c-a824-c52646fc1196"
  }

```
  
```JSON
{
    "user": {
        "id": "62f7daf9-d523-4b2d-b0cd-94039c5c4082",
        "imgPerfil": "https://ovicio.com.br/wp-content/uploads/2020/09/20200916-d9ffbeb5e7862a243ce822bb89d12b66_750x750-555x555.jpg",
        "name": "Toshinori",
        "rgb": [
            57,
            82,
            65
        ]
    },
    "post": [
        {
            "img": "https://firebasestorage.googleapis.com/v0/b/rede-social-203d0.appspot.com/o/feed%2F1676760852632.webp?alt=media&token",
            "texto": "Outro",
            "rgb": [
                57,
                82,
                65
            ],
            "id": "322ea0a3-1657-4ad1-8f75-4a95a2832394",
            "date": "18/02/2023, 19:54:14",
            "idUserLike": null,
            "imgPerfil": "https://ovicio.com.br/wp-content/uploads/2020/09/20200916-d9ffbeb5e7862a243ce822bb89d12b66_750x750-555x555.jpg",
            "name": "Toshinori",
            "idUser": "62f7daf9-d523-4b2d-b0cd-94039c5c4082"
        },...
        }
```
  
<br /> 

### 🎯 REGISTRA UM USUÁRIO NO BANCO DE DADOS.
  
### ```POST``` 

```URL

http://localhost:3003/users/register

```
  
```JSON
{
    "name": "teste",
    "email": "teste@gmail.com",
    "password": "123456"
}

```

<br /> 

### 🎯 FAZ LOGIN
  
### ```POST``` 

```URL

http://localhost:3003/users/login

```
  
```JSON
{
    "email": "teste@gmail.com",
    "password": "123456"
}

```

<br /> 


### 🎯 PEGA TODOS OS POSTS
  
### ```GET``` 

```URL
http://localhost:3003/posts
```
  
```JSON
[
  {
    "id": "ed66e018-666f-40e9-a16f-510848491842",
    "date": "18/02/2023, 19:56:17",
    "img": "https://firebasestorage.googleapis.com/v0/b/rede-social-203d0.appspot.com/o/feed%2F1676760975303.jpg?alt=media&token",
    "idUser": "f27d54fd-2edb-4653-af60-bb311a00a5b3",
    "name": "Asui",
    "idUserLike": null,
    "rgb": [
      73,
      168,
      126
    ],
    "imgPerfil": "https://i.pinimg.com/originals/3a/2e/9a/3a2e9ab1fbf688f75f9227cc3c66951a.jpg",
    "texto": "E vai indo"
  },...
  ]

```

<br /> 

### 🎯 FAZ LOGIN
  
### ```POST``` 

```URL
http://localhost:3003/posts
```
  
```JSON
{
    "idUser": "f27d54fd-2edb-4653-af60-bb311a00a5b3",
    "texto": "olha eu kkkkk",
    "img": "Tem como mandar a imagem do pc ou mandar url da imagem, por padrão só tem como manda do pc"
}
```

<br/>

<a href="#Sumário"> 📖 Volta ao Sumário </a>

<br /> 

<a id="Dependências"></a>
## 🧪 Dependências
> Requisitos para rotar o codigo...

<br/>

## `📖 Instalação` 
  
  
 <br /> 

> Caso tenha Git basta da git clone, caso não tenha baixe o projeto completo em dowlon

```BASH
git clone https://github.com/MayconCoutinho/Readme-GitHub
```

<br /> 

> Caso já tenha o Node em sua maquina basta instalar o projeto com npm i

```BASH
npm i 
```

<br /> 

## `📖 Scripts` 

```JSON
  "scripts": {
    "dev": "next dev",
    "build": "next build",
    "start": "next start",
    "lint": "next lint",
    "prepare": "husky install"
  }

```

<br/>

## `📖 Dependencies` 

```JSON
  "dependencies": {
    "axios": "^0.27.2",
    "next": "12.2.5",
    "react": "18.2.0",
    "react-dom": "18.2.0",
    "sass": "^1.54.8"
  }

```

<br /> 

## `📖 devDependencies` 


```JSON
  "devDependencies": {
    "@commitlint/cli": "^17.6.1",
    "@commitlint/config-conventional": "^17.6.1",
    "eslint": "^8.38.0",
    "eslint-config-airbnb": "^19.0.4",
    "eslint-config-google": "^0.14.0",
    "eslint-config-next": "12.2.5",
    "eslint-config-prettier": "^8.8.0",
    "eslint-plugin-import": "^2.27.5",
    "eslint-plugin-jsx-a11y": "^6.7.1",
    "eslint-plugin-prettier": "^4.2.1",
    "eslint-plugin-react": "^7.32.2",
    "eslint-plugin-react-hooks": "^4.6.0",
    "husky": "^8.0.3",
    "prettier": "^2.8.7"
  }

```
<br/>

<a href="#Sumário"> 📖 Volta ao Sumário </a>

<br /> 

<a id="Ideias"></a>
## 💡 Possíveis Melhoras
> Possíveis melhorias no código e no projeto, caso queira voltar e melhorá lo.

<br /> 

- [ ] ***- Testa todo o código.*** 
- [ ] ***- Pesquisar o perfil com nome*** 
- [ ] ***- *** 
- [x] ***- *** 

<br/>

<a href="#Sumário"> 📖 Volta ao Sumário </a>

<br /> 

<a id="Creditos"></a>
## 🏆 Créditos
> Todo o projeto foi feito por...
  
<br /> 

<div > 

| [<img src="https://user-images.githubusercontent.com/60453269/217899761-dc2d4e4b-3336-419d-9076-79304290aa0a.png" width=300><br><sub> Maycon Coutinho </sub>](https://www.linkedin.com/in/maycon-coutinho/) | ***Hello 😃 Se você chegou até aqui, acredito que gostou do meu projeto, nesse caso temos algo em comum, sendo assim que tal conversamos um pouco? Meu chama no linkedin 😁*** | 
|---|---|

</div> 
  
<br /> 

