# Sito statico Gympanion

Questo repository/cartella contiene il sito informativo e la Privacy Policy di Gympanion. Non usa build tool, framework, cookie o analytics: GitHub Pages può servire direttamente questi file.

## Pubblicazione su GitHub Pages

1. Crea un nuovo repository GitHub, ad esempio `gympanion-site`.
2. Carica il contenuto di questa cartella nella root del repository.
3. In **Settings → Pages**, scegli **Deploy from a branch**, il branch `main` e la cartella `/(root)`.
4. Attendi la pubblicazione e inserisci in Google Play Console l'URL pubblico:
   `https://<tuo-account-github>.github.io/gympanion-site/privacy.html`

La pagina deve rimanere pubblica, senza autenticazione e raggiungibile anche da browser mobile.

## Prima della pubblicazione

- Controlla che la dicitura `Lo sviluppatore` e `lucamanuel999@gmail.com` siano coerenti con le informazioni che compariranno nella scheda Google Play.
- Mantieni aggiornati Privacy Policy e sezione **Sicurezza dei dati** di Play Console quando cambiano dati, permessi, SDK o servizi esterni dell'app.
- Inserisci nell'app un collegamento visibile alla stessa pagina Privacy Policy, ad esempio nelle Impostazioni.
