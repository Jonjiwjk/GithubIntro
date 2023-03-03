# Registrazione al GitHub

1) Apri il sito web di [GitHub](https://github.com/).
2) Fai clic sul pulsante "Sign up" (Registrati) in alto a destra della pagina.
3) Inserisci il tuo indirizzo email e una password sicura.
4) Fai clic sul pulsante "Create account" (Crea account) per continuare.
5) Completa il processo di verifica del tuo account facendo clic sul link di verifica inviato al tuo indirizzo email.
6) Fornisci alcune informazioni aggiuntive per completare la tua registrazione, come il tuo nome, la tua posizione e i tuoi interessi.

[Scribe-How](https://scribehow.com/shared/Creating_a_GitHub_Account__8NlzqoIMTbi2Ji8X4C3nDA)

Fatto! Ora hai un account GitHub e puoi iniziare a creare repository, collaborare con altri sviluppatori e contribuire a progetti open source.

**NB:** Assicurati che la password sia lunga almeno 8 caratteri e contenga lettere, numeri e simboli.

---

## Approfondimenti

## Configurazione credential-manager

marco@DESKTOP-72VFU3G MINGW64 ~/Documents/GitProjects
$ git config --global credential.credentialStore gpg

marco@DESKTOP-72VFU3G MINGW64 ~/Documents/GitProjects
$ git credential-manager configure
Configuring component 'Git Credential Manager'...
Configuring component 'Azure Repos provider'...

marco@DESKTOP-72VFU3G MINGW64 ~/Documents/GitProjects
$ git credential-manager store

marco@DESKTOP-72VFU3G MINGW64 ~/Documents/GitProjects
$ git config --global credential.https://github.com/.useHttpPath true