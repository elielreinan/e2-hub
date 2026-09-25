# 2E.dev — Portfolio

Portfolio da 2E.dev, uma operação freelance focada exclusivamente em desenvolvimento de software.

## Estrutura

- `src/index.html` — página principal
- `src/assets/logo.svg` — logo em estilo display digital, inspirada na referência enviada
- `src/CNAME` — domínio `e2dev.me`
- `.github/workflows/pages.yml` — deploy automático para GitHub Pages
- `.gitignore` — arquivos locais ignorados
- `README.md` — documentação

## Stack do site

HTML5 + Tailwind CSS via CDN + CSS customizado + Devicon CDN para os ícones da stack.

## Executar localmente

Na raiz do projeto:

```bash
python -m http.server 8000 --directory src
```

Acesse `http://localhost:8000`.

## Deploy

O workflow do GitHub Actions publica automaticamente o conteúdo de `src/` no GitHub Pages a cada push na branch `main`.

O domínio configurado no projeto é `e2dev.me`.

## Conteúdo

O portfolio apresenta exclusivamente serviços e projetos relacionados a software. Não há seções de infraestrutura, suporte ou produtividade.
