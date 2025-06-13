# 🎴 Blog Preview Card Component | Frontend Mentor

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Responsive](https://img.shields.io/badge/Responsive-Yes-success?style=for-the-badge)
![Frontend Mentor](https://img.shields.io/badge/Frontend%20Mentor-3F54A3?style=for-the-badge)

Uma solução responsiva para o desafio [Blog Preview Card](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS) do Frontend Mentor.

## 📸 Preview
![Visualização do componente](./preview.jpg)

## ✨ Funcionalidades

- **Design totalmente responsivo**
- **Efeitos hover interativos** no título
- **Tags de categoria estilizadas**
- **Sistema de espaçamento automático** entre elementos
- **Semântica HTML** para melhor acessibilidade
- **Variáveis CSS** para fácil manutenção

## 🛠 Tecnologias

```html
<!-- Estrutura HTML -->
<main class="container">
  <div class="card">
    <img src="illustration-article.svg" alt="Ilustração do artigo">
    <p class="categoria">Learning</p>
    <p class="publicacao">Published 21 Dec 2023</p>
    <h1 class="titulo">HTML & CSS foundations</h1>
    <p class="descricao">These languages are the backbone...</p>
    <div class="autor-data">
      <img src="image-avatar.webp" alt="Greg Hooper">
      <h2 class="usuario">Greg Hooper</h2>
    </div>
  </div>
</main>


/* Destaques CSS */
:root {
  --Yellow: hsl(47, 88%, 63%);
  --White: hsl(0, 0%, 100%);
  --cinza2: hsl(0, 0%, 7%);
}

.container {
  max-width: 23em;
  box-shadow: 6px 6px 0px var(--cinza2);
  border-radius: 1rem;
}

.titulo:hover {
  color: var(--Yellow); /* Efeito hover */
}


/* Estrutura do projeto */

blog-card/
├── src/
│   ├── assets/
│   │   ├── Imagens/
│   │   │   ├── illustration-article.svg
│   │   │   └── image-avatar.webp
│   │   └── favicon-32x32.ico
│   └── css/
│       └── style.css
├── index.html
└── README.md

!Desenvolvido por Douglass José (https://github.com/DouglassJose)
# Frontend-Mentor-Blog-Card
