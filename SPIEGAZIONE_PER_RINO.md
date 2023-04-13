# esercizioBackendW5D2

Parto dalle soluzioni dell'esercizio del primo giorno. Ho creato i due enum Stato e StatoOrdine, le classi Tavolo, Ordine, ListaOrdini, e la classe OrdineRunner che
implementa CommandLineRunner. La logica in di creaOrdine in OrdineRunner è da sistemare, mi sono intanto focalizzato sullo stampare qualcosa in console per verificare
il funzionamento. 
@Value("${order.costocoperto}") private double costoCoperto nella classe Ordine non prende il valore da application.properties, non capisco perchè.
