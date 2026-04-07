# Fundo Mágico

Projeto web frontend que permite ao usuário descrever um background e gerar automaticamente o código HTML/CSS correspondente usando uma API externa.

## Sobre

O `Fundo Mágico` é uma interface interativa construída com HTML, CSS e JavaScript. O usuário digita uma descrição do background desejado, o app envia essa descrição para uma API do n8n e exibe o resultado em tempo real em um preview visual, além de mostrar o HTML e o CSS gerados.

## Tecnologias

- HTML5
- CSS3
- JavaScript (DOM, eventos, fetch, async/await)
- Integração com API externa (n8n)

## Funcionalidades

- Formulário de entrada para descrição do background
- Requisição `POST` para API externa
- Exibição de carregamento durante a geração
- Renderização do preview do background gerado
- Exibição do código HTML e CSS gerados
- Layout responsivo para telas menores

## Estrutura do projeto

- `index.html` – estrutura da página
- `src/css/reset.css` – reset de estilos
- `src/css/estilos.css` – estilos principais da interface
- `src/css/responsivo.css` – ajustes para responsividade
- `src/js/index.js` – lógica de interação e requisição à API

## Uso

1. Abra `index.html` em um navegador.
2. Digite a descrição do background desejado.
3. Clique em "Gerar Background Mágico".
4. Veja o preview e o código HTML/CSS retornados.

## Observação

A aplicação depende de uma API externa configurada via n8n para gerar o conteúdo dinâmico. Se a API não estiver disponível, o recurso de geração de fundos não funcionará.
