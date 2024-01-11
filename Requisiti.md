WebApp per la gestione dell'energia

<br>PROBLEMA</br>
Gestire l'energia per un minore consumo con conseguente minore impatto ambientale, avere un resoconto sui propri consumi e gestire il proprio contratto in maniera facile e intuitiva

Funzionalità
1. Gestione del contratto luce e gas: Permette di gestire il contratto di fornitura di energia direttamente dall'app.
2. Comunicazione dell'autolettura del contatore: Comunica la lettura del  contatore di ogni cliente.
3. Pagamento della bolletta: Pagare la bolletta con carta di credito o Paypal.
4. Richiesta della domiciliazione della bolletta: Richiedere che la bolletta venga inviata direttamente a casa.
5. Richiesta della Bolletta Web: Richiedere di ricevere la bolletta in formato digitale.
6. Monitoraggio dei consumi energetici: Permette di vedere l'andamento dei  consumi quasi in tempo reale.
7. Gestione delle pratiche relative all'utenza: Seguire la gestione delle pratiche relative all'utenza, come voltura, subentro o gestione guasto.
8. Comunicazione con il centro assistenza: Comunicare velocemente con il centro assistenza per risolvere eventuali problemi.

DIAGRAMMA UML
<img src="https://yuml.me/diagram/usecase/[Utente%20visitatore]-(Sign%20In),[Utente%20visitatore]-(Ricezione%20bolletta),(Ricezione%20Bolletta)%3E(Bolletta%20Telematica),(Ricezione%20Bolletta)%3E(Bolletta%20Cartacea),(Sign%20In)%3C(Cambio%20Password),(Sign%20In)%3E(Compra%20un%20Piano),[Utente%20Autenticato]-(Compra%20un%20piano),(Compra%20un%20piano)%3E(Checkout),[Utente%20Autenticato]-(Problemi),(Problemi)%3C(Comunicazione%20centro%20assistenza),[Utente%20Autenticato]-(Gestione%20del%20contratto),(Gestione%20del%20contratto)-(Luce),(Gestione%20del%20contratto)-(Gas),(Luce)%3C(Pagamento%20bolletta),(Gas)%3C(Pagamento%20bolletta),[Utente%20Autenticato]-(Pagamento%20Bolletta),(Pagamento%20Bolletta)%3E(Checkout),(Checkout)-(Aggiungi%20una%20carta),(Aggiungi%20una%20carta)%3E[Staff%20bancario],">

WBS
![Pietro Moscheni WBS-1](https://github.com/MoscheniPietro/Progetto-GEP/assets/101174884/300ca8bf-ad07-42ea-baec-3e423de94bdd)


<br>VALUE PROPOSITION</br>
WebApp per la gestione dell'energia 
<br><b>Titolo</b></br>
Fai una scelta semplice e sostenibile con la nostra app.
<br><b>Sottotitolo</b></br>
Con la nostra app hai un esperienza integrata e intelligente per gestire l'energia in modo ottimizzato e sostenibile.
<br><b>Lista dei Benefici</b>
<br>Questa soluzione offre:
<br>Riduzione del consumo energetico
<br>Facilità di gestione del contratto
<br>Comunicazione efficiente con il centro assistenza
<br>Pagamenti sicuri
<br>Digitalizzazione delle pratiche utente
<br>Trasparenza dei consumi
<br>Gestione semplificata delle pratiche utente</br>
<br><b>Visual<b></br>
![_29477981-aec4-43ab-8f10-6d0a5446d006](https://github.com/MoscheniPietro/Progetto-GEP/assets/101174884/39b6773b-bd94-4668-94b9-c457414984b8)

<br>USER STORIES</br>
Titolo:Monitoraggio del consumo energetico
<br>Come:Utente abbonato al servizio EnergyHub
<br>Voglio: Monitorare il consumo energetico in tempo reale.
<br>In modo che: Possa individuare i comportamenti energetici inefficienti e apportare modifiche per la riduzione del consumo e il miglioramento dell'efficienza.
<br>Criteri d'accettazione:
1)Visualizzazione dei dati di consumo energetico attuali nell'abitazione attraverso l'interfaccia utente di EnergyHub.
2)La visualizzazione del consumo energetico deve essere aggiornata in tempo reale.
3)Selezionare intervalli di tempo specifici per analizzare i dati di consumo passati.
4)L'interfaccia utente deve fornire grafici chiari e intuitivi per rappresentare il consumo energetico.
5)Ricevere notifiche immediate in caso di picchi anomali di consumo.
