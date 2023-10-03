Boolzapp
===
### Milestone 1
Replica della grafica con la possibilità di avere messaggi scritti dall’utente (verdi) e dall’interlocutore (bianco) assegnando due classi CSS diverse
Visualizzazione dinamica della lista contatti: tramite la direttiva v-for, visualizzare nome e immagine di ogni contatto
### Milestone 2
Visualizzazione dinamica dei messaggi: tramite la direttiva v-for, visualizzare tutti i messaggi relativi al contatto attivo all’interno del pannello della conversazione
Click sul contatto mostra la conversazione del contatto cliccato
### Milestone 3
Aggiunta di un messaggio: l’utente scrive un testo nella parte bassa e digitando “enter” il testo viene aggiunto al thread sopra, come messaggio verde
Risposta dall’interlocutore: ad ogni inserimento di un messaggio, l’utente riceverà un “ok” come risposta, che apparirà dopo 1 secondo.


### Svolgimento

1. creare la struttura in html con un div che contiene tutto e un altro div che contiene "l'app" e altri due div interni
1. creare la lista su js dei messaggi
1. nel lato sinistro creo i div per (utente, notifiche, input e per i contatti) 
1. nei contatti faccio un for in
1. nel lato sinistro creo la la chat, input chat e l'utente della conversazione
1. aggiungo la classe active al click del contatto