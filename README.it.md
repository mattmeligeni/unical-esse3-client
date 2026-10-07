[English](README.md) | **Italiano**

# unical-esse3-client

Piccolo client Python per l'**API REST Esse3** dell'Università della Calabria (Unical): accesso, anagrafica,
insegnamenti, appelli disponibili, prenotazioni e medie, con un menu interattivo da terminale.

È il prototipo con cui ho esplorato e documentato l'API prima di realizzare l'app iOS
**[MyUnical](https://github.com/mattmeligeni/MyUnical)**, ed è archiviato.

![Python](https://img.shields.io/badge/Python-3-3776AB?logo=python&logoColor=white)
![Stato](https://img.shields.io/badge/stato-archiviato-lightgrey)
![Licenza](https://img.shields.io/badge/licenza-PolyForm%20Strict%201.0.0-lightgrey)

## Cosa copre

| Area | Servizi |
| --- | --- |
| Autenticazione | `/login` (HTTP Basic) |
| Anagrafica e carriera | dati anagrafici, tratti di carriera, corso di studi |
| Esami | appelli disponibili per insegnamento, dettaglio, appelli prenotati |
| Medie | media ponderata e aritmetica dal servizio libretto |

## Uso

```bash
pip install -r requirements.txt
python play.py      # chiede le credenziali Unical (mai salvate) e apre il menu
```

`api_client.py` contiene la classe `UnicalApiClient` usata dal menu.

## Licenza

Codice consultabile con la [PolyForm Strict License 1.0.0](LICENSE): si può leggere ed eseguire per scopi non
commerciali; non si può modificare, ridistribuire né usare commercialmente senza permesso scritto.

---

<sub>© 2024-2026 [Mattia Meligeni](https://mattiameligeni.com) · Non affiliato all'Università della Calabria né a Cineca.</sub>
