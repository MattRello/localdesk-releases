LocalDesk
LocalDesk è un'app per Windows che tiene in un posto solo scadenze, soldi, lista della spesa, documenti importanti, contatti e lo stato del computer. Tutto resta sul tuo PC, cifrato: niente account, niente pubblicità, nessun dato inviato a nessuno.

Cosa serve
Windows 10 o 11 a 64 bit.
Nient'altro: non servono permessi di amministratore né altri programmi.
Come si installa
Apri l'ultima versione e, in fondo alla pagina, sotto Assets, scarica il file LocalDesk_…_x64-setup.exe.
Apri il file scaricato.
Windows può mostrare «Windows ha protetto il PC». Succede perché l'installer non ha una firma a pagamento, non perché sia pericoloso. Premi Ulteriori informazioni, poi Esegui comunque.
Segui l'installazione: bastano pochi clic. Alla fine LocalDesk si apre e i Primi passi ti guidano nelle prime scelte.
Come si aggiorna
Non serve riscaricare nulla: in LocalDesk vai in Impostazioni → Informazioni e premi Cerca aggiornamenti. Se c'è una versione nuova, vedi cosa cambia e scegli Aggiorna ora. LocalDesk fa prima una copia di sicurezza dei dati, poi si chiude e si riapre aggiornato.

Privacy
LocalDesk usa Internet solo quando premi «Cerca aggiornamenti»: in quel momento chiede a questa pagina se c'è una versione nuova. Non invia i tuoi dati, né allora né mai.

Fai un backup
I dati sono cifrati e legati al tuo account di Windows. Per non perderli, e per spostarli su un altro PC, usa il backup in Impostazioni → Backup: scegli una password e una cartella (meglio una chiavetta o una cartella di OneDrive) e, se vuoi, fallo partire da solo ogni settimana.

Ricorda la password del backup: senza, il backup non si apre e nessuno può recuperarlo.
Nuovo PC: installa LocalDesk, nel primo passo scegli «Ho già un backup: ripristinalo» e indica il file. Copiare a mano la cartella dei dati non funziona.
Disinstallare
Da Impostazioni di Windows → App → App installate → LocalDesk → Disinstalla. I tuoi dati restano sul PC, a meno che tu non spunti la casella per cancellarli. Prima di cancellarli fai un backup.

Controllare il file scaricato (facoltativo)
Sotto ogni versione trovi l'impronta SHA-256 dell'installer. Per controllare che il file sia integro, apri PowerShell nella cartella dei download e scrivi:

Get-FileHash .\LocalDesk_0.3.0_x64-setup.exe -Algorithm SHA256

Il valore deve essere uguale a quello scritto nella pagina della versione.

Problemi
Scrivi a chi ti ha consigliato LocalDesk, dicendo la versione (in Impostazioni → Informazioni) e cosa stavi facendo.

Le licenze dei componenti usati da LocalDesk sono nel file LICENZE-TERZE-PARTI.txt allegato a ogni versione.# localdesk-releases
