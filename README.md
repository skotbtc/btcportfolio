# ₿ BTC Portfolio

> 🟠 Bitcoin portfolio tracker — live price, P&L, collateralized loans, 9 cycle indicators and encrypted backups. A single HTML file, no install needed.
>
> 🟠 Gerenciador de portfólio Bitcoin — cotação ao vivo, P&L, empréstimos com colateral, 9 indicadores de ciclo e backup encriptado. Um único arquivo HTML, sem instalação.

---

## 🇺🇸 English

### What is it

A Bitcoin portfolio tracker that runs straight in your browser. No server, no sign-up, no dependencies — just open the `.html` file. Your data never leaves your machine.

### Features

**Portfolio**
- **Live price** with 4 cascading sources (Binance → Kraken → Coinbase → CoinGecko), refreshed every 60s
- **Overview**: total value, unrealized P&L, avg. cost, total invested, BTC bought and BTC/USD allocation
- **4 units**: view everything in **BTC, SATS, USD or BRL** (defaults to BTC; remembers your choice)
- **Editable balances and avg. cost** with one click
- **Privacy mode 👁**: blur all values for screenshots or public places

**Transactions & DCA**
- Log buys, sells and deposits (BTC/USD) with date, time and notes
- **Inline editing** right in the history row
- Trades plotted on the candlestick chart
- **CSV export** of the full history (Excel/Sheets-ready, useful for tax reporting)

**BTC-collateralized loans**
- Debt with daily accrued interest (APR), **live LTV**, liquidation price and distance to it
- P&L vs having sold the BTC
- Grouped by name under **Custody**, showing net collateral − debt

**Custody**
- Track where your stack lives (cold wallet, hot wallet, exchange…) with % and unallocated alert

**Chart**
- 4H / daily / weekly / monthly candles with zoom and RSI(14)

**Cycle indicators (dedicated tab)**
- Fear & Greed, MVRV Ratio, Realized Price, NUPL, Mayer Multiple, Pi Cycle Top, 200-Week MA, Bitcoin Power Law and Halving countdown
- Color-coded bottom/top zones, auto-refresh every 30 min

**Backup**
- Export/import all data as JSON
- **Optional password encryption** (AES-256-GCM, PBKDF2 · 300k iterations — 100% local)
- 🟠 indicator for changes not yet backed up

**General**
- Bilingual 🇧🇷 🇺🇸 · Dark theme with the classic Bitcoin orange

### How to use

1. Download `BTC Portfolio (Standalone).html` from the [Releases](../../releases) page
2. Open it in your browser (double-click)
3. Set your balances by clicking the values under **Balances**
4. Log transactions, custody and loans
5. **Export a backup before closing** — that's how your data is kept

### Where is my data stored?

**In memory only while the page is open**, plus the backup files you export. Nothing is persisted automatically — by design: no traces are left in the browser. The app warns you on exit if there are unexported changes (orange dot on the backup button).

⚠️ An encrypted backup without its password is **unrecoverable**. Keep it safe.

### Privacy

- No data is ever sent to any server; no account, analytics or tracking
- The only external calls are **read-only** requests to public APIs: price/candles (Binance, Kraken, Coinbase, CoinGecko), Fear & Greed (alternative.me), on-chain data (CoinMetrics community) and block height (mempool.space / blockstream.info)
- Works offline (except live price and indicators) and over Tor


---

## 🇧🇷 Português

### O que é

Um gerenciador de portfólio Bitcoin que roda direto no navegador. Sem servidor, sem cadastro, sem dependências — basta abrir o arquivo `.html`. Seus dados nunca saem da sua máquina.

### Funcionalidades

**Portfólio**
- **Cotação ao vivo** com 4 fontes em cascata (Binance → Kraken → Coinbase → CoinGecko), atualizada a cada 60s
- **Visão geral**: valor total, P&L não realizado, preço médio, total investido, BTC comprado e alocação BTC/USD
- **4 unidades**: veja tudo em **BTC, SATS, USD ou BRL** (abre em BTC; lembra sua escolha)
- **Saldos e preço médio editáveis** com um clique
- **Modo discreto 👁**: borre todos os valores para abrir em público ou tirar screenshot

**Transações & DCA**
- Registro de compras, vendas e depósitos (BTC/USD), com data, hora e nota
- **Edição inline** direto na linha do histórico
- Operações plotadas no gráfico de candles
- **Exportação CSV** do histórico (pronta para Excel/planilhas e declaração de IR)

**Empréstimos com colateral em BTC**
- Dívida com juros acumulados dia a dia (APR), **LTV atual**, preço de liquidação e distância até ele
- P&L vs ter vendido o BTC
- Agrupados por nome na seção **Custódia**, mostrando o líquido colateral − dívida

**Custódia**
- Registre onde seu stack está (cold wallet, hot wallet, corretora…) com % e alerta de não alocado

**Gráfico**
- Candles 4H / diário / semanal / mensal com zoom e RSI(14)

**Indicadores de ciclo (aba própria)**
- Fear & Greed, MVRV Ratio, Realized Price, NUPL, Mayer Multiple, Pi Cycle Top, Média de 200 Semanas, Bitcoin Power Law e countdown do Halving
- Zonas de fundo/topo coloridas e atualização automática a cada 30 min

**Backup**
- Exporte/importe todos os dados em JSON
- **Encriptação opcional por senha** (AES-256-GCM, PBKDF2 com 300 mil iterações — 100% local)
- Indicador 🟠 de alterações ainda não salvas em backup

**Geral**
- Bilíngue 🇧🇷 🇺🇸 · Tema escuro com o laranja clássico do Bitcoin

### Como usar

1. Baixe o arquivo `BTC Portfolio (Standalone).html` na página de [Releases](../../releases)
2. Abra no navegador (duplo clique)
3. Defina seus saldos clicando nos valores em **Saldos**
4. Registre transações, custódia e empréstimos
5. **Exporte um backup antes de fechar** — é assim que seus dados são guardados

### Onde ficam meus dados?

**Apenas na memória enquanto a página está aberta** e nos arquivos de backup que você exporta. Nada é gravado automaticamente — por design: nenhum rastro fica no navegador. O app avisa ao sair se houver alterações não exportadas (pontinho laranja no botão de backup).

⚠️ Backup encriptado sem a senha é **irrecuperável**. Guarde bem a senha.

### Privacidade

- Nenhum dado é enviado a servidor algum; não há conta, analytics ou rastreamento
- As únicas conexões externas são consultas **somente leitura** a APIs públicas: preço/candles (Binance, Kraken, Coinbase, CoinGecko), Fear & Greed (alternative.me), dados on-chain (CoinMetrics community) e altura de bloco (mempool.space / blockstream.info)
- Funciona offline (exceto cotação e indicadores) e via Tor


---

## 📋 Changelog

| Version | Highlights / Destaques |
|---|---|
| **v1.3** | Privacy mode 👁 · SATS unit · invested + stacked summary · CSV export · unsaved-backup dot · defaults to BTC and remembers unit / Modo discreto · unidade SATS · total investido + BTC comprado · exportação CSV · indicador de backup pendente · abre em BTC e lembra a unidade |
| **v1.2** | Password-encrypted backups (AES-256-GCM) · inline history editing · loans grouped under Custody (collateral − debt) / Backup encriptado por senha · edição inline no histórico · empréstimos agrupados na Custódia (colateral − dívida) |
| **v1.1** | Indicators tab with 9 cycle metrics and auto-refresh / Aba de indicadores com 9 métricas de ciclo e atualização automática |
| **v1.0** | Portfolio, transactions, candlestick chart with RSI, loans, wallets and JSON backup / Portfólio, transações, gráfico de candles com RSI, empréstimos, carteiras e backup JSON |

---

**V1.3** · Built with vanilla HTML/CSS/JS · No frameworks, no build step
