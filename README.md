# Programa OZ 2026 (Espaço Lis Coradi)

Site estático de um arquivo só (`index.html`). Não há build.

## Publicar pela CLI (3 comandos)

```bash
npm i -g vercel        # uma vez
vercel login           # abre o navegador, entra na sua conta
vercel --prod          # dentro desta pasta; na primeira vez, aceite os padrões
```

A CLI pergunta nome do projeto (sugestão: `programa-oz`) e pasta; é só confirmar.
O endereço de produção aparece no fim (`https://programa-oz.vercel.app` ou similar).

## Atualizar depois

Substitua o `index.html` e rode `vercel --prod` de novo. O `vercel.json`
desliga o cache do HTML, então a versão nova aparece na hora no celular.

## Domínio próprio (opcional)

No painel do projeto, Settings > Domains, adicione por exemplo
`programa.seudominio.com.br` e crie o CNAME indicado no DNS do domínio.

## QR codes

Um QR geral: `https://SEU-ENDERECO/`

Um QR por sessão (abre já filtrado, sem perguntar):

- Sáb 7, 10h: `https://SEU-ENDERECO/#s7-10`
- Sáb 7, 15h: `https://SEU-ENDERECO/#s7-15`
- Sáb 7, 19h: `https://SEU-ENDERECO/#s7-19`
- Dom 8, 10h: `https://SEU-ENDERECO/#s8-10`
- Dom 8, 15h: `https://SEU-ENDERECO/#s8-15`
- Dom 8, 19h: `https://SEU-ENDERECO/#s8-19`
