# Progetto-di-Tesi
In questa tesi verrà realizzato un mondo virtuale rappresentante un
vasto bosco e verrà posta particolare attenzione sui metodi di gestione
e ottimizzazione delle risorse, al fine di contenere il più possibile i costi
computazionali.
Una delle tecniche che farà al caso nostro sarà proprio quella della
generazione procedurale.
Come primo passo, verrà sviluppato un sistema di generazione per
porzioni territoriali di forma quadratica; all’interno di ogni sezione sa-
ranno presenti delle aree lungo il perimetro, sulle quali, se il giocatore vi
si trova, verrà generata la porzione di terreno adiacente.
Dopodiché verrà implementato un meccanismo di attivazione e disatti-
vazione delle sezioni generate, il quale consisterà nel mantenere attiva
una porzione quando confinante con quella in cui risiederà il giocatore,
altrimenti verrà disattivata.
Infine avrà luogo la popolazione di queste, collocando sulla loro superfi-
cie, alcuni modelli tridimensionali raffiguranti elementi distintivi di un
bosco; la procedura verrà realizzata attraverso la tecnica del raycasting,
che comporta la proiezione di un numero finito di raggi - definito a priori
in base alla categoria del modello - da una sorgente lungo una direzione
stabilita. 
