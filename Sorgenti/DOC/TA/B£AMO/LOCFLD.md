# Componente FLD

- [Abstract](Sorgenti/DOC/TA/B£AMO/LOCFLD_F00)

## Funzionalità
- [Abstract](Sorgenti/DOC/TA/B£AMO/LOCFLD_F00)
- [Tipi di campo](Sorgenti/DOC/TA/B£AMO/LOCFLD_F01)
- [Personalizzazione grafica](Sorgenti/DOC/TA/B£AMO/LOCFLD_F02)
- [Dinamismi](Sorgenti/DOC/TA/B£AMO/LOCFLD_F03)
- [Opzioni](Sorgenti/DOC/TA/B£AMO/LOCFLD_F04)

## Formato dei dati
Questo componente viene alimentato da un xml di tipo albero.

## Dinamismi
Il componente FLD lancia l'evento 'Change' quando viene modificato il valore del cambio dell'input.
L'evento 'Click' viene invece chiamato quando viene premuto il pulsante di conferma (o quando viene premuto il tasto INVIO nel campi che lo permettono, come ad esempio l'inputtext).

In entrambi i casi, al dinamismo vengono aggiunte le seguenti variabili : 
1) Tipo / Parametro / Codice del field
2) Eventuali variabili di riga associate all'elemento selezionato (ad esempio, nel caso in cui il campo sia una combo o un radio button)

## Schede di esempio
Scheda d'esempio, esclusiva per WebUP

 :  : DEC K(Esempi) D(Sezione specifica per il web) X(F(EXD;\*SCO;) 1(V2;JAGRA;FLD) 2(MB;SCP_SCH;WETEST_FLD)) L(1)
