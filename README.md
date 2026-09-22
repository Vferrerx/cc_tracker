# 🌿 Centro Comunitário — Checklist

Um checklist interativo, offline e no estilo visual de **Stardew Valley**, para acompanhar quais itens você já tem para completar os conjuntos (*bundles*) do Centro Comunitário padrão do jogo.

![Licença](https://img.shields.io/badge/licença-MIT-a66d3f) ![Feito com](https://img.shields.io/badge/feito%20com-HTML%20%2B%20CSS%20%2B%20JS-7a4a24)

## Sobre o projeto

Este projeto nasceu de uma necessidade simples: acompanhar, fora do jogo, quais itens dos conjuntos do Centro Comunitário já foram conseguidos. É uma página HTML única, sem build, sem dependências de backend e sem necessidade de instalação — basta abrir no navegador.

O progresso fica salvo automaticamente no seu navegador (`localStorage`), então você pode fechar a aba e voltar depois sem perder nada.

## Funcionalidades

- ✅ **Checklist completo** dos 6 cômodos e 30 conjuntos do Centro Comunitário padrão (não randomizado)
- 💰 **Rastreio de ouro** para os 4 pagamentos do Cofre (2.500 / 5.000 / 10.000 / 25.000)
- 🔍 **Busca** por item ou conjunto, em qualquer cômodo
- 🧭 **Filtro por cômodo** e opção de mostrar apenas os conjuntos pendentes
- 📦 **Visão "Todos os itens"**, útil quando um mesmo item aparece em mais de um conjunto
- 💾 **Progresso salvo automaticamente** no navegador (`localStorage`), sem conta ou servidor
- ⬆️⬇️ **Exportar e importar progresso** em `.json`, para fazer backup ou trocar de dispositivo
- 🎨 **Visual temático**, inspirado na estética rústica/pixelada de Stardew Valley

## Como usar

1. Baixe ou clone este repositório
2. Abra o arquivo `index.html` diretamente no navegador (duplo clique já funciona)
3. Clique nos itens para marcar o que você já possui
4. Use a busca e os filtros de cômodo para navegar mais rápido
5. Exporte seu progresso de vez em quando como backup

Não é necessário nenhum servidor, build ou instalação — é uma página estática.

> **Nota:** os ícones dos itens são carregados da [Stardew Valley Wiki](https://stardewvalleywiki.com), então é necessário estar conectado à internet para eles aparecerem. O checklist, os filtros e o progresso salvo funcionam mesmo offline.

## Estrutura do projeto

```
cc_tracker/
├── index.html          # aplicação inteira (HTML + CSS + JS)
└── assets/
    └── placeholder.svg # ícone de reserva, caso um sprite não carregue
```

## Tecnologias

- HTML, CSS e JavaScript puros — sem frameworks, sem etapa de build
- `localStorage` para persistência do progresso no navegador
- Ícones dos itens servidos pela Stardew Valley Wiki, com cadeia de fallback (proxy de imagem → espelho em português → ícone local) para reduzir casos de ícone ausente

## Créditos

- Nomes e requisitos dos conjuntos baseados na página **Bundles** da [Stardew Valley Wiki](https://stardewvalleywiki.com) (em português)
- Ícones dos itens hospedados pela Stardew Valley Wiki
- Stardew Valley é uma criação de ConcernedApe — este projeto é um fã-tracker sem fins comerciais e não possui vínculo oficial com o jogo ou seus criadores

## Licença

Distribuído sob a licença MIT. Sinta-se à vontade para usar, adaptar e melhorar.
