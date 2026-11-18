# Doutor Face — Transplante Capilar

Landing page de conversão para transplante capilar FUE em Cascavel/PR.
Tráfego pago (Meta Ads) → WhatsApp.

## Stack

HTML, CSS e JavaScript puros. Sem build, sem dependências.

## Estrutura

```
index.html           página completa (estilos e scripts inline)
config.js            WhatsApp, dados da clínica, médica, Pixel
ESTRATEGIA.md        estratégia de tráfego e atendimento
assets/resultados/   6 casos antes/depois
```

## Editar

Quase tudo que muda está em `config.js`: número de WhatsApp, dados da
clínica, responsável técnica e ID do Pixel do Meta. Os textos da página
estão em `index.html`, com comentários marcando cada seção.

## Rodar localmente

```bash
python3 -m http.server 8777
# abre em http://localhost:8777
```

## Publicar

Site estático — qualquer host serve. No Vercel ou Netlify, conecte o
repositório e publique sem configuração extra (a raiz já é o site).

## Pendências

- [ ] Foto da Dra. Letícia em `assets/dra-leticia.jpg`
- [ ] ID do Pixel do Meta em `config.js`
- [ ] Autorização de uso de imagem dos pacientes (arquivo da clínica)

## Responsável técnica

Dra. Letícia Menezes de Almeida Cardoso — CRM-PR 62027
