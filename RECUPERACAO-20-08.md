# Recuperação do Projeto Guajupiá — 20/08/2026

## Projeto identificado

**Guajupiá — Dossiê de Implantação e Investimento**

## Evidências recuperadas do Telegram

- Versão completa original: `/root/guajupia_app/index.html`
- Versão simples original: `/root/guajupia_app/guajupia-simples/index.html`
- Link completo antigo: `barrier-washington-north-settings.trycloudflare.com`
- Link simples antigo: `source-email-achievements-bind.trycloudflare.com`
- ZIP original recuperado do Telegram: `guajupia_app_v8_en_dolar.zip`
- Arquivos no ZIP original: `index.html`, `README.md`, `foto-sitio.jpg`

## Alterações de quinta-feira reaplicadas

### App completo
- texto ajustado para “sistemas agroflorestais com foco em frutíferas nativas” em PT/EN;
- custos reais de perlita, vermiculita, húmus, micorrizas, bokashi, Calda Bordalesa e composto;
- biofertilizante registrado como produção própria, sem custo de compra;
- subtotal dos insumos comprados: R$ 6.155,38;
- total conhecido da seção de custos: R$ 23.455,38, mantendo cinco itens sem orçamento.

### Versão simples
- foto fixa `foto-sitio.jpg`;
- foco e zoom no canto inferior direito (`object-position:100% 100%`, escala 1,35);
- lucro bruto por safra: R$ 112.500 a R$ 562.500;
- quadro A/B/C de totais;
- tabela editável e sincronizada com os totais;
- conversão PT/EN e BRL/USD, taxa histórica R$ 5 = US$ 1;
- sementes/mudas: A R$ 2.400, B/C R$ 4.800;
- seção própria de insumos removida da versão simples;
- opção de trocar a foto removida;
- nota “Estufa com −30% / liofilizadora / C ideal” removida, conforme pedido final.

## Validação atual

Teste Playwright em viewport mobile confirmou:

- foto visível e fixa;
- ausência de upload/troca de foto;
- lucro por safra presente;
- quadro A/B/C correto;
- seis linhas editáveis;
- recálculo ao editar uma célula;
- troca PT/EN;
- conversão para dólar sem `R$` residual na versão simples;
- versão completa carregando o dossiê e os custos recuperados;
- zero erros JavaScript de página.
