RandomGroups
============

Questo tool permette di **sorteggiare dei gruppi di persone** da una lista definita in precedenza.

### La lista

Gli elementi della lista possono essere semplici o composti:

+ Maschio (semplice - 1 unità)
+ Femmina (semplice - 1 unità)
+ Coppia (composto - 2 unità semplici: un maschio e una femmina)
+ Composizione (composto - n unità semplici di qualsiasi tipo)

### Vincoli

Gli elementi composti possono essere utili in quanto permettono di definire dei vincoli aggiuntivi, per cui determinate pesone vengono sempre sorteggiate insieme.

Inoltre possono essere definiti degli attributi sugli elementi, per definire ulteriori vincoli.

Per esempio: 
  
l'elemento Giovanni "ha la macchina". "ha la macchina" è un attributo, a cui viene associata la seguente regola:
Per ogni gruppo sorteggiato deve esserci almento un elemento che "ha la macchina".

### Il sorteggio

In fase di sorteggio, si può decidere il numero dei gruppi da sorteggiare.
In base a questo valore, il programma tenterà di creare dei gruppi il più possibile omogenei (con lo stesso numero di unità), vincoli permettendo.

### In futuro..

Un'idea per il futuro sarebbe implementare la parte di "gestione dei contatti":

Ad ogni persona potrebbero essere assegnate le sue informazioni anagrafiche, e farebbe anche comodo un tool automatico per esportare l'elenco in formato PDF, ed eventualmente anche i gruppi sorteggiati.
