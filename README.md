# Pormaishof — site

Site da Pormaishof, escola de Harmonização Orofacial em Recife. Duas versões estáticas (HTML, CSS e JS puros, sem build).

| Pasta | Versão |
|---|---|
| `v01/` | Versão principal |
| `v02/` | Landing de conversão (GSAP ScrollTrigger) |

A raiz (`index.html`) redireciona para `v01/`.

## Publicar no GitHub Pages

1. Envie o conteúdo desta pasta para a raiz do repositório.
2. Em **Settings > Pages**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`.
3. O site fica em `https://<usuario>.github.io/<repositorio>/` (v01) e `.../v02/`.

## Dependências externas (CDN)

- Google Fonts: Montserrat (v01 e v02) e Figtree (v02)
- GSAP 3.15.0 e ScrollTrigger via jsDelivr (somente v02)

## Pendências antes do lançamento

- Trocar as fotos e o vídeo (`img/`) pelos originais em alta, hoje tirados do Instagram
- Logo vetorial no lugar do monograma em texto
- Datas reais em "Próximas turmas"
- Validar com as professoras os tópicos dos cursos, o mapa de marcação e as respostas da FAQ
