# 📦 PatchUP – Verifica Ricambi

Repo con codice Apps Script + HTML per verifiche magazzino PatchUP.

## Struttura
- Code.gs → backend Apps Script
- Index.html → form inserimento (mobile)
- Dashboard.html → dashboard gestione
- Styles.html → stili
- Articoli_PatchUP_from_Form.csv → dataset iniziale articoli

## Setup
1. Crea un Google Sheet `Verifica Ricambi PatchUP` con fogli: Config, Articoli, Conteggi, StockCorrente, TrasferimentiSuggeriti
2. Apri **Estensioni → Apps Script** e copia i file di questo repo.
3. Importa `Articoli_PatchUP_from_Form.csv` nel foglio `Articoli`.
4. **Deploy → App Web** e usa i link `...?page=form` (tecnici) e `...?page=dashboard` (gestione).
