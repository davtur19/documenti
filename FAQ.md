# FAQ

***DISCLAIMER** Questo documento non vuole essere un dogma. Le informazioni riportate in basso sono principalmente frutto di opinioni di una community, e non sono "scientificamente dimostrate". Se volete proporre nuovi contenuti, siete invitati a fare una pull request.*

### Voglio entrare nel mondo della sicurezza informatica, da dove inizio?
La sicurezza informatica è una specializzazione dell'informatica, quindi una conoscenza informatica "moderna" di base è necessaria:
- Programmazione (algoritmi, strutture dati, ecc.)
- Sistemi Operativi (come funzionano, come interagirci, ecc.)
- Reti (almeno i protocolli fondamentali dello stack tcp/ip)
- Architettura (macchina di Von Neumann, un asm moderno, ecc.)

Se credi di avere già un'infarinatura su questi argomenti, puoi cominciare a studiare i concetti specifici collegati al ramo della sicurezza informatica che più ti interessa. Ad esempio:
- Malware Analysis: focus su asm Intel e ARM, techniche di binary analysis, internals Windows/Android.
- Application Security: focus su sistemi operativi/mitigation, programmazione sicura, classi di vulnerabilità.
- Network Security: focus su protocolli di rete a ogni layer e relative classi di attacco, networking stack dei sistemi operativi.
- Incident Response/Digital Forensics: focus su periferiche e le loro comunicazioni, file system e hard/solid state drive, Windows/Linux internals.

Inutile ricordare che la conoscenza dell'inglese è fondamentale, e viene prima di qualsiasi altra cosa.

### Quali corsi universitari consigliate?
I corsi consigliati sono quelli che coprono gli argomenti elencati nella prima domanda, quindi per la triennale un corso di Computer Science (informatica) o Computer Engineering (ingegneria informatica).
Esistono anche corsi sulla sicurezza informatica triennali o magistrali, in presenza o online.
Per una lista aggiornata dell'offerta accademica in Italia consulta [questa pagina](https://www.consorzio-cini.it/index.php/it/labcs-home/formazione-in-cyber-security-in-italia) sul sito del Consorzio CINI.

### Quale OS consigliate?  
Quello su cui hai più dimestichezza. Se hai bisogno di un sistema operativo particolare è sempre possibile usare una macchina virtuale (ad es. Virtualbox). Ovviamente, se ti interessa imparare un sistema operativo specifico, usa quello come sistema operativo principale.

### Che mi dite di Kali (BackBox, Parrot, BlackArch, ecc...)?
L'unico buon motivo per usare Kali (o qualsiasi altra distribuzione dedicata al pentesting) è la necessità di dover utilizzare un tool per un'occasione singola, per un'emergenza, o per valutarlo senza installarlo sulla propria postazione lavorativa. Non c'è reale motivo per usare una distribuzione dedicata ad un determinato scopo come OS giornaliero, né per studio. Se stai studiando sicurezza informatica, è caldamente installare i tool necessari sulla propria postazione lavorativa o su una VM dedicata; l'installazione stessa del tool, soprattutto se da sorgenti, è componente didattica.

### Quali certificazioni consigliate?
Le certificazioni sono un mezzo efficace tramite il quale un'azienda può dimostrare di avere personale con competenze in un settore, verificate da un ente indipendente e riconosciuto. Sono quindi principalmente uno strumento aziendale e non un percorso formativo:
- Se sei uno studente senza esperienza lavorativa, una certificazione non ti aiuterà a trovare lavoro
- Se sei un lavoratore con esperienza informatica ma SENZA esperienza in ambito sicurezza informatica, una certificazione potrebbe aiutarti a cambiare carriera ma molto probabilmente non sarà sufficiente.
- Se sei un lavoratore con esperienza in ambito sicurezza informatica, una certificazione specifica potrebbe aiutarti a trovare lavoro in caso un'azienda stesse cercando figure certificate in quel determinato ambito, ma anche in quel caso potrebbe non essere sufficiente, dato che non si riuscirebbe a dimostrare esperienza.

In ogni caso, dato che le certificazioni, come detto, sono strumenti aziendali, dovrebbe essere l'azienda a preoccuparsi di certificare i propri dipendenti. Come hai potuto leggere su, sono rari i casi in cui valga davvero la pena investire in una certificazione, e non sempre portano al risultato ottenuto.

## Lista libri e risorse consigliate divisi per categoria

### Crypto
- [Applied Cryptography: Protocols, Algorithms, and Source Code in C](https://www.amazon.it/Applied-Cryptography-Protocols-Algorithms-Source/dp/1119096723/)
- [Serious Crypto](https://nostarch.com/seriouscrypto)

### Sistemi operativi/architettura
- [I moderni sistemi operativi](https://www.amazon.it/moderni-sistemi-operativi-aggiornamento-online/dp/8891901016/)
- [Architettura calcolatori](https://www.amazon.it/Architettura-dei-calcolatori-approccio-strutturale/dp/8871929624/)

### Programmazione
- [Introduction to Algorithms](https://www.amazon.it/Introduction-Algorithms-Thomas-H-Cormen/dp/0262533057/)
- C
  - [King](https://www.amazon.it/Programmazione-C-Kim-N-King/dp/8838785821/)
  - [K&R](https://www.amazon.it/Programming-Language-PROGRAMMING-LANG-English-ebook/dp/B009ZUZ9FW/)
- Assembly
  - [Practical Reverse Engineering](https://www.amazon.it/Practical-Reverse-Engineering-Reversing-Obfuscation-ebook/dp/B00IA22R2Y/)
  - [Modern Assembly Language Programming with the ARM Processor](https://www.amazon.it/Modern-Assembly-Language-Programming-Processor/dp/0128036982/)
- [Rust](https://doc.rust-lang.org/book/)
- [Effective Go](https://golang.org/doc/effective_go.html)
- [Learn Python the Hard Way](https://learnpythonthehardway.org/)

### Networking
- [Reti di calcolatori e internet. Un approccio top-down](https://www.amazon.it/calcolatori-internet-approccio-top-down-aggiornamento/dp/8891902543/)
- [TCP/IP Illustrated: The Protocols: 1](https://www.amazon.it/TCP-IP-Illustrated-Protocols-1/dp/0321336313/)


### OS
- Windows
  - [Windows Internals, Book 1: User Mode](https://www.amazon.it/Windows-Internals-Book-User-Mode/dp/0735684189/)
  - [Accelerated Windows Malware Analysis with Memory Dumps](https://www.amazon.it/Accelerated-Windows-Malware-Analysis-Memory/dp/1908043865/)
- Linux
  - [Understanding the Linux Kernel](https://www.amazon.it/Understanding-Linux-Kernel-Daniel-Bovet/dp/0596005652/)
  - [Guida alla Programmazione in Linux](https://gapil.gnulinux.it/)
- macOS
  - [MAC OS X Internals: A Systems Approach](https://www.amazon.it/MAC-OS-Internals-Systems-Approach/dp/0134426541/)

### Misc
- phrack https://www.phrack.org
- PoC || GTFO https://nostarch.com/gtfo
- PoC || GTFO 2 https://nostarch.com/gtfo2
- The art of exploitation https://www.amazon.com/Hacking-Art-Exploitation-Jon-Erickson/dp/1593271441/

## Wall of Shame: materiale caldamente sconsigliato

- Qualsiasi distro "per il pentest" (Kali, Parrot, ecc.)
- Gli "Hacker" che sentono il bisogno di scriverlo nella bio di Twitter e/o Linkedin
- Qualsiasi corso che in tre semplici lezioni ti farà diventare un hacker etico
- Hacklog e qualsiasi altro videocorso che promette risultati garantiti in 7 giorni
- Qualsiasi religion war relativa a software, sistemi operativi, ecc. Il radicalismo (in qualsiasi ambito) è il tumore del progresso. Gli estremisti fungono da metastasi.

*[in aggiornamento]*
