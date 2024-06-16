# SASS

Referência: https://sass-lang.com/

## Introdução a pré-processadores

São ferramentas utilizadas para aumentar a produtividade no desenvolvimento CSS, mantentendo a compatibilidade entre as versões do CSS nos navegadores.

- SASS https://sass-lang.com/
- Stylus https://stylus-lang.com/
- Less https://lesscss.org/
- PostCSS https://postcss.org/

## Preprocessamento

- Processo de interpretação intermediário
- Antes do processamento do navegador
- Prevenção de erros
- Organização
- Reaproveitamento

## Variáveis

- Facilitam a customização e reaproveitamento

## Identação / Hirarquia

- Estruturação de componentes
- Herança
- Evita sobreposição

## Partials

- Modularizar o código
- snippets

## Code Together

1. ter no node instalado
2. instalar o sass (https://sass-lang.com/install):

```bash
npm install -g sass    
```

1. criar projeto ou clonar o repositório
2. criar ou alterar arquivo style.scss
3. rodar o comando para processar o css:

```bash
sass ./scss/style.scss ./css/style.css 
```

1. customizar o projeto
2. salvar alterações
3. comitar no seu repositório
4. enviar o link do repositório para o portal da EBAC
sass ./scss/style.scss ./css/style.css
sass --watch ./scss/style.scss:./css/styles.css
