# BeMor Notes

**BeMor Notes** é uma aplicação web para gerenciamento de anotações simples, com funcionalidades como busca, fixação, duplicação e exportação de notas em formato CSV. O projeto é desenvolvido utilizando HTML, CSS e JavaScript puro, com suporte a ícones do Bootstrap Icons.

## Funcionalidades

- Adicionar notas com texto livre
- Editar o conteúdo das notas diretamente
- Fixar/desfixar notas importantes
- Duplicar notas existentes
- Buscar notas pelo conteúdo
- Exportar todas as notas em formato `.csv`
- Interface responsiva

## Tecnologias Utilizadas

- **HTML5**  
- **CSS3**  
- **JavaScript (ES6+)**  
- **Bootstrap Icons**  
- **LocalStorage** (para armazenamento persistente das notas no navegador)

## Como Usar

1. Clone ou baixe este repositório:
   ```bash
   git clone https://github.com/seu-usuario/bemor-notes.git
   ```
2. Abra o arquivo `index.html` em um navegador moderno.
3. Comece a adicionar suas anotações.

## Estrutura do Projeto

```
bemor-notes/
│
├── assets/
│   ├── js/
│   │   └── script.js
│   └── styles/
│       └── styles.css
│
└── index.html
```

## Recursos

- As notas são armazenadas localmente no navegador usando `localStorage`.
- O campo de busca permite filtrar rapidamente notas com base em seu conteúdo.
- O botão "Exportar CSV" gera um arquivo com todas as notas no formato `.csv`.

## Responsividade

A interface foi adaptada para funcionar em diversos tamanhos de tela, com layout flexível e colunas ajustáveis para dispositivos móveis.

## Contribuindo

Contribuições são bem-vindas. Caso deseje sugerir melhorias, correções ou novas funcionalidades, sinta-se à vontade para abrir uma issue ou um pull request.