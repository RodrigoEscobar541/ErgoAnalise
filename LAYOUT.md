# LAYOUT.md — Sistema visual do folder novo (equipe de design)

> **Fonte:** 2 PNGs entregues pela equipe de design (as duas imagens são a **mesma peça**,
> em duplicata — não são duas peças diferentes).
> **Formato:** A4 paisagem, 3 colunas verticais. É um **folder / one-pager institucional**,
> não uma tela de site.
>
> **Status desta versão:** este documento **substitui integralmente** a versão anterior do
> LAYOUT.md (que descrevia o folder "Livia Escobar / Portfólio" + "Implantação NR-01").
> Aquelas peças ficam como histórico de conteúdo; **a direção visual vigente é esta.**
>
> **Aviso sobre cores:** todos os HEX abaixo foram estimados visualmente a partir dos PNGs.
> Estão marcados com `~` e devem ser confirmados contra o arquivo original (Canva/PDF)
> antes de virarem tokens definitivos.

---

## Índice

- [1. O que mudou em relação ao layout anterior](#1-o-que-mudou-em-relação-ao-layout-anterior)
- [2. Tokens visuais](#2-tokens-visuais)
- [3. Estrutura da peça](#3-estrutura-da-peça)
- [4. Conteúdo — transcrição integral](#4-conteúdo--transcrição-integral)
- [5. Tradução da peça para o site](#5-tradução-da-peça-para-o-site)
- [6. O que a peça NÃO cobre](#6-o-que-a-peça-não-cobre)

---

## 1. O que mudou em relação ao layout anterior

Três mudanças estruturais. Elas **contradizem** o LAYOUT.md antigo e prevalecem sobre ele:

| Tema | Layout anterior | Layout novo (esta peça) |
|---|---|---|
| **Superfície escura** | Não existia. Tudo era creme; o olive aparecia só em ondas e blobs. | Existe um **painel verde-escuro sólido, sangrado de topo a base**, ocupando uma coluna inteira. É o principal recurso de hierarquia da peça. |
| **Raio de borda** | `0` — "nenhum card, caixa ou botão arredondado existe nas imagens". | O **botão é uma pílula** (raio = metade da altura). O raio deixa de ser 0 para elementos de ação. |
| **Terracota** | `~#C05F3C` — mais saturado e escuro, usado em ícones de linha e títulos. | `~#CA8062` — **mais claro e mais salmão**, usado como **preenchimento** (botão) e em filetes. Não aparece em texto corrido. |

Duas mudanças de tom:

- **Caixa alta some.** A peça anterior era quase toda em MAIÚSCULAS. Esta usa **caixa mista** em
  tudo, inclusive nos títulos. Muito mais legível.
- **Densidade cai.** A peça anterior empilhava 12 + 7 blocos de serviço. Esta tem **3 blocos de
  texto por coluna, no máximo**, com muito respiro. O ativo visual passou a ser o espaço em branco.

---

## 2. Tokens visuais

### 2.1 Cores

| Token | HEX (~estimado) | Papel |
|---|---|---|
| `--paper` | `~#F3F0E7` | Fundo das colunas 1 e 3. Creme quente, levemente amarelado. É o fundo padrão do documento. |
| `--paper-alt` | `~#EDE9DE` | Não aparece explicitamente na peça; derivado, um passo mais escuro que `--paper`, para faixas alternadas. |
| `--forest` | `~#434F42` | **Painel escuro da coluna 2** (sangra topo a base). Verde-floresta dessaturado, puxando para cinza-oliva. Não é preto nem verde vivo. |
| `--forest-ink` | `~#3C4A3D` | Cor dos **títulos serifados sobre creme** ("Livia Escobar — ErgoAnálise", "Como atrair e reter talentos…", "Por que Escolher a ErgoAnálise?"). Um tom abaixo de `--forest`. |
| `--terracotta` | `~#CA8062` | **Preenchimento do botão-pílula** e do filete sob "Livia Escobar". Salmão/argila claro. |
| `--terracotta-deep` | `~#B36A4C` | Derivado, para estado hover do botão. Não aparece na peça. |
| `--olive` | `~#6B7350` | Palavra "ANÁLISE" do logotipo e a linha de assinatura no pé da coluna 3. |
| `--olive-soft` | `~#A8AE8C` | Derivado; usado como meio-tom onde a peça só tem transparência. |
| `--ink` | `~#45463E` | Texto corrido sobre creme. Cinza-quente esverdeado, nunca preto puro. |
| `--ink-soft` | `~#5C5C52` | Texto secundário / assinatura de rodapé da coluna 3. |
| `--on-dark` | `~#F0EDE3` | Texto e filetes sobre o painel `--forest`. Creme levemente mais frio que `--paper`. |
| `--star-dark` | `rgba(240,237,227,0.13)` | Rosa-dos-ventos decorativa **sobre** o painel verde. Renderiza como `~#4E5A4B`. |
| `--star-light` | `~#E7E4D2` | Rosa-dos-ventos e circunferências decorativas **sobre** o creme. Contraste baixíssimo, quase marca-d'água. |

**Cores do logotipo** (glifo circular, aparece 2× na peça):

| Elemento | HEX (~estimado) |
|---|---|
| Disco superior | `~#F2C230` (amarelo-ouro) |
| Arco / semicírculo inferior | `~#D2703F` (terracota saturado) |
| Contorno, colchetes laterais e palavra "ANÁLISE" | `~#6B7350` (olive) |
| Palavra "ERGO" | `~#D2703F` |

**Regras de cor observadas**

- **Não há preto puro nem branco puro** em nenhum ponto da peça.
- **Terracota nunca é usada em texto.** Só como preenchimento (botão) e filete. Isso é uma
  mudança em relação à peça anterior, onde terracota titulava.
- **Verde é a cor da voz da marca**: painel, títulos e assinatura. Terracota é a cor da **ação**.
- Os dois cremes (coluna 1 e coluna 3) são praticamente idênticos; a diferença perceptível é
  ruído de compressão, não intenção de design.

### 2.2 Tipografia

Nenhuma fonte é declarada. As identificações abaixo são **inferidas visualmente**.

| Papel | Característica observada | Família recomendada | Onde |
|---|---|---|---|
| **Display serifado** | Serifa transicional com bracketing marcado, contraste alto haste/filete, altura-x grande, entrelinha apertada (~1.05–1.15), peso semibold/bold | **Playfair Display** (600/700) — Prata e Lora são alternativas | "Livia Escobar — ErgoAnálise"; "Sua Empresa Pronta para o Próximo Nível?"; "Como atrair e reter talentos…"; "Por que Escolher a ErgoAnálise?" |
| **Corpo** | Sans humanista/geométrica, `a` de dois andares, altura-x alta, peso Regular, entrelinha larga (~1.6) | **DM Sans** (300/400/500) | Todos os parágrafos, os 4 contatos da coluna 2, o rótulo do botão, a assinatura do rodapé |

> A família serifada usada até agora no site (**Cormorant Garamond**) é **mais leve e mais
> estreita** do que a serifa da peça. A troca para Playfair Display é a mudança tipográfica
> desta versão. **DM Sans permanece** — é compatível com o que se vê.

### 2.3 Escala e hierarquia

Não há medidas absolutas. Hierarquia relativa observada (múltiplos do corpo base):

| Nível | Escala | Exemplo |
|---|---|---|
| H1 do painel escuro | **~3.0×**, serif, entrelinha ~1.1 | "Sua Empresa Pronta para o Próximo Nível?" |
| H1 sobre creme | **~2.9×**, serif, verde | "Como atrair e reter talentos no cenário atual e ainda estar dentro das normas?" |
| H2 de coluna | **~1.9×**, serif, verde | "Livia Escobar — ErgoAnálise" |
| H3 interno | **~1.35×**, serif, verde, bold | "Por que Escolher a ErgoAnálise?" |
| Subtítulo / lead | **~1.15×**, sans, regular | "Agende um Diagnóstico Integrado de RH e SST." |
| Corpo | **1×** (base), sans, regular, entrelinha ~1.65 | Parágrafos das colunas 1 e 3 |
| Contatos (coluna 2) | **~1.05×**, sans, entrelinha muito larga (~2.6 entre linhas) | "WhatsApp: (11) 98385-3451" |
| Rótulo do botão | **~0.95×**, sans, medium | "Soluções Estratégicas da ErgoAnálise" |
| Assinatura de rodapé | **~0.8×**, sans, olive | "ErgoAnálise — RH por Competências \| T&D \| Ergonomia \| SST" |

Ênfase dentro de parágrafo é feita com **negrito na mesma cor**, nunca com cor diferente
(ex.: "…mas **onde ninguém quer morar.**").

### 2.4 Espaçamento e grid

- **Proporção da peça:** ≈ 1.41:1 (A4 paisagem, 297×210 mm).
- **Grid de 3 colunas, larguras desiguais:** col. 1 ≈ **33%** · col. 2 ≈ **28%** · col. 3 ≈ **39%**.
  A coluna do meio é a mais estreita e a única com fundo próprio.
- **Sem calhas visíveis:** as colunas se encostam. A separação é **puramente cromática**
  (creme → verde → creme), sem linha, sem sombra, sem borda.
- **Padding interno das colunas:** generoso e uniforme, ≈ 6–7% da largura da peça em todos os lados.
- **Espaço entre blocos de texto:** ≈ 1.8–2.2× a altura de linha. Entre título e seu parágrafo, ≈ 0.8×.
- **Entrelinha do corpo:** ~1.6–1.7. A peça é deliberadamente arejada.
- **Espaço entre as linhas de contato (col. 2):** ~2.6× — muito maior que o corpo normal.
  É um recurso de ritmo, não um erro.

### 2.5 Raio de borda

- **Botão: pílula completa** (`border-radius: 999px`). É o único elemento com raio na peça.
- Foto da Livia: **recorte reto**, canto vivo, sem moldura.
- Painel verde: **canto vivo**, sangrando nas 3 bordas que tocam a página.
- Conclusão para o sistema: `--radius: 0` para superfícies e cards; `--radius-pill: 999px`
  para botões e chips.

### 2.6 Sombras

- **Nenhuma.** Nenhum `box-shadow` ou `text-shadow` em nenhum elemento.
- Toda separação de plano vem de **cor de fundo**. O botão-pílula é chapado sobre o creme.

### 2.7 Elementos decorativos

Dois motivos, ambos derivados da rosa-dos-ventos do logotipo:

1. **Estrela de 8 pontas (rosa-dos-ventos).** Aparece 2×:
   - Sobre o painel verde, canto inferior, **sangrando pela borda** — creme a ~13% de opacidade.
   - Sobre o creme da coluna 3, canto superior direito — `--star-light`, envolta em
     **2–3 circunferências concêntricas finas** e raios curtos radiais.
   As pontas são finas e agudas (proporção ~1:8), alternando 4 pontas longas (cardeais) e
   4 curtas (colaterais).
2. **Filete horizontal curto.** ~2px de espessura, ~90–120px de comprimento, sempre **acima ou
   abaixo de um título**, alinhado à esquerda:
   - Creme, no topo da coluna 2 (abre o painel escuro).
   - Terracota, sob "Livia Escobar — ErgoAnálise".

Não há: ícones, pins de mapa, linhas pontilhadas, blobs orgânicos ou ondas — **todos os
decorativos da peça anterior foram abandonados.**

---

## 3. Estrutura da peça

```
+---------------------------------------------------------------------------------+
| +-- COL 1 (33%, creme) --+ +- COL 2 (28%, --forest) -+ +-- COL 3 (39%, creme) -+ |
| | [foto]        [logo]   | | [filete creme]          | | [logo]     [estrela   | |
| |                        | |                         | |          concentrica] | |
| |                        | | H1 Sua Empresa Pronta   | |                       | |
| |                        | |    para o Proximo       | |                       | |
| | H2 Livia Escobar       | |    Nivel?               | | H1 Como atrair e reter| |
| |    - ErgoAnalise       | |                         | |    talentos no cenario| |
| | [filete terracota]     | | sub Agende um           | |    atual e ainda estar| |
| |                        | |     Diagnostico         | |    dentro das normas? | |
| | p bio (4 linhas)       | |     Integrado de RH/SST | |                       | |
| |                        | |                         | | p lead (3 linhas)     | |
| |                        | |                         | |                       | |
| | H3 Por que Escolher    | | WhatsApp: ...           | |                       | |
| |    a ErgoAnalise?      | |                         | |                       | |
| |                        | | E-mail: ...             | |                       | |
| | p (2 linhas)           | |                         | |                       | |
| |                        | | Instagram: ...          | | (   BOTAO PILULA    ) | |
| | p (3 linhas, com bold) | |                         | |                       | |
| |                        | | Site: ...               | |                       | |
| | p (5 linhas)           | |                         | |                       | |
| |                        | |    [estrela sangrando]  | | assinatura de rodape  | |
| +------------------------+ +-------------------------+ +-----------------------+ |
+---------------------------------------------------------------------------------+
```

**Ordem de leitura pretendida:** coluna 2 (a pergunta) → coluna 3 (a promessa + ação) →
coluna 1 (a credencial). O painel escuro é o ponto de entrada visual, apesar de estar no meio.

---

## 4. Conteúdo — transcrição integral

Transcrito exatamente como aparece na peça.

### 4.1 Coluna 1 — Credencial

**Título:** `Livia Escobar — ErgoAnálise`

**Bio:**
> Mais de 25 anos de experiência prática em backoffice, gestão financeira, comercial e
> departamento pessoal. Especialista em Gestão de RH Generalista por Competências, Ergonomia
> e Gestão de NR-01.

**Subtítulo:** `Por que Escolher a ErgoAnálise?`

> Estar apenas em conformidade com as normas não garante o sucesso do seu negócio.

> Preencher requisitos legais de SST sem uma estrutura de RH por Competências é como construir
> uma casa segura, mas **onde ninguém quer morar.**

> A ErgoAnálise integra a segurança do ambiente (SST/Ergonomia) ao desenvolvimento das pessoas
> (RH/T&D). Nós transformamos obrigações trabalhistas em uma cultura forte de atração, retenção
> e alta performance.

### 4.2 Coluna 2 — Chamada e contato (painel verde)

**H1:** `Sua Empresa Pronta para o Próximo Nível?`

**Subtítulo:** `Agende um Diagnóstico Integrado de RH e SST.`

**Contatos:**

| Rótulo | Valor |
|---|---|
| WhatsApp | `(11) 98385-3451` |
| E-mail | `apoio.consultoria.10@gmail.com` |
| Instagram | `@ergo_analise` |
| Site | `www.ergoanalise.com.br` |

### 4.3 Coluna 3 — Promessa e ação

**H1:** `Como atrair e reter talentos no cenário atual e ainda estar dentro das normas?`

**Lead:**
> Unimos a Gestão de RH por Competências à Segurança do Trabalho para criar ambientes seguros,
> atrativos e altamente produtivos.

**Botão (pílula terracota):** `Soluções Estratégicas da ErgoAnálise`

**Assinatura de rodapé:** `ErgoAnálise — RH por Competências | T&D | Ergonomia | SST`

### 4.4 Observações sobre o conteúdo

- **Nenhum erro de digitação** foi encontrado nesta peça (diferente da anterior, que tinha 13).
- O telefone aparece formatado como `(11) 98385-3451` — com parênteses. A peça anterior usava
  `11 98385-3451`. **Padronizado em `(11) 98385-3451`** no site.
- O Instagram aparece como `@ergo_analise` — com arroba. Padronizado.
- A assinatura de rodapé define os **4 pilares oficiais da marca**, nesta ordem:
  `RH por Competências · T&D · Ergonomia · SST`. É a definição mais curta e mais atual do
  posicionamento — usada como descritor da empresa no site inteiro.
- O botão diz "Soluções Estratégicas", não "Fale conosco". O vocabulário de CTA da marca é
  **de valor**, não de contato.

---

## 5. Tradução da peça para o site

A peça não é um wireframe web. Este é o mapeamento adotado no [Index.html](Index.html):

| Elemento da peça | Onde vira o quê no site |
|---|---|
| Painel `--forest` sangrado | **Nav no topo, faixa de números, faixa "Resultado Integrado", seção de contato e rodapé.** É o recurso de ritmo vertical da página: alterna creme → verde → creme. |
| H1 serifado creme sobre verde | Título do hero e da seção de contato. |
| H1 serifado verde sobre creme | Todos os `.section-title`. |
| Filete curto de 2px | `.rule` — abre cada seção: terracota sobre creme, creme sobre verde. |
| Botão-pílula terracota | `.btn-primary`. Sobre fundo verde vira `.btn-on-dark` (pílula creme, texto verde). |
| Estrela de 8 pontas | SVG inline decorativo, `aria-hidden`, em 3 pontos: hero (sobre verde), faixa integrada (sobre verde) e contato (sobre verde). |
| Grid 33/28/39 | Não é replicável em web responsivo. Vira grid assimétrico em desktop e empilhamento único em mobile. |
| Espaçamento generoso | `--sec-pad: clamp(5rem, 9vw, 8.5rem)` de padding vertical por seção. |
| Bio da Livia + "Por que escolher" | Seção `#sobre`, ao lado da foto. |
| Contatos da coluna 2 | Seção `#contato` (cards sobre verde) + rodapé. |
| Assinatura dos 4 pilares | Descritor da marca no rodapé e no `og:description`. |

---

## 6. O que a peça NÃO cobre

Tudo abaixo **não existe** na peça e foi derivado do site atual ou definido do zero:

### 6.1 Estrutura de site

- **Header / navegação**, estado ativo, comportamento no scroll, menu mobile (hambúrguer + drawer).
- **Rodapé de site completo** — a peça tem 4 linhas de contato; falta navegação, copyright, descritor.
- **Botão flutuante de WhatsApp** — existe no site, não na peça.
- **Âncoras internas e rolagem suave.**

### 6.2 Componentes de interface

- **Estados do botão** — só existe o estado de repouso. `hover`, `focus`, `active` e `disabled`
  foram derivados (`--terracotta-deep` no hover, contorno de foco visível em 2px).
- **Botão secundário / ghost** — não existe na peça. Derivado: contorno verde de 1px, sem preenchimento.
- **Cards** — a peça usa texto solto em coluna. Os cards do site (`.dor-card`, `.serv-bloco`,
  `.regiao-card`) usam borda de 1px `--hairline`, sem sombra e sem raio, para não contradizer a peça.
- **Acordeão (FAQ)**, seletor de formulário, iframe — nenhum equivalente na peça.
- **Indicador de foco de teclado** — não definido na peça; obrigatório no site.

### 6.3 Comportamento

- **Breakpoints** e ordem de empilhamento em mobile.
- **Animações** — a peça é estática. O site mantém `reveal` no scroll com `--ease-out-expo`.
- **Modo escuro** — não existe. A paleta é clara, com o verde como acento, não como tema.

### 6.4 Conteúdo

- **Prova social**, depoimentos, logos de clientes, preços, blog, área de cliente — nada disso
  aparece na peça nem existe no site.
- **Política de privacidade / LGPD** — ausente nos dois.
- O conteúdo de texto do site **não vem desta peça**: vem do documento
  [Código do Site ErgoAnálise - RH por Competências e SST.docx](Código%20do%20Site%20ErgoAnálise%20-%20RH%20por%20Competências%20e%20SST.docx).
  A peça define **como** o site parece; o .docx define **o que** ele diz.

### 6.5 Ativos

- **Logotipo vetorial** — só existe rasterizado dentro dos PNGs. O site usa wordmark em texto
  ("Ergo Análise") em vez do glifo, porque não há SVG disponível.
- **Estrela de 8 pontas em SVG** — não fornecida; foi redesenhada à mão no site.
- **Foto da Livia** — [livia-escobar.jpg](livia-escobar.jpg) existe no repo; o recorte da peça é
  mais fechado e com fundo escuro.
- **Valores HEX exatos e nomes de fonte** — não fornecidos. Ver aviso no topo.
