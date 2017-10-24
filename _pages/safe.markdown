---
layout: page
title: Safe
permalink: /safe/
---

Safe ti consente di annotare le tue credenziali scolastiche (nome utente e tutte le password) in un posto protetto, eliminando il peso di dimenticarti delle troppe password. Safe è accessibile dall'omonima voce nel menù laterale  

# Configurazione iniziale
Durante il primo accesso a Safe sarà richiesta l'immissione di una password personale che consente di proteggere le tue credenziali da occhi indiscreti. La password non deve rispettare nessun criterio specifico, anche se le password alfanumeriche con più di 8 caratteri sono raccomandabili.  

# Accedere a Safe
All'apertura della schermata di Safe verrà richiesto di effetuare l'autenticazione immettendo la password precedentemente scelta. I dispositivi dotati di lettore d'impronte digitali con almeno un'impronta registrata potranno utilizzare semplicemente il lettore d'impronte stesso per effettuare l'accesso senza inserire la password.
Una volta completato l'accesso sarà possibile annotare le proprie password e nome utente nei campi di testo. Una volta terminata l'operazione sarà necessario salvare premendo il pulsante "V" presente in basso. 

# Cambio di password
Nel caso in cui si volesse cambiare password basterà effettuare l'accesso a Safe e toccare sull'icona "_Ripristina_" in alto a destra. Resettando la password tutte le credenziali salvate in Safe saranno eliminate, quindi è consigliabile annotare temporaneamente le credenziali salvate prima di cambiare password.  

# Errori di sicurezza
Nel caso in cui il dispositivo in uso non sia in grado di fornire un adeguato livello di sicurezza, l'accesso a Safe sarà vietato.  
 * Errore 1: non è stato possibile completare il test della sicurezza. Verifica la connessione ad internet e riprovare
 * Errore 2: il test d'integrità del dispositivo (SafetyNet) è fallito. Verifica che il dispositivo stia eseguendo un software non compromesso
 * Errore 3: SELinux permissivo / disattivato. Il sistema di sicurezza SELinux non è attivo e pertanto non è garantita la sicurezza del dispositivo. Verifica che il dispositivo stia eseguendo un software compromesso.
 * Errore 4: applicazione manevola rilevata. È stata rilevata un'app in grado di compromettere la sicurezza del dispositivo. Verifica la presenza di app in grado di alterare le funzioni basilari del dispositivo e rimuovila.
 * Errore 5: la versione dell'app in uso non è valida. Disinstalla l'app e reinstallala dal Play Store.

# Come viene garantita la sicurezza dei dati archiviati?
Safe archivia le credenziali in formato criptato con chiave AES a 256bit in una partizione protetta del dispositivo. Detto in parole povere i dati vengono salvati in un formato illeggibile e molto complesso da "decodificare" da tutto ciò che non è l'app stessa. Prima di effettuare l'accesso viene verificata l'integrità del dispositivo e dell'app stessa al fine di impedire tentativi di estrazione dei dati archiviati.  