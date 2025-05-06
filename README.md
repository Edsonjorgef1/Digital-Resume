# Digital Resume - Edson Jorge Francisco

## Estrutura do Projeto

```
.
├── assets/
│   ├── images/
│   │   └── projects/
│   │       ├── fams.jpg
│   │       ├── consultare.jpg
│   │       ├── network1.jpg
│   │       ├── djobar.jpg
│   │       ├── team.jpg
│   │       └── digital.jpg
│   └── Edson_Francisco-Resume.pdf
├── index.html
├── projects.html
├── translations.js
└── README.md
```

## Adicionando Novos Projetos

Para adicionar um novo projeto, siga estas etapas:

1. Adicione a imagem do projeto na pasta `assets/images/projects/`
2. Atualize o arquivo `projects.html` com o novo projeto na seção apropriada
3. Certifique-se de que a imagem tenha as seguintes características:
   - Formato: JPG ou PNG
   - Dimensões recomendadas: 800x600 pixels
   - Tamanho máximo: 500KB
   - Nome do arquivo: em minúsculas, sem espaços, usando hífen como separador

## Estrutura de um Projeto

Cada projeto deve seguir este formato:

```html
<div class="swiper-slide">
    <img src="assets/images/projects/nome-do-projeto.jpg" alt="Nome do Projeto" class="project-image">
    <div class="project-content">
        <h3 class="project-title">Nome do Projeto</h3>
        <p class="project-description">Descrição do projeto...</p>
        <div class="project-links">
            <a href="URL" class="project-link" target="_blank">Link 1</a>
            <a href="URL" class="project-link" target="_blank">Link 2</a>
        </div>
    </div>
</div>
```

## Categorias de Projetos

Os projetos estão organizados nas seguintes categorias:

1. Projetos de Tecnologia
2. Implementações de Redes
3. Projetos Freelance
4. Liderança e Treinamento
5. Casos de Uso de Transformação Digital

## Desenvolvimento

Para desenvolver localmente:

1. Clone o repositório
2. Abra o arquivo `index.html` em seu navegador
3. Para visualizar a página de projetos, clique em "Ver Projetos"

## Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript
- Swiper.js (para carrosséis)
- Google Fonts 