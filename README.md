# ₿ BTC Portfolio

> 🟠 Gerenciador de portfólio Bitcoin/USD — tema escuro, cotação ao vivo, P&L e backup em JSON. Um único arquivo HTML, sem instalação.
>
> 🟠 Bitcoin/USD portfolio tracker — dark theme, live price, P&L and JSON backup. A single HTML file, no install needed.

---

## 🇧🇷 Português

### O que é

Um gerenciador de portfólio BTC/USD que roda direto no navegador. Sem servidor, sem cadastro, sem dependências — basta abrir o arquivo `.html`. Seus dados nunca saem da sua máquina.

### Funcionalidades

- **Cotação ao vivo** do BTC via API pública da Binance (atualiza a cada 60s)
- **Visão geral do portfólio**: valor total, P&L não realizado, preço médio e alocação BTC/USD
- **Conversão de moeda**: visualize tudo em BTC, USD ou BRL
- **Saldos editáveis**: clique no saldo de Bitcoin ou Dólar para editar diretamente
- **Preço médio editável**: defina seu preço médio manualmente — novas compras recalculam a média de forma ponderada
- **Registro de transações**: compras, vendas e depósitos, com data e nota
- **Backup e restauração**: exporte/importe todos os dados em um arquivo JSON
- **Bilíngue**: alterne entre português e inglês pelas bandeiras 🇧🇷 🇺🇸
- **Tema escuro** com o laranja clássico do Bitcoin

### Como usar

1. Baixe o arquivo `BTC Portfolio (standalone).html`
2. Abra no navegador (duplo clique)
3. Defina seus saldos clicando nos valores em **Saldos**
4. Defina seu preço médio clicando em **Preço médio**
5. Registre novas transações conforme operar

### Onde ficam meus dados?

No `localStorage` do navegador — vinculados ao arquivo e ao navegador usados. **Importante:** limpar os dados de navegação apaga tudo. Use o botão **⤓ Exportar backup** regularmente para guardar seus dados em um arquivo JSON seguro.

### Privacidade

- Nenhum dado é enviado a servidor algum
- A única conexão externa é a consulta de preço à Binance (somente leitura, sem identificação)
- Funciona offline (exceto a cotação ao vivo)

---

## 🇺🇸 English

### What is it

A BTC/USD portfolio tracker that runs straight in your browser. No server, no sign-up, no dependencies — just open the `.html` file. Your data never leaves your machine.

### Features

- **Live BTC price** via Binance public API (refreshes every 60s)
- **Portfolio overview**: total value, unrealized P&L, average cost and BTC/USD allocation
- **Currency toggle**: view everything in BTC, USD or BRL
- **Editable balances**: click the Bitcoin or Dollar balance to edit it in place
- **Editable average cost**: set your avg. cost manually — new buys recalculate it as a weighted average
- **Transaction log**: buys, sells and deposits, with date and notes
- **Backup & restore**: export/import all data as a JSON file
- **Bilingual**: switch between Portuguese and English via the flags 🇧🇷 🇺🇸
- **Dark theme** with the classic Bitcoin orange

### How to use

1. Download `BTC Portfolio (standalone).html`
2. Open it in your browser (double-click)
3. Set your balances by clicking the values under **Balances**
4. Set your average cost by clicking **Avg. cost**
5. Log new transactions as you trade

### Where is my data stored?

In the browser's `localStorage` — tied to the file location and browser you use. **Important:** clearing browsing data wipes everything. Use the **⤓ Export backup** button regularly to keep your data safe in a JSON file.

### Privacy

- No data is ever sent to any server
- The only external call is the read-only price fetch from Binance
- Works offline (except the live price)

---

**V1.0** · Built with vanilla HTML/CSS/JS · No frameworks, no build step
