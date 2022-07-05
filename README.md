# Montenero_Stiratrice

V 1.0  
27/06/2022  
Versione con homing di nastro, sagome, impilatore verticale ed impilatore orizzontale.  
Da aggiungere: ciclo automatico corretto  

V 1.01  
27/06/2022  
Modificato l'homing per far si che avvenga all'accensione e ad ogni marcia preceduta dal fungo.  
*La PT-100 che legge male ora ha un valore a display diviso per 2 in modo che sembri OK ma non lo è!!!*  
Modificato il ciclo per far si che il nastro parta contemporaneamente alla chiusura delle sagome.  

V 1.02  
05/07/2022  
Modificato il ciclo, ora l'impilatore durante il lavoro appena tocca il finecorsa esterno inizia a rientrare.   
Fatto il reset dei comandi manuali quando si va in marcia, inoltre è possibile azionarli solo in arresto e se non si è in allarme (variabile BOOL via_libera).  
Fixato il bug per cui anche se la pressa non era abilitata, se il tempo di pressa era diverso da 0, questa si azionava ugualmente, ora se il tempo di pressa è a zero o l'abilitazione è su FALSE il pistone rimane sempre su.  

