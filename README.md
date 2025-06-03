# Capire il cambiamento climatico con Python ⛈️🐍

Ciao! 🙋‍♂️

Qui troverai il codice per riprodurre le analisi del talk ["Capire il cambiamento climatico con Python"](https://2025.pycon.it/en/event/capire-il-cambiamento-climatico-con-python-dal-rapporto-ipcc-allazione-climatica), e anche di più!
<br>
Ho tenuto questo talk il 29 maggio 2025 in occasione della PyConIT 2025.

Vuoi analizzare dati climatici, sia passati che futuri? Ecco, cominciamo! 🚀

👉 (Se invece sei solo alla ricerca della presentazione, guarda nella cartella `presentation`)

## Installazione 🪺

Consiglio di utilizzare [uv](https://docs.astral.sh/uv/). Se non lo hai, spendi 10 secondi [per installarlo](https://docs.astral.sh/uv/getting-started/installation/#standalone-installer).

Quindi, con un unico comando puoi creare un ambiente virtuale nella cartella `.venv`:
```sh
uv sync --frozen
```

Hai l'ambiente pronto per lo sviluppo!

Ti consiglio di utilizzare [VSCode](https://code.visualstudio.com/) per aprire ed interagire con i notebook.

## Codici 🧑‍💻
Sono presenti due notebook (li riconosci grazie all'estensione `.ipynb`):
1. `ssp_variables.ipynb` analizza l'evoluzione storica e futura delle variabili socioeconomiche e climatiche a livello globale secondo i 5 scenari climatici futuri definiti dalla comunità scientifica;
2. `temperature.ipynb` analizza e crea graziose gif del cambiamento della temperatura in Italia dal 1950 al 2099, sempre considerando i 5 scenari climatici futuri.

I notebook sono strumenti per eseguire Python in maniera interattiva e cellulare: sono divisi in celle, che si possono eseguire indipendentemente e che mostrano il proprio output sotto di sé (nei notebook troverai l'output che avevo ottenuto eseguendoli sul mio computer).

⚠️ A grandi poteri corrispondono grandi responsabilità! ⚠️ I notebook sono molto utili per sperimentare e sono carini, tuttavia è molto facile creare confusione di variabili e raggiungere uno stato di caos di variabili!
<br>
Ti consiglio di utilizzare i notebook dall'alto al basso; aggiungi nuove celle o modifica quelle esistenti, ma con consapevolezza per evitare di sovrascrivere variabili senza che tu te ne accorga.

## Presentazione 👀
Nella cartella `presentation` trovi la presentazione del talk sia in formato `.pptx` che in formato `.pdf` (dove tuttavia video e gif sono statici!). 

## Contribuire 👐
Hai trovato un'inesattezza? Vuoi estendere le analisi? Vuoi commentare o discutere?
<br>
Ti invito ad aprire una issue qui su GitHub! 🐙

## Per approfondire 📚
👉 [Articolo di pubblicazione](https://www.sciencedirect.com/science/article/pii/S0959378016300681) degli scenari climatici SSP.

👉 [Homepage del Copernicus Climate Data Store](https://cds.climate.copernicus.eu/) dove è possibile trovare innumerevoli dataset meteorologici e climatici di alta qualità completi di Python API e documentazione/pubblicazione scientifica a supporto.

👉 [Sesto Assessment Report della IPCC](https://www.ipcc.ch/assessment-report/ar6/), la pubblicazione più rilevante che sintetizza lo stato della conoscenza del sistema clima e della sua evoluzione; oltre alla versione completa, sono presenti sintesi del report.

## Licenza ⚖️
Tutto il materiale nella repo viene pubblicata con licenza [CC 4.0 BY-NC-SA](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.en)


