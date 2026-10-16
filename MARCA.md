# Yacaré Seguros — manual de uso da marca

Yacaré Seguros is named after the jacaré-do-pantanal (*Caiman yacare*), whose mother guards her nest for three months and then carries every hatchling, one by one in her mouth, to the safety of the water. Everything in the brand says **protection that carries the family through time**: warm greens from the Pantanal, an off-white like paper, one terracota accent, a soft serif that speaks gently, and a small jacaré resting on the edge of every frame.

The system is built for **social posts (1080×1350)** and brand applications. All measurements are on that canvas; scale them proportionally.

## Voice and copy

- Speak to the reader as **você**, warmly, as someone who cares. Ask the question rather than sell: the brand line is a question.
- Core line: **"E depois de você, quem cuida das finanças?"** Support line: **"Proteção que atravessa o tempo."**
- Sentence case, Brazilian Portuguese, short lines. No exclamation-mark selling, no emoji, no all-caps headlines (all caps belong only to "SEGUROS" inside the logo).
- Break a headline into 3–4 short lines that each carry one idea:
  > E depois  
  > de ***você,***  
  > quem cuida  
  > das ***finanças?***
- Emphasise one or two words per headline, never more: the person (**você**) and the stake (**finanças**, **família**, **futuro**).

## Colour

Use the palette exactly; tokens hold the official values from the palette sheet.

- `off-white` and `verde-yacare` are the two main grounds; `verde-profundo` is the dark ground; `verde-medio` is the ink of the wordmark and icons; `terracota` appears only in "SEGUROS" and as a small accent.
- Set text with the semantic tokens: `texto` on `fundo`, `texto-marca` for headlines on `fundo`, `texto-sobre-marca` (white) on `fundo-marca` and photos.
- White on `verde-yacare` is 4.39:1: fine for headlines (`titulo`, `chamada`), not for small text. Put small text on `off-white` or `verde-profundo`.
- Never set text in `terracota` on `off-white` or white (2.76:1).
- Two-tone posts stack `verde-medio` over `verde-profundo`, or a photo over `verde-yacare`, divided by the zigzag edge.
- The logo artwork and the post templates were exported with near-identical values (#4b6842, #628052, #cb8052, #f4f1ee). Use the files as they are; use the tokens for anything you build.

## Typography

Two families, stored as variable font files in this system: Fraunces upright `fonts/Fraunces-VariableFont_SOFT,WONK,opsz,wght.ttf` and italic `fonts/Fraunces-Italic-VariableFont_SOFT,WONK,opsz,wght.ttf` (weights 100–900), and `fonts/Quicksand-VariableFont_wght.ttf` (weights 300–700). Declare them as "Fraunces" (normal and italic) and "Quicksand" with `@font-face`; `titulo-enfase` uses the real Fraunces italic.

- **Fraunces** (`display`) carries the voice. Headlines in `titulo` (Light 300, 84/76px on a 1080 post) with the key words in `titulo-enfase` (Bold Italic 700). Leading is tight (0.9); keep lines ragged, left-aligned.
- The brand book also uses **Fraunces 72pt Soft SemiBold** (opsz 72, SOFT 100, weight 600) for institutional headlines; use it in print and stationery, not in posts.
- **Quicksand** (`sans`) is the supporting voice: tagline lockups beside the logo in `chamada-forte` (Bold) then `chamada` (Regular), e.g. **Proteção** / que atravessa / o tempo. The brand book's fill-in phrases ("E depois ___ de você,") use Quicksand Regular with Medium (500) on the key words.
- Never set body copy in Fraunces Bold Italic; never use a third typeface.

## Logo

Assets in **Logos**: `logo-preferencial.svg` (full colour), `logo-verde-medio.svg`, `logo-preto.svg`, `logo-negativo.svg`.

- Use `logo-preferencial` on `off-white` and white. Use `logo-negativo` on `verde-yacare`, `verde-medio`, `verde-profundo` and photos. Use `logo-verde-medio` where only one ink is possible on light grounds; `logo-preto` only for black one-colour reproduction.
- Clear space: the height of the "x" (the brand book's "x" unit) on every side.
- On posts, the logo sits bottom-right, small (about 180–200px wide on 1080), or beside a Quicksand tagline in a lockup (see the Assinatura component).
- The logo is always the complete lockup: jacaré, "Yacaré" and "SEGUROS" together. Only these four files are the logo.
- The jacaré alone is not a logo: never use it as a signature, profile picture, app icon or favicon, and never crop it out of the logo files. Profile pictures and avatars use one of the four complete versions.
- Never recolour, outline, stretch, add effects, or separate the jacaré from the wordmark.

## Shapes and layout

- **The zigzag ("dentes")**: the jacaré's back turned into an edge. Four teeth across the post (`dente-largura` 270px, `dente-altura` 64px). It divides a photo from a green band, or closes the post as a footer. Use the Templates files rather than redrawing it.
- **The frame**: photos sit in a frame, either rounded (`raio-moldura` 45px, inset `moldura-arredondada` 56px, small teeth on the top-right edge) or square with a zigzag base (`moldura-reta` 98px). A small jacaré rests on the bottom-left of the frame, as if guarding it.
- Headlines start at `margem-post` (112px) from the left edge, in the green band or on `off-white`.
- Flat colour only: no gradients, no drop shadows, no glows.

## Imagery

- Real, warm moments of care: hands holding hands, parents and babies, families walking or at the beach at sunset. Natural light; one black-and-white treatment is allowed.
- Calm studio set-ups on brand green: the umbrella over a wooden family, the origami jacaré, the house of hands.
- Textured "ondulado" backgrounds in each brand green and in off-white (Fundos) for text-only posts.
- No stock-photo handshakes, no money piles, no fear imagery (accidents, fire).

## Iconography

- **Icones** holds one set of eight thin-line icons (mind, health card, family reading, medicine, transport, care, headset, home), drawn with rounded strokes, as PNG sheets in `verde-medio` and in white. Use green on `off-white`, white on the greens.
- There are no individual icon files: crop from the sheets or request separate SVGs before building UI with them. Do not substitute another icon library without flagging it.

## Partner and cause marks

- **Parceiros** holds the "Minha Vida Protegida" logo and symbol (orange #ff8f00, theirs, not ours) and the autism-awareness puzzle ribbon.
- They appear small, bottom-left of the post, opposite the Yacaré logo, never larger than the logo and never recoloured.

## Templates and examples

- **Templates**: the 1080×1350 bases (off-white, verde, verde escuro), footers ("rodapé") and frame templates 1–5 plus the white outline frame. Start every post from one of them.
- **Exemplos**: approved posts and carousel slides; match their rhythm before inventing a new layout.
- **Manual**: the full brand book PDF and the colour palette sheet.
