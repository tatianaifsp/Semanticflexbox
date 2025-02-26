# Logística Express - Estrutura do Site 

🎯 Objetivos da Aula 

✅ Compreender o que são tags semânticas em HTML.

✅ Aprender como usá-las para estruturar o layout de uma página web.

✅ Entender o conceito e a aplicação do Flexbox no CSS.

✅ Implementar exemplos práticos de tags semânticas com Flexbox.


## Descrição
Este repositório contém o código-fonte de um site responsivo para a empresa **Logística Express**. O objetivo é apresentar os serviços de logística oferecidos, depoimentos de clientes, FAQs e um blog.

(https://tatianaifsp.github.io/Semanticflexbox/)

## Tecnologias Utilizadas
- **HTML5**: Para estruturação semântica da página.
- **CSS3 (Flexbox)**: Para estilização e layout responsivo.

## Estrutura do Projeto
```
/
|-- index.html
|-- style.css
|-- /img (Imagens utilizadas)
```

## Estrutura Semântica do HTML
O site foi estruturado usando **tags semânticas**, seguindo boas práticas de acessibilidade e SEO:

| Tag | Função |
|------|---------|
| `<header>` | Contém o logotipo e o menu de navegação |
| `<nav>` | Contém os links do menu de navegação |
| `<main>` | Engloba o conteúdo principal da página |
| `<section>` | Organiza diferentes seções como serviços, depoimentos, FAQ e blog |
| `<article>` | Usado para artigos do blog |
| `<aside>` | Barra lateral para informações adicionais |
| `<footer>` | Rodapé com informações de contato |

## Uso do Flexbox
O CSS utiliza **Flexbox** para alinhar e distribuir elementos responsivamente. Alguns exemplos:
```css
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.cards {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
}
```

## Como Rodar o Projeto
1. Clone este repositório:
   ```sh
   git clone https://github.com/seu-usuario/logistica-express.git
   ```
2. Abra o arquivo `index.html` no navegador.

## Melhorias Futuras
- Adicionar animações CSS.
- Implementar um formulário de contato funcional com JavaScript.
- Melhorar a acessibilidade com atributos `aria`.

---

Este projeto é um exemplo de boas práticas de **HTML semântico** e **CSS moderno**. Sinta-se à vontade para contribuir! 🚀

