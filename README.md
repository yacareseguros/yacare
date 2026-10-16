# Yacaré Seguros — Design System

Identidade visual da Yacaré Seguros: cores, tipografia, logos, templates de post, imagens e regras de uso.

> **Proteção que atravessa o tempo.**

## Estrutura

| Pasta | Conteúdo |
| --- | --- |
| [`MARCA.md`](MARCA.md) | Manual de uso: tom de voz, cores, tipografia, logo, formas, imagens, ícones e parceiros |
| [`tokens/`](tokens) | `tokens.json` (fonte dos valores) e `tokens.css` (variáveis CSS prontas, com as fontes) |
| [`fonts/`](fonts) | Fraunces (normal e itálico) e Quicksand, fontes variáveis |
| [`assets/Logos`](assets/Logos) | As quatro versões completas do logo (SVG) |
| [`assets/Templates`](assets/Templates) | Bases, rodapés e molduras de post 1080×1350 (SVG) |
| [`assets/Icones`](assets/Icones) | Folhas de ícones em verde e branco (PNG) |
| [`assets/Fundos`](assets/Fundos) | Fundos texturizados e fotos-chave |
| [`assets/Exemplos`](assets/Exemplos) | Posts e carrosséis aprovados |
| [`assets/Parceiros`](assets/Parceiros) | Minha Vida Protegida e fita do autismo |
| [`assets/Manual`](assets/Manual) | Manual da marca e paleta de cores (PDF) |
| [`components/`](components) | Exemplos visuais: capa, Título, Assinatura e Post Social (abra o `preview.html` no navegador) |

## Cores

| Nome | HEX | Uso principal |
| --- | --- | --- |
| Verde Yacaré | `#628151` | Fundo de posts, faixa em zigue-zague |
| Verde Médio | `#516b43` | Logo, ícones, títulos sobre off-white |
| Verde Profundo | `#1f2f26` | Fundo escuro, texto sobre off-white |
| Terracota | `#cc8052` | "SEGUROS" e pequenos destaques (nunca texto sobre claro) |
| Off-White | `#f5f1ee` | Fundo claro |

## Tipografia

- **Fraunces** — títulos. Light (300) com as palavras-chave em Bold Italic (700): "E depois de *você*, quem cuida das *finanças?*"
- **Quicksand** — textos de apoio e chamadas ao lado do logo.

## Usando em um site

```html
<link rel="stylesheet" href="tokens/tokens.css">
<h1 class="titulo" style="color: var(--texto-marca)">E depois de <em class="titulo-enfase">você</em>…</h1>
```

O tema escuro é ativado com `data-theme="escuro"` no `<html>`.

## Regras essenciais

- O logo é sempre a versão **completa** (jacaré + "Yacaré" + "SEGUROS"). O jacaré sozinho não é logo.
- Não recolorir, distorcer ou aplicar efeitos ao logo.
- Use os SVGs de `assets/Templates` para o zigue-zague e as molduras; não redesenhe.

Licenças das fontes: Fraunces e Quicksand são distribuídas sob a SIL Open Font License.
