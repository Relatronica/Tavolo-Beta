<p align="center">
  <img src="materiali/logo/tavolo-beta-logo.png" alt="Logo Tavolo Beta: tavolo rotondo con otto sedie, una libera" width="140">
</p>

# Tavolo Beta

> Il movimento di chi ha smesso di aspettare che lo faccia qualcun altro.

**Stato: bozza 0.1.** Nome provvisorio. Tutto quello che trovi qui è un'ipotesi da mettere alla prova, non una regola.

Tavolo Beta è prima un metodo, poi un movimento. L'unità di base è un **tavolo**: da cinque a dodici persone, novanta minuti, una decisione da realizzare entro due settimane.

Questo repository è l'**archivio di approfondimento**: la documentazione, la teoria e la storia delle scelte, per chi vuole capire come funziona, studiarlo, criticarlo o copiarlo. Per organizzare una serata non serve leggere niente di quello che c'è qui: basta la [guida alla serata](formato/serata.md).

## Da dove partire

| Se vuoi... | Leggi |
|---|---|
| Organizzare un tavolo | [formato/organizza-un-tavolo.md](formato/organizza-un-tavolo.md) e poi [formato/serata.md](formato/serata.md) |
| Capire il metodo e i suoi principi | [teoria/modello-e-principi.md](teoria/modello-e-principi.md) |
| Sapere perché esiste | [teoria/diagnosi.md](teoria/diagnosi.md) |
| Sapere cosa non abbiamo ancora deciso | [teoria/domande-aperte.md](teoria/domande-aperte.md) |
| Sapere come può fallire | [teoria/rischi.md](teoria/rischi.md) |
| Vedere perché abbiamo scelto così | [decisioni/](decisioni/) |
| Studiare le fonti | [studio/bibliografia.md](studio/bibliografia.md) |
| Vedere come cambia il formato | [CHANGELOG.md](CHANGELOG.md) |

## Struttura

```
tavolo-beta/
├── README.md
├── LICENZA.md               # provvisoria: la licenza va ancora scelta
├── CHANGELOG.md             # versioni del formato
├── CONTRIBUTING.md          # come contribuire, in italiano semplice
├── teoria/                  # modello, principi, rischi, domande aperte
├── formato/                 # serata, regole, temi, scheda esito
├── decisioni/               # un file per ogni scelta: cosa e perché
├── studio/                  # bibliografia commentata
├── esiti/                   # archivio degli esiti (solo anonimizzati)
└── materiali/               # logo e slide esportate
```

## Principi di questo repository

- **I testi sono la fonte, le slide sono un'esportazione.** Se un contenuto cambia, si cambia qui e poi si rigenerano le slide.
- **Niente dati personali.** Nomi, contatti e foto non vanno mai in questo repository: la cronologia di Git non dimentica. Vedi [esiti/README.md](esiti/README.md).
- **Le versioni sono numerate.** Ogni modifica al formato finisce nel [CHANGELOG](CHANGELOG.md), con il motivo.
- **Si misura una cosa sola:** alla terza volta, le persone tornano?

## Licenza

Ancora da decidere (è la domanda 3 delle [domande aperte](teoria/domande-aperte.md)). Fino ad allora, vedi [LICENZA.md](LICENZA.md).
