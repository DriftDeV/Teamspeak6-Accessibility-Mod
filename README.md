# Teamspeak6-Accessibility-Mod
Questa è una mod di accessibilità per teamspeak6, dato che di base
teamspeak non è accessibile con screen reader
ovviamente questo progetto è ancora in uno stato prematuro, in alpha
se vogliamo dire così, quindi molte cose devono ancora essere ottimizzate
e aggiustate però ci sto lavorando
Datemi feedback e fatemi sapere quali feature posso aggiungere
tutti i suggerimenti sono graditi!
# Installazione
## Windows
### Prerequisiti
* Screen Reader  I(ovviamente)
* Nodejs
* Teamspeak6
  ### Installazione di Node
  Se non hai già node installato, su windows puoi installarlo tramite questo link
  https://nodejs.org/en/download
  Consiglio scaricate il .msi (si trova in basso alla pagina dopo il blocco di codice di docker)
  ### Installazione di Teamspeak
  https://www.teamspeak.com/en/downloads/
  Logicamente, scarica la versione per Windows a 64bit di temspeak 6.0.0 (versione attuale)
  
### Installazione ed esecuzione degli Script di accessibilità
* Vai su https://github.com/DriftDeV/Teamspeak6-Accessibility-Mod/releases e scaricati source-code.zip

* Estrai il file zip, e nella cartella creata fai tasto destro (shft-F10) e seleziona "Apri nel terminale" e digita:
  ''' npm install package.json '''
* se vi si presenta un errore digitate:
  ''' npm udit fix --force '''
 E poi riprovate a digitare il comando precedente a questo, dovrebbe funzionare
* Adesso vi basta soltanto fare tasto destro su start-teamspeak.ps1 ed "esegui con powershell" ed il gioco è fatto!
Per qualsiasi cosa potete creare una issue e vi risponderò quanto prima possibile
  

## MacOS
