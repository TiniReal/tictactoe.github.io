# Progetto Vue.js 1 di Thomas Tinelli
# Tic Tac Toe 

Benvenuti nel progetto Tic Tac Toe, un mini-sito del famoso gioco Tris sviluppato con Vue, TypeScript e Vite. Questo progetto offre una semplice interfaccia grafica per giocare a Tris, dove due giocatori possono alternarsi cliccando sui riquadri di una griglia 3x3.

## Funzionalità

- **Griglia 3x3**: Una griglia di gioco interattiva di 3x3 caselle.
- **Alternanza dei Turni**: I giocatori si alternano tra X e O ad ogni click sulla griglia.
- **Reset del Gioco**: Possibilità di resettare la griglia e iniziare una nuova partita.

## Requisiti

- Node.js v14 o superiore
- npm v6 o superiore

## Installazione

1. **Clonare il Repository**
   
2. **Installare le Dipendenze**
  
3. **Avviare l'Applicazione**
   
## Struttura del Progetto

- **src/**: Contiene i file sorgenti del progetto.
  - **components/**: Contiene i componenti Vue.
    - `TicTacToe.vue`: Il componente principale della griglia di gioco.
    - `Square.vue`: Il componente per ogni singola casella della griglia.
  - **App.vue**: Il componente principale dell'applicazione.
  - **main.ts**: Il file di ingresso dell'applicazione.
- **public/**: Contiene i file statici.
- **vite.config.ts**: Configurazione di Vite.

## Licenza

Questo progetto è rilasciato sotto la licenza MIT. Vedi il file [LICENSE](./LICENSE) per maggiori dettagli.

---

### Tecnologie Utilizzate

- [Vue 3](https://v3.vuejs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Vite](https://vitejs.dev/)

### Esempio di Utilizzo

1. **Avvio del Gioco**: Una volta avviata l'applicazione, si vedrà una griglia vuota 3x3.
2. **Alternanza di X e O**: Cliccando su una casella, essa verrà riempita con una X o una O, alternando ad ogni click.
3. **Vincitore**: Continuare a giocare fino a completare una linea di tre simboli uguali (orizzontale, verticale o diagonale).

Divertiti a giocare a Tic Tac Toe!
