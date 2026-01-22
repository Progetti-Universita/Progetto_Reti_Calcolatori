# Progetto Reti Calcolatori

Simulare un terminale remoto simile a Secure Shell (SSH). Utilizzare il modello client/server, con server che è in grado di gestire connessioni multiple. La connessione è possibile solo ad utenti registrati (utilizzare un file per memorizzare gli utenti)
L'utente deve essere in grado di:
•	Connettersi alla macchina remota tramite username (es. NomeApplicativo bob@127.0.0.1)
o	Il server deve chiedere la password per poter procedere
•	Cambiare la propria password:
o	Comando: passwd
Il terminale deve permettere:
•	La navigazione nel file system remoto
o	Comandi: ls, cd,  
•	Creare file, directory:
o	Comandi: mkdir, touch
•	Copiare, rinominare, spostare e cancellare file:
o	Comandi: cp, mv, rm
•	Uscire dalla sessione:
o	Comando: exit

## Installazione

1. Clona il repository:
   git clone https://github.com/lpappa/Progetto_Reti_Calcolatori.git
2. Apri il progetto con Eclipse o IntelliJ
3. Compila ed esegui

## Uso

Esempio:

```java
UserManager manager = new UserManager();
manager.createUser("Mario");
```

## Licenza

Questo progetto è sotto licenza MIT.

Copyright (c) 2026 Luigi Pappa.

