# openAPI_exercises

#Several exercises test in yaml

#Exercise Fountain Project
Define the API for the Fountains project (fountains are called Fontanelle or Nasoni in Rome). 
The Fountains project includes a mobile app that allows citizens and tourists to explore nearby drinking fountains.
In Rome, drinking water is available thanks to little public fountains, also known as “nasoni” (“large noses”, due to their nose-like shape). 
They were installed in the late 1800 by the local municipalities in the capital city and nearby areas. More than 2500 are still working. 
The “Fountains” project includes a mobile app that allows citizens and tourists to explore nearby drinking fountains (see their location and status). 
Also, they will be able to change the status or location of any fountains, add missing fountains in the app and remove those that are no more present. 
A fountain’s status is “good” when it is in working condition and “faulty” if it’s broken. 
The app will communicate with a central server via REST and JSON - no information is stored locally in the smartphone. 
No authentication is needed, nor is user identification.

Operazioni richieste:
-	Ricevere la lista di fontane date delle coordinate
-	Segnalare se una fontana funziona o no r/o cambiarne le coordinate
-	Aggiungere una fontana che non è presente
-	Cancellare una fontana che è presente in modo improprio
