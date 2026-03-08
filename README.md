# Guion — Site Institucional

Site institucional da **Guion Sistemas e Consultoria**, especializada em automação inteligente com RPA & IA para escritórios de advocacia e empresas do setor de recuperação judicial.

## Estrutura

```
guion-site/
├── index.html          # Página principal (single-page)
├── 404.html            # Página de erro personalizada
├── CNAME               # Domínio customizado (guion.dev.br)
├── robots.txt          # Configuração para buscadores
├── sitemap.xml         # Sitemap para SEO
├── favicon.ico         # Favicon colorido
├── favicon_gray.ico    # Favicon cinza (alternativo)
└── assets/
    └── img/
        ├── logo.png        # Logo teal (fundo escuro)
        ├── logo_gray.png   # Logo cinza (fundo claro)
        └── logo_white.png  # Logo branca (fundo escuro)
```

## Deploy no GitHub Pages

1. Crie um repositório no GitHub (ex: `guion-site` ou `guion.dev.br`)
2. Faça push de todos os arquivos deste diretório para a branch `main`
3. Vá em **Settings > Pages**
4. Em **Source**, selecione `Deploy from a branch` > `main` > `/ (root)`
5. Clique em **Save**

### Domínio Customizado

Para configurar `guion.dev.br`:
1. No registrador DNS, adicione os seguintes registros:
   - `A` apontando para `185.199.108.153`
   - `A` apontando para `185.199.109.153`
   - `A` apontando para `185.199.110.153`
   - `A` apontando para `185.199.111.153`
   - `CNAME` de `www` apontando para `<usuario>.github.io`
2. No GitHub Pages, marque **Enforce HTTPS**
3. O arquivo `CNAME` já está configurado no repositório

## SEO

O site inclui:
- Meta tags otimizadas para o setor jurídico (recuperação judicial)
- Dados estruturados (JSON-LD) para Organization e WebSite
- Open Graph tags para compartilhamento em redes sociais
- Sitemap XML
- Robots.txt
- Semântica HTML5 com atributos ARIA

## Contato

- **E-mail:** contato@guion.dev.br
- **Site:** https://guion.dev.br
