# Regolamento Informatico
Regolamento Informatico in vigore presso il Comune di Piove di Sacco (PD)

## Introduzione
La progressiva diffusione delle nuove tecnologie informatiche, e l'accesso alla rete Internet dai Personal Computer, espone il Comune di Piove di Sacco ai rischi di un coinvolgimento sia patrimoniale che penale, creando problemi alla sicurezza e all’immagine del Comune stesso.
Premesso quindi che l’utilizzo delle risorse informatiche e telematiche del Comune deve sempre ispirarsi al principio della diligenza e correttezza, comportamenti che normalmente si adottano nell’ambito di un rapporto di lavoro, il Comune di Piove di Sacco ha adottato un Regolamento interno diretto ad evitare che comportamenti inconsapevoli possano innescare problemi o minacce alla sicurezza nel trattamento dei dati.

## Come consultare il Regolamento all'ultima versione
E' possibile consultare online il Regolamento Informatico attualmente in vigore [cliccando qui](regolamento_informatico_comunale.md).  
In alternativa sono disponibili file di tipo PDF presso il sito ufficiale del Comune di Piove di Sacco nella sezione [Regolamenti](https://piovedisacco.trasparenza-valutazione-merito.it/web/trasparenza/dettaglio-trasparenza?p_p_id=jcitygovmenutrasversaleleftcolumn_WAR_jcitygovalbiportlet&p_p_lifecycle=0&p_p_state=normal&p_p_mode=view&p_p_col_id=column-2&p_p_col_count=1&_jcitygovmenutrasversaleleftcolumn_WAR_jcitygovalbiportlet_current-page-parent=12501&_jcitygovmenutrasversaleleftcolumn_WAR_jcitygovalbiportlet_current-page=12503), oppure in forma cartacea su richiesta presso il nostro [Ufficio Personale](https://www.comune.piovedisacco.pd.it/it/organizational_unit/10356).  

## Come so se il Regolamento che sto leggendo è quello approvato dagli Organi di Governo Comunali?
Ottima domanda che necessita di una risposta adeguata.
I Regolamenti Comunali sono Atti del Comune che devono essere approvati e poi emanati dal Consiglio Comunale. Per verificare se il regolamento che stai leggendo è esattamente quello approvato ed emanato dal Consiglio è necessario che siano soddisfatte due condizioni:  
- [\[1\]](#1) L'hash del file del regolamento è lo stesso che viene riportato nella delibera di Consiglio.
- [\[2\]](#2) La delibera di Consiglio firmata digitalmente supera tutti i controlli delle firme digitali.
  
\[1\] <a name="1"></a>  
Il primo punto si ottiene scaricando il file del regolamento che stai leggendo o di cui intendi verificare la validità e calcolando il suo hash con un algoritmo `SHA-256`. Questa attività si esegue facilmente sia con sistema operativo Windows che Linux e MacOS, andando al prompt dei comandi del S.O. e digitando il comando:
- `certutil -hashfile "C:\percorso\regolamento_informatico_comunale.md" SHA256` nel caso di S.O. Windows.
- `sha256sum /percorso/regolamento_informatico_comunale.md` nel caso di S.O. Linux.
- `shasum -a 256 /percorso/regolamento_informatico_comunale.md` nel caso di S.O. MacOS.

In qualsiasi caso, sostituire la stringa `/percorso` con il percorso dove si trova il file `regolamento_informatico_comunale.md` che avete scaricato. 
Questa funzione ritornerà una stringa alfanumerica di 64 caratteri simile alla seguente: `3f7a1a06f86a6f90eb835a410b02df4b242669a7d5e6bde228a6cf6b4ce84c8a`, questa stringa rappresenta l'impronta del documento e rimmarrà immutata fintantoché il documento controllato non sarà modificato. Pertanto, con la stringa ricavata dalla funzione di hashing, si va a controllare se  corrisponde alla stringa riportata nella Delibera di Consiglio.  
Se gli hash coincidono, significa che il file non è stato alterato, se gli hash sono diversi, il file è stato modificato o corrotto.  
> 💡 _Suggerimento<br>
> Se volete scaricare i file del regolamento, quello più recente e approvato lo troverete all'interno dell'archivio "**Source code.zip**" presente a questo [**link**](https://github.com/Matteo-PioveDiSacco/Regolamento_Informatico/releases) nella sezione che mostra l'etichetta_ `Latest` _a fianco. All'interno dello zip troverete il file_ `regolamento_informatico_comunale.md` _che contiene l'ultimo regolamento approvato. Sempre al link fornito in precedenza, troverete i file di tutte le altre versioni passate._

<br> 

\[2\] <a name="2"></a>  
Il secondo punto si completa semplicemente verificando che il file dell'Atto di approvazione del Regolamento superi tutti i controlli previsti dalla verifica della firma digitale, solitamente deve essere impiegato un software di terze parti come [Dike](https://www.firma.infocert.it/) o [Aruba Sign](https://www.pec.it/firma-digitale.aspx), in alcuni casi è possibile servirsi di verificatori on-line che non necessitano di installazione di software nel PC. Se il file supera i controlli allora significa che il contenuto non è stato modificato e quindi si tratta di un atto ufficiale regolare, altrimenti il file non è valido e deve essere considerato corrotto o modificato senza permesso.  
Concludendo, se entrambe le verifiche danno esito positivo allora quello che state leggendo è esattamente il Regolamento approvato dal Consiglio Comunale, altrimenti è possibile che uno dei documenti (o entrambi) sia stato corrotto o modificato senza permesso e pertanto bisogna scartarlo.

