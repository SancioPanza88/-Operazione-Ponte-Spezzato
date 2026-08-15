# Operazione Ponte Spezzato

Gioco di strategia tattica WWII in tempo reale, **P2P e senza server**: ogni giocatore
comanda il proprio plotone e le truppe agiscono in autonomia per eseguire gli ordini.

> Ispirazione e materiali originali:
> - Video originale: https://www.youtube.com/watch?v=fbNqWWomgZA&t=1151s
> - Gioco originale: https://www.youdev.it/games/operazione-ponte-spezzato.html

## Come si gioca
1. Apri `index.html` con un doppio click (funziona via `file://`).
2. Scegli una fazione e premi **Entra in battaglia**.
3. Trascina col tasto sinistro per selezionare le tue truppe, poi clicca sulla mappa
   per dare ordini (Muovi, Attacca, Difendi, Sopprimi, Ripiega, Trincera…).
4. Coopera con il tuo blocco, contrasta l'altro blocco e le pattuglie nemiche NPC.

> La prima connessione P2P usa Trystero caricato da `esm.run`: serve una connessione
> internet al primo avvio. Senza rete il gioco resta giocabile in solo-NPC.

## Comandi rapidi
- **1** Muovi · **2** Attacca · **3** Difendi · **4** Sopprimi
- **5** Ripiega · **6** Trincera · **7** Lento · **0** Ferma
- Rotellina: zoom · WASD/frecce o click-destro trascinato: muovi mappa
- **Invio**: chat · **R**: schiera un nuovo plotone

## Tecnologia
- HTML + Canvas 2D, JavaScript (singolo file, nessun build).
- Rete P2P WebRTC tramite [Trystero](https://github.com/mattcg/trystero) (stanza condivisa).
- Sprite dei soldati e dei carri generati (set riusato e tinteggiato per fazione).

## Struttura
```
index.html                       # gioco completo (apri questo)
assets/                          # texture e sprite (erba, acqua, ponti, soldati, carri, fortificazioni, alberi, case)
```

Divertiti sul Ponte Spezzato. 🎖️
