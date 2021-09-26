# Configurazione dell'indirizzo mail

Questa guida fornisce un tutorial per la configurazione dell'indirizzo mail del tipo nome@bembus.org. Ad oggi è possibile utilizzare la mail aziendale soltanto sul'applicazione Mail (solo per gli utenti in possesso di un dispositivo Apple) e sull'applicazione web GMail di Google (solo per colore che già posseggono un indirizzo mail del tipo nome@gmail.com). Per poter svolgere le operazioni è necessario avere a portata di mano la mail con le credenziali d'accesso.

## Mail (Mac)

### Configurare la casella di posta 

1. Per configurare l'indirizzo mail personale con l'applicazione Mail di macOS avviare l'applicazione, quindi cliccare su "Mail" > "Aggiungi account".
2. Nella finestra che compare selezionare "Altro account Mail", quindi "Continua".
3. Compilare i campi "Nome", "Indirizzo e-mail" e "Password" indicati nella mail ricevuta che contiene le credenziali per la configurazione dell'indirizzo.
4. Nella schermata successiva accertarsi che la voce "IMAP" sia selezionata in corrispondenza del "Tipo di account", quindi inserire ```imap.ionos.it``` in corrispondenza del campo "Server di posta in entrata" e ```smtp.ionos.it``` per il "Server di posta in uscita". Infine cliccare su "Accedi". Non modificare gli altri campi.
5. Nella finestra successiva accertarsi che sia spuntata l'app Mail, quindi cliccare su "Fine".  

### Creare una firma personalizzata

Al fine di garantire un'adeguata professionalità nei rapporti con l'esterno, si chiede agli utenti di configurare una firma personalizzata in linea con la *corporate identity* di Bembus.
1. Per creare una nuova firma, andare su "Mail" > "Preferenze..." e quindi attivare la scheda "Firme".
2. Cliccare su "+" (in basso a sinistra della sezione centrale) per creare una nuova firma (che si può rinominare con l'etichetta "Bembus" o con un altro nome di facile comprensione), quindi sullo scomparto di destra fare copia e incolla della firma predefinita indicata nel messaggio ricevuto via mail, la cui struttura è riportata sotto. Nell'incollare il testo, si presti attenzione a non alterare la formattazione, ovvero al rispetto delle parti della firma in grassetto.

```
–
*Nome Cognome*
Qualifica

*Bembus*
A knowledge production community in the humanities
www.bembus.org
info@bembus.org
*LOGO ORIZZONTALE*
```

3. Selezionare www.bembus.org, quindi cliccare la combinazione di tasti ```⌘ (Command)+K``` e, sulla finestra che compare, incollare la seguente stringa di testo: ```https://bembus.org```.
4. Quindi selezionare info@bembus.org, cliccare nuovamente la combinazione di tasti ```⌘ (Command)+K``` e, sulla finestra che compare, scrivere: ```mailto:info@bembus.org```.
5. In corrispondenza del logo, trascinare il file denominato "BEM_Logo_signature" fornito in allegato alla mail con le credenziali per l'accesso nella schermata della firma, sotto all'indirizzo mail, senza lasciare una riga vuota. Il logo è riprodotto anche sotto.

![BEM_Logo_signature](https://user-images.githubusercontent.com/68023045/118394478-47e32800-b645-11eb-98dc-c095390a2dee.png)

6. Nella scheda "Firme" aperta al punto 1, nella seconda colonna selezionare la firma creata e spostarla (cioè tenere premuto il tasto del mouse e trascinare) in corrispondenza dell'indirizzo mail in questione (nome@bembus.org) presente nella prima colonna di sinistra.
7. Scorrere la prima colonna di sinistra fino ad individuare l'indirizzo mail in questione (nome@bembus.org), quindi cliccare su di esso.
8. In basso, in corrispondenza della voce "Scegli firma", cliccare sul menu a tendina e selezionare la firma creata.

### Test
Al fine di verificare il funzionamento della mail, nonché la corretta procedura di configurazione della stessa, si chiede di invuare un messaggio di prova a info@bembus.org con un oggetto e un testo a piacere. La firma appena creata deve comparire automaticamente in coda a ogni messaggio e non deve essere inserita manualmente.


## GMail (web browser)

### Configurare la casella di posta 

1. Per configurare l'indirizzo mail personale con l'applicazione GMail di Google occorre aprire l'applicazione _web based_ e fare il login all'indirizzo https://mail.google.com/ utilizzando le credenziali di un altro indirizzo Google personale già posseduto.
2. Nella finestra che compare, cliccare sull'icona a forma di ingranaggio che indica le impostazioni presente in alto a destra (fra il punto di domanda e l'icona a forma di quadrato composta da nove punti), quindi cliccare su "Visualizza tutte le impostazioni".
3. Attivare la scheda "Account e importazione" dal menu orizzontale situato in alto.
4. In corrispondenza della voce "Controlla la posta da altri account", cliccare su "Aggiungi un account email".
5. Nella finestra che compare selezionare "Altro account Mail", quindi "Continua".
6. Nella scheda che compare inserire l'indirizzo mail indicato nella mail contenente le credenziali per la configurazione della casella, quindi cliccare su "Avanti".
7. Nella schermata successiva spuntare "Importa le email dal mio altro account (POP3)" e cliccare su "Avanti".
8. Nella nuova pagina inserire il nome utente (cioè l'indirizzo mail nome@bembus.org) e la password secondo le indicazioni fornite via mail. In corrispondenza di server POP inserire ```pop.ionos.it``` e il numero di porta ```995```. Spuntare la voce "Utilizza sempre una connessione protetta (SSL) quando viene scaricata la posta" e "Applica etichetta ai messaggi in arrivo", quindi cliccare su "Nuova etichetta..." dal menu a tendina e inserire il nome utente fornito via mail. Al termine cliccare su "Aggiungi account".
9. Nella pagina successiva cliccare su "Sì, desidero poter inviare messaggi come nome@bembus.org" e quindi "Avanti".
10. In corrispondenza del campo "Nome", inserire il nome fornito via mail. Attenzione: assicurarsi che la voce "Considera come un alias" **non** sia spuntata.
11. Nella schermata successiva impostare i seguenti record. Per "Server SMTP" scrivere ```smtp.ionos.it```, il numero di porta è ```465```. Compilare con il nome utente (cioè l'indirizzo mail) e la password fornite via mail. Verificare che sia spuntata l'opzione "Connessione protetta tramite SSL (consigliata)", quindi cliccare su "Aggiungi account".

### Verifica dell'account

Dopo aver terminato i passaggi elencati di cui al paragrafo sopra, informare l'amministratore di Bembus della procedura svolta e **attendere che quest'ultimo autorizzi al controllo dell'account**. Solo dopo aver avuto esplicita conferma dell'autorizzazione a controllare l'account, cioè dopo che l'amministratore ha utilizza un codice di verifica o confermato un link, procedere con la creazione della firma.


### Creare una firma personalizzata

Al fine di garantire un'adeguata professionalità nei rapporti con l'esterno, si chiede agli utenti di configurare una firma personalizzata in linea con la *corporate identity* di Bembus.
1. Per creare una nuova firma, andare sulle impostazioni seguendo la procedura indicata al punto 2 del paragrafo "Configurare la casella di posta", quindi attivare la scheda "Generali".
2. In corrispondenza di "Firma", cliccare su "Crea nuova". Rinominare la firma "Bembus" o utilizzare un altro nome di facile comprensione, quindi cliccare su "Crea".
3. Sullo scomparto di destra fare copia e incolla della firma predefinita indicata nel messaggio ricevuto via mail, la cui struttura è riportata sotto. Nell'incollare il testo, si presti attenzione a non alterare la formattazione, ovvero al rispetto delle parti della firma in grassetto.

```
–
Nome Cognome
Qualifica

Bembus
A knowledge production community in the humanities
www.bembus.org
info@bembus.org
*LOGO ORIZZONTALE*
```

4. Selezionare www.bembus.org, quindi cliccare la combinazione di tasti ```⌘ (Command)+K```. Ripetere l'operazione per info@bembus.org. Al termine della procedura i due link devono risultare di colore blu, ovvero essere configurati come collegamenti ipertestuali.
5. In corrispondenza del logo, cliccare sul menu in basso per caricare un'immagine, quindi attivare la scheda "Carica" e fare l'upload del logo inviato via mail (e che si riproduce qui sotto). Assicurarsi di lasciare una riga vuota tra l'indirizzo mail info@bembus.org e il logo.

![BEM_Logo_signature](https://user-images.githubusercontent.com/68023045/118394478-47e32800-b645-11eb-98dc-c095390a2dee.png)

6. In corrispondenza della voce "Impostazioni firma predefinita", selezionare l'indirizzo email in questione, cioè del tipo nome@bembus.org, quindi su "Nuove email" e "Risposte/inoltro" selezionare dal menu a tendina la nuova firma creata.
7. Scorrere fino in fondo alla pagina e cliccare su "Salva modifiche".

### Test
Al fine di verificare il funzionamento della mail, nonché la corretta procedura di configurazione della stessa, si chiede di invuare un messaggio di prova a info@bembus.org con un oggetto e un testo a piacere. La firma appena creata deve comparire automaticamente in coda a ogni messaggio e non deve essere inserita manualmente.
