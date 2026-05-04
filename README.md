# LFS Capture Dashboard

Monitor de requisições Git LFS para teste de segurança em Cloudflare Pages.

## Estrutura

- `index.html` - Dashboard principal
- `styles.css` - Estilos
- `lfs/capture/index.html` - Endpoint de captura LFS

## Uso

1. Configure `.lfsconfig` no repositório alvo:
```ini
[lfs]
    url = https://graomelo.github.io/lfs/capture
```

2. Quando o Cloudflare Pages fizer build, o Git LFS conectará aqui
3. O dashboard mostrará os dados capturados