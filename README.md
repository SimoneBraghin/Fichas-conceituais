# Fichas Conceituais — Índice

Site estático que lista automaticamente os arquivos `.html` de uma pasta do repositório e os abre em um visualizador embutido (iframe), sem precisar editar código a cada novo arquivo adicionado.

## Como funciona

O `index.html` consulta a **API do GitHub** (`api.github.com/repos/.../contents/PASTA`) toda vez que a página é carregada. 

Ao clicar num item da lista, o arquivo correspondente abre dentro de um iframe, com um botão para voltar à lista.

## Estrutura de pastas

```
/
├── index.html              ← página principal (fica na raiz)
└── fichas-conceituais/      ← pasta com os arquivos .html das fichas
    ├── arquivo1.html
    └── arquivo2.html
```
