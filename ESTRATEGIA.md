# Doutor Face · Transplante Capilar
## Site + estratégia de aquisição

---

## 1. Antes de publicar (bloqueantes)

| # | Item | Onde |
|---|------|------|
| 1 | ~~Nome e CRM do médico~~ **feito:** Dra. Letícia Menezes, CRM-PR 62027 | `config.js` |
| 2 | **Foto da Dra. Letícia**, salvar como `assets/dra-leticia.jpg` | a seção já está pronta, mostra placeholder até lá |
| 3 | **Autorização de uso de imagem assinada** dos 6 pacientes | arquivo físico/digital na clínica |
| 4 | Confirmar que o WhatsApp `(45) 99951-0548` é o que atende leads | `config.js` → `whatsapp` |
| 5 | Criar o Pixel do Meta e colar o ID | `config.js` → `metaPixelId` |

**Responsável técnica:** Dra. Letícia Menezes de Almeida Cardoso, CRM-PR 62027 que atua em medicina
capilar e é pós-graduanda em Dermatologia (AFYA/SP). Nome e registro aparecem na seção de
autoridade, no rodapé e no schema de SEO, como exige a publicidade médica.

O Dr. Matheus França de Oliveira (cirurgia plástica, INCA) não entra nesta página, que trata
só de transplante capilar. Se a clínica quiser divulgar cirurgia plástica, o caminho é uma
landing própria, porque misturar os dois serviços dilui a mensagem e confunde o tráfego pago.

---

## 2. Por que este site não tem contagem regressiva

A referência (M Hair) usa countdown porque tinha evento real de 3 dias. Você não tem data.
Copiar o countdown sem o evento cria **escassez falsa**, e em saúde isso destrói conversão
no ponto mais caro: o lead chega ao WhatsApp desconfiado, pergunta preço e some.

O motor aqui é outro:

```
Referência (lançamento)          Este site (perene)
───────────────────────          ──────────────────
Urgência de data          →      Prova + autoridade médica
"Garanta sua vaga"        →      "Descubra se você é candidato"
Formulário + e-mail       →      WhatsApp direto
Nutrição até o evento     →      Conversa agora
```

**A oferta é o diagnóstico, não o desconto.** "Avaliação capilar gratuita" tem baixa fricção,
qualifica o lead (quem aceita avaliação está considerando de verdade) e dá um motivo honesto
para chamar hoje. Sem mentir sobre prazo.

---

## 3. Estrutura da página e o que cada bloco faz

| Seção | Função no funil |
|-------|-----------------|
| **Hero + caso em destaque** | Prova em 2 segundos. No mobile a foto vem antes do texto, que é o que segura o scroll vindo do Meta. |
| **6 casos reais** (logo em seguida) | Volume de prova antes de qualquer argumentação. Um caso é sorte, seis é método. CTA dentro do bloco. |
| **Como funciona (3 etapas)** | Mata o medo do desconhecido. Cirurgia assusta; processo explicado não. |
| **Dra. Letícia (CRM-PR 62027)** | Diferencia de clínica sem médico e de pacote na Turquia. Justifica preço maior. |
| **FAQ (5 perguntas)** | Responde o que trava o lead antes do WhatsApp e ainda economiza atendimento. |
| **CTA final** | Reafirma a oferta como diagnóstico, não como venda. |
| **Barra fixa (mobile)** | CTA sempre presente. ~85% do tráfego Meta é mobile. |

**CTA único, "Agendar avaliação":** todos os 6 botões usam o mesmo texto, em verde WhatsApp.
Um comando repetido se fixa; textos diferentes a cada bloco fazem o leitor reavaliar a decisão
toda vez. O verde separa a ação da cor de marca e antecipa para onde o clique leva.

**Por que os resultados vêm logo após o hero:** tráfego frio do Meta não lê argumentação,
decide por prova. A página é curta de propósito (~690 palavras): quem está convencido converte
na galeria, e quem precisa de mais encontra as etapas e o FAQ abaixo. Sete botões de WhatsApp
distribuídos para que nunca seja preciso rolar de volta.

**Decisão de copy deliberada:** a seção de preço no FAQ não dá valor e explica *por que* não dá
("desconfie de quem dá preço fechado por telefone"). Isso transforma a objeção de preço em
argumento de autoridade, e leva a conversa para o WhatsApp, que é onde você fecha.

---

## 4. Tráfego no Meta

### Estrutura de campanha
```
Objetivo:  Conversões  →  evento "Contact" (já instalado nos botões)
           Comece em Tráfego só se o pixel tiver < 50 conversões/semana.

Campanha
├── Conjunto A (ampla)     | Cascavel + 50km | Homens 28-55 | sem interesses
├── Conjunto B (interesse) | idem            | Calvície, minoxidil, barbearia, estética masculina
└── Conjunto C (retarget) | quem viu 50%+ da página ou do vídeo, 30 dias
```

Comece pelo **Conjunto A**. O algoritmo do Meta acha homem com calvície melhor que
segmentação manual, porque o rosto na foto já é o filtro.

### Orçamento sugerido (início)
- R$ 50-80/dia distribuído entre A e B
- Mínimo 7 dias sem mexer (deixe sair da fase de aprendizagem)
- Só então corte o pior conjunto e realoque

### Criativos, por ordem de prioridade
1. **Antes/depois em vídeo** com transição lenta (o que mais performa nesse nicho)
2. **Carrossel** com 4-5 dos casos da pasta
3. **Depoimento falado** do paciente. Se conseguir gravar, converte muito
4. Imagem estática antes/depois (use como controle, não como principal)

### Atenção às políticas do Meta
A política de saúde proíbe anúncios que impliquem imagem corporal negativa ou foquem em
"defeito" da pessoa. O que reprova e o que passa:

| Evite | Use |
|-------|-----|
| "Você está ficando careca?" | "Transplante capilar com folículo próprio" |
| "Acabe com a calvície" | "Conheça o procedimento" |
| Zoom isolado na área falhada | Antes/depois completo, mesma luz |
| "Resultado garantido" | "Resultados variam conforme o caso" |

Antes/depois é tecnicamente restrito na política de saúde do Meta. Na prática roda neste
nicho, mas **espere reprovações eventuais**. Mantenha 2 ou 3 criativos aprovados em reserva e
nunca deixe a conta depender de um criativo só.

---

## 5. O WhatsApp é onde se ganha ou perde

O site entrega o lead quente. Se o atendimento demora, o dinheiro do anúncio evapora.

**Regra de ouro: responda em menos de 5 minutos no horário comercial.**

### Roteiro de atendimento

```
1. ABERTURA (imediata)
   "Oi [nome]! Aqui é [atendente] da Doutor Face. Vi que você quer a avaliação
    capilar. Posso te fazer 3 perguntas rápidas pra já te adiantar?"

2. QUALIFICAÇÃO (3 perguntas, não mais)
   • "Há quanto tempo você percebe a queda?"
   • "Já fez algum tratamento antes?"
   • "Me manda 2 fotos: uma de cima da cabeça e uma da nuca?"
     a foto da nuca é o que define se ele é candidato, por causa da área doadora

3. AUTORIDADE
   "Pelas fotos dá pra ver que [observação real]. Quem avalia é o Dr. [nome],
    e ele define o número exato de folículos no atendimento."

4. AGENDAMENTO (ofereça 2 horários, nunca pergunta aberta)
   "Tenho quinta às 14h ou sexta às 10h. Qual fica melhor?"

5. CONFIRMAÇÃO
   Lembrete 1 dia antes + no dia. Reduz muito o não-comparecimento.
```

**Sobre preço no WhatsApp:** não passe valor fechado antes da avaliação, nem por insistência.
Resposta pronta:
> "O valor depende de quantos folículos o seu caso precisa, e isso só dá pra saber olhando sua
> área doadora. Por isso a avaliação é gratuita: você sai de lá sabendo o número exato, o valor
> e as condições. Sem compromisso nenhum."

---

## 6. O que medir

| Métrica | Referência saudável | Onde |
|---------|--------------------|------|
| CTR do anúncio | acima de 1,5% | Gerenciador de Anúncios |
| Custo por clique | R$ 0,80 - R$ 2,50 | Gerenciador |
| Clique → WhatsApp | acima de 15% | evento `Contact` no Pixel |
| Custo por conversa | R$ 15 - R$ 50 | Gerenciador |
| Conversa → agendamento | acima de 30% | planilha manual |
| Agendamento → comparecimento | acima de 60% | planilha manual |
| Comparecimento → fechamento | 20-40% | planilha manual |

Cada botão manda a origem do clique (`hero`, `galeria`, `medico`, `final`, `barra-fixa`) junto com o evento.
Depois de umas 2 semanas você vai saber qual seção converte e pode encurtar a página nos
trechos que ninguém usa.

**Monte uma planilha simples** com: data | nome | origem | respondeu? | agendou? | compareceu? |
fechou? | valor. Sem isso você otimiza anúncio no escuro, porque o Meta só enxerga até a conversa.

---

## 7. Próximos passos sugeridos

**Semana 1**: subir o site, instalar o pixel e rodar R$ 50/dia no Conjunto A
**Semana 2 e 3**: deixar rodar, medir e ajustar só os criativos
**Mês 2**: ligar o retargeting do Conjunto C, que costuma ter o menor custo por conversa
**Mês 3**: com mais de 20 atendimentos, você sabe seu custo real por paciente e pode escalar com segurança

### Melhorias que valem depois de validar
- **Vídeo depoimento** de paciente no hero, no lugar da foto. É o maior ganho de conversão disponível
- **Página separada por tipo de calvície** (entradas, coroa, difusa) para SEO e segmentação
- **Simulador de folículos**: quiz de 4 perguntas que estima a faixa e captura o lead
- **Google Ads** para "transplante capilar Cascavel". A intenção é muito maior que no Meta, com volume menor

---

## 8. Arquivos

```
site/
├── index.html              página completa
├── config.js               ← edite aqui (WhatsApp, médico, pixel)
├── ESTRATEGIA.md           este documento
└── assets/resultados/      6 casos (caso-01 … caso-06.jpg)
```

### Como publicar
O site é estático, feito com HTML, CSS e JS, sem build. Arraste a pasta `site/` em
[app.netlify.com/drop](https://app.netlify.com/drop) ou conecte no Vercel. Publica em segundos.
Depois aponte um subdomínio, como `capilar.doutorface.com.br`.

### Como editar
Quase tudo que muda está em `config.js`. Os textos da página estão em `index.html`, com comentários marcando cada seção.
