# Offline Hash Generator
Calcolatore di hash offline e orientato alla privacy (i file restano sul dispositivo e non viaggiano in rete). Genera hash SHA-1, SHA-256, SHA-384 e SHA-512.

> Calcola hash dei file mantenendo i dati sul tuo dispositivo.
> Nessun upload. Nessun server. Solo elaborazione locale. Rispetto totale della privacy.

**Offline Hash Generator** permette di generare hash direttamente nel browser senza caricare file online.

Supporta:

- SHA-1
- SHA-256
- SHA-384
- SHA-512

L'elaborazione avviene **interamente sul dispositivo dell'utente**, utilizzando funzionalità crittografiche integrate nel browser (Web Crypto API).

---

## Perché questo progetto?

Molti strumenti online per il calcolo di hash richiedono il caricamento dei file su server esterni.

Per documenti riservati, file di lavoro o dati sensibili, questo può rappresentare un rischio o semplicemente una limitazione indesiderata.

**Offline Hash Generator** nasce con un obiettivo semplice:

> consentire il calcolo di hash senza che i file lascino mai il computer dell'utente.

---

## Funzionalità

✅ Trascinamento file (drag & drop)  
✅ Supporto a più algoritmi di hashing  
✅ Copia rapida dei singoli hash  
✅ Copia simultanea di tutti gli hash  
✅ Visualizzazione metadati del file  
✅ Elaborazione completamente locale  
✅ Nessuna dipendenza esterna  
✅ Funziona anche offline dopo il caricamento della pagina  

---

## Privacy

Tutti i calcoli vengono eseguiti direttamente nel browser.

I file:

- non vengono caricati online;
- non vengono inviati a server esterni;
- non vengono memorizzati;
- non vengono condivisi;
- non vengono analizzati da servizi terzi.

Il codice sorgente è pubblico e verificabile.

---

## Compatibilità browser

Compatibile con i browser moderni:

- Chrome
- Edge
- Firefox
- Safari
- Opera
- Brave
- Browser mobili aggiornati

**Internet Explorer non è supportato.**

---


## Installazione

Clonare il repository:

```bash
git clone https://github.com/StatisticianPlusPlus/Offline-Hash-Generator.git
```

oppure scaricare il file ZIP dal repository GitHub.

Aprire:

```text
index.html
```

direttamente nel browser.

Non è richiesta alcuna installazione.

---

## Utilizzo

1. Aprire la pagina;
2. Trascinare un file nell'area dedicata oppure selezionarlo;
3. Scegliere gli algoritmi desiderati;
4. Premere:

```text
Calcola hash
```

5. Copiare il risultato.

---

## Nota sugli algoritmi

**SHA-1** è mantenuto principalmente per compatibilità con sistemi legacy.

Per verifiche di integrità più robuste si raccomanda:

- SHA-256
- SHA-512

---

## Tecnologie utilizzate

- HTML5
- CSS3
- JavaScript Vanilla
- Web Crypto API (browser)

---

## Possibili sviluppi futuri

- Verifica hash atteso ↔ hash calcolato
- Elaborazione batch di più file
- Esportazione risultati TXT / CSV
- Tema scuro
- Supporto ad algoritmi aggiuntivi

---

## Licenza

Distribuito con licenza MIT.

Utilizzabile, modificabile e condivisibile liberamente.
