# Cookies da Mãe Joana — landing page

Site estático (HTML + CSS + um pouco de JavaScript), sem build e sem dependências.

## Estrutura
- `index.html` — a página inteira
- `fotos/` — imagens em WebP (logo e 9 fotos)
- `vercel.json` — cache das fotos e cabeçalhos básicos

## Publicar no GitHub
```bash
git init
git add .
git commit -m "Landing page Cookies da Mãe Joana"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/cookies-da-mae-joana.git
git push -u origin main
```

## Publicar na Vercel
1. Em vercel.com, escolha **Add New → Project** e importe o repositório.
2. **Framework Preset:** Other. Deixe Build Command e Output Directory em branco.
3. Clique em **Deploy**.

Também funciona sem GitHub: arraste a pasta para vercel.com/new.

## Antes de divulgar (pendências)
- [ ] Confirmar o número de WhatsApp: está como `554196963967` (8 dígitos após o DDD). Se o número real tiver 9 dígitos (41 9XXXX-XXXX), trocar em todo o `index.html` (busca por `554196963967`) e o texto `(41) 9696-3967` no rodapé e no JSON-LD (`+554196963967`).
- [ ] Confirmar os horários (tabela em "Onde estamos").
- [ ] Trocar o `canonical` (`https://DOMINIO-A-DEFINIR/`) pelo domínio real.
- [ ] Trocar o `og:image` (`fotos/foto-07.webp`) por URL absoluta com o domínio real.
- [ ] Nomes e sabores dos cookies (avisos "em breve").
- [ ] Prazo de encomenda e área de entrega (aviso "em breve").
- [ ] História da Mãe Joana (aviso "em breve").
- [ ] Fotos originais em alta resolução: substituir os arquivos de `fotos/` mantendo os mesmos nomes e ajustar `width` e `height` no `index.html`.

## Observações
- Endereço completo removido de propósito; a página mostra só Água Verde, Curitiba, Paraná.
- Depoimentos são trechos reais de clientes por WhatsApp, sem nome, com autorização da dona.
