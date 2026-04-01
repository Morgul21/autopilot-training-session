# autopilot-training-session
autopilot-training
Userscript Tampermonkey che fa runnare in background (muto compreso) i video formativi su un match site definito dall'utente, notificandoti quando terminano anche se sei su un altro tab.

Funzionalità
▶️ Il video non si mette in pausa quando cambi tab

🔔 Notifica di sistema quando il video è finito

🔇 V1.0 Compatibile con il mute della scheda. Mutandolo direttamente dal video lo script non parte (to-do)
Requisiti

Google Chrome (o qualsiasi browser Chromium-based)
Estensione Tampermonkey installata

Installazione
1. Installa Tampermonkey
Vai sul Chrome Web Store e installa l'estensione Tampermonkey.
2. Crea un nuovo script dall'icona di tampermonkey
Clicca sull'icona di Tampermonkey in alto a destra nel browser, poi seleziona "Crea nuovo script". CTRL+S per salvare lo script

Se è andato tutto ok dovresti avere il toggle dello script attivo, e l'icona di tampermonkey con un flag rosso che ti segna il numero di script attivi.
Se così non fosse, vai su Chrome -> Estensioni -> Gestisci Estensioni -> Tampermonkey -> Dettagli -> Consenti Script Utente -> Riapri il tab-> Enjoy.

Dovresti essere in grado di eseguire video in background in una scheda mentre stai lavorando su un altra.
N.B. Assicurati di mutarlo da scheda di chrome: right-click->Disattiva audio sito, il mute da comandi della modale triggera un altro evento che non fa partire lo script.
