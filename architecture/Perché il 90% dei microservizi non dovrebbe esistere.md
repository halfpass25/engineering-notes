2026-13-01


I microservizi vengono spesso raccontati come una conquista di maturità:

quando cresci, separi,
quando scali, spezzi,
quando sei serio, distribuisci.

Peccato che, nella pratica, la maggior parte dei microservizi non nasca per necessità, ma per insicurezza.

Insicurezza del team, o sul codice o, ancora, sulle decisioni prese in precedenza.


E' così che il microservizio diventa più una specie di rifugio psicologico
con al pia illusione che  “se separo, almeno non rompo tutto.”

Il problema è che separare non significa capire.

Molti sistemi hanno origine come monoliti confusi:logica sparsa, regole implicite, 
responsabilità poco chiare.
E laddove ci si dovrebbe fermare a fare chiarezza, si prende una scorciatoia: si spezza tutto in microservizi.

E che cosa si ottiene, di norma? Che la confusione continua a regnare indisturbata, solo...distribuita!
Stesse ambiguità, ma con una rete in mezzo
Stessi errori concettuali, moltiplicati per "n" servizi.
Non so cosa ne pensiate voi, ma per me, questo non è fare architettura, è replicare il problema,
modificando solo le sue sembianze.

C’è una verità scomoda che raramente viene detta o se detta, spesso rapidamente dimenticata:

"I microservizi funzionano bene solo quando il dominio è già stato capito molto bene."

Il fatto è che si fraintende la vera "comprensione" con:

-sapere quali endpoint servono
-sapere quali tabelle esistono

Comprensione vera, dovrebbe essere invece:

-sapere dove inizia e dove finisce una responsabilità
-sapere chi decide cosa
-sapere quali regole non devono mai essere violate

Se tutto questo non è già chiaro in un monolite, non lo diventerà per magia,
frammentandolo in microservizi. Anzi: diventerà ancor più complesso individuare
i confini di ogni blocco funzionale che realizza il sistema.

AL contrario, unnmonolite ben progettato ha un enorme vantaggio 
che si tende a sottovalutare: è osservabile.

Si può infatti:

-seguire un flusso dall’inizio alla fine
-capire dove nasce una decisione
-vedere l’impatto reale di una modifica

mentre in  molti sistemi a microservizi, invece:

-il comportamento emerge dalla somma delle interazioni
-gli effetti collaterali sono lontani dalla causa
-il debugging diventa un lavoro investigativo

Conclusione: la desiderata scalabilità, finisce per tradursi in opacità.

C'è poi un altro aspetto che, mentre si parla di questioni puramente tecniche,
tende a passare del tutto inosservato ma non meno letale: i microservizi vengono 
spesso giustificati con il lavoro dei teams.

“Così i teams sono indipendenti.”

Ma anche qui, l’indipendenza tecnica non risolve la mancanza di coordinamento 
umano,la nasconde.

Se i teams non parlano (o peggio ancora, comunicano male), non condividono il modello,
non sono allineati sugli obiettivi, i microservizi non li rendono più efficienti ma solo
più distanti.

E questa frammentazione anche sul piano umano, fa sì che se qualcosa va 
storto, nessuno “possiede” davvero il problema.

Ma attenzione: questo non significa che i microservizi siano il male assoluto.

Sto solo dicendo che arrivano dopo, non prima, che sono una conseguenza, 
non una strategia e che servono quando è il sistema, a spingere per essere separato, 
non perché qualcuno lo decide a tavolino.

Evidenziate le criticità appena esposte, diciamoci le cose come stanno: molti sistemi 
non hanno bisogno di microservizi.
Hanno bisogno di:

-confini chiari
-regole esplicite
-responsabilità ben definite

E queste cose si possono (e più spesso che no si dovrebbero) costruire dentro un monolite.

La domanda da porci, pertanto, non è: “dovremmo passare ai microservizi?”

ma:

“siamo davvero in grado di spiegare il nostro sistema senza disegnarlo a blocchi?”

Se la risposta è no, i microservizi non sono il passo successivo.
Sono solo un modo elegante di rimandare il problema.

E i problemi rimandati, in architettura -si sa-, tornano sempre con gli interessi.

Sempre lieto di sentire la vostra opinione nei commenti!

-Pasquale-  (halfpass25)
