# Landing page · Zenvia Grande Minas

Projeto estático (HTML, CSS e JS puros). Não precisa instalar nada.

## Como abrir no VS Code

1. `Arquivo > Abrir Pasta…` e selecione a pasta `zenvia-grande-minas`.
2. Aceite a sugestão de instalar a extensão **Live Server**.
3. Clique com o botão direito em `index.html` e escolha **Open with Live Server**.

> Abra sempre por um servidor (Live Server) ou por um site publicado.
> O webchat da Zenvia pode não carregar corretamente abrindo o arquivo
> direto do disco (`file://`).

## Estrutura

```
zenvia-grande-minas/
├── index.html        página e script do webchat (no final do <body>)
├── css/style.css     estilos e cores (variáveis em :root)
├── js/main.js        ano do rodapé
├── assets/favicon.svg
└── .vscode/          recomendações para o VS Code
```

## Trocar o token do webchat

No final do `index.html`, altere só o texto entre aspas:

```js
new ZenviaChat('SEU_TOKEN_AQUI')
```

## O que personalizar

- Textos de contato (e-mail, telefone, horário) na seção `#contato`.
- Cores: variáveis `--ink`, `--teal` e `--clay` no início de `css/style.css`.
- Textos de apresentação: são exemplos. Ajuste ao que a Zenvia Grande Minas realmente oferece.
