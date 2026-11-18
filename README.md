# Portfólio — Marcelo José Gomes Parreira

Site pessoal com visual claro e efeito vidro. Mostra os projetos com uma prévia animada ao passar o mouse e uma ficha completa ao clicar.

**Ao vivo:** https://jmarcelogomesparreira-ship-it.github.io/

## Como publicar no GitHub Pages

1. Crie um repositório chamado **`jmarcelogomesparreira-ship-it.github.io`**. Com esse nome, o site fica no endereço principal, sem `/nome-do-projeto/` no final.
2. Suba o `index.html` e este `README.md`.
3. Vá em **Settings → Pages → Branch: main → / (root) → Save**.
4. Em 1 ou 2 minutos o site está no ar.

## Arquivos opcionais (deixam o site ainda melhor)

| Arquivo | O que faz |
|---|---|
| `foto.jpg` | Opcional: a foto já vai embutida no `index.html`. Para trocar, suba `foto.jpg` e mude `foto: FOTO` para `foto: "foto.jpg"`. |
| `curriculo.pdf` | Arquivo do botão "Baixar currículo". |
| `prints/sigma.jpg` etc. | Print real do projeto, no lugar da cena animada. |
| `videos/sigma.mp4` etc. | Vídeo curto (5–10 s, sem som) que toca ao passar o mouse. |

Depois de subir um print ou vídeo, preencha o campo do projeto no `index.html` (bloco `PROJETOS`, logo no início do `<script>`):

```js
img: "prints/sigma.jpg", video: "videos/sigma.mp4"
```

### Como gravar o vídeo da prévia
- **Windows:** `Win + Alt + R` (Xbox Game Bar) grava a janela do navegador.
- Grave de 5 a 10 segundos com a simulação rodando (velocidade 60× fica ótimo).
- Para ficar leve, comprima em https://www.freeconvert.com/video-compressor (alvo: menos de 3 MB por vídeo).

## Editando textos
Tudo fica no começo do `<script>`:
- `PERFIL`: nome, cargo, e-mail, WhatsApp, LinkedIn, GitHub
- `PROJETOS`: cada projeto (resumo, problema, o que faz, destaques, link)
- `EXPERIENCIA`, `FORMACAO`, `SKILLS`

Um projeto com `url: ""` mostra o botão **"Pedir demonstração"**, que abre o WhatsApp. Serve para os projetos que você só manda para quem quiser.

## Confira os links
Os endereços dos projetos foram montados a partir dos nomes dos repositórios. Abra cada um para conferir, principalmente o **Torque** (`torque-manutencao`) e o **Pátio 34** (`patio34-veiculos`).
