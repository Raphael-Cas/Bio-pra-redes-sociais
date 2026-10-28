# Bio-pra-redes-sociais

# Link na bio | Raphael Almeida Castro

Página de links no estilo Linktree para usar na bio das redes sociais. Reúne Instagram, LinkedIn e GitHub, o curso atual e os focos de aprendizado

## Recursos

- Foto de perfil circular com anel azul
- Banners para Instagram, LinkedIn e GitHub
- Seções de curso atual e focos de aprendizado
- Efeito de vidro (`backdrop-filter`) sobre fundo com manchas de azul
- Layout responsivo, pensado para celular
- Sem frameworks nem dependências: só HTML, CSS e JavaScript

## Estrutura

```
.
├── index.html
├── style.css
├── script.js
├── assets/
│   └── foto-perfil.jpg
└── README.md
```

## Como personalizar

- **Textos e links:** edite o `index.html`. Cada banner é um bloco `<a class="glass link">` com o `href` da rede.
- **Foto:** troque `assets/foto-perfil.jpg` por outra imagem quadrada, de preferência com 400 px ou mais.
- **Cores:** no `style.css`, ajuste as manchas de fundo (`.o1`, `.o2`, `.o3`), o anel do avatar (`.avatar`) e as variáveis em `:root`.
- **Intensidade do vidro:** altere o valor de `blur()` na classe `.glass`.


## Autor

**Raphael Almeida Castro**
[LinkedIn](https://www.linkedin.com/in/raphael-almeida-castro/) | [Instagram](https://www.instagram.com/1raphael.castro/) | [GitHub](https://github.com/Raphael-Cas)
