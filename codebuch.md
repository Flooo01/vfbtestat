Codebuch

*Stand 2022-05-19*


Daten erhoben von: https://www.transfermarkt.de/vfb-stuttgart/startseite/verein/79

	
edgelist

from: initiierender Knoten, in diesem Fall: Vorheriger Verein, Nationalität oder Rückennummer des Spielers

to: erhaltender Knoten, in diesem Fall: Rückennummer des Spielers oder Nationalität

weight: Transfersumme in 100.000 Euro Schritten, gerundet falls abweichend.

season: Jahr des Transfers (nur erste Jahreszahl des Transferfensters als JJJJ verwendet)


	
nodelist

id: Identische IDs wie aus der edgelist, in diesem Fall: Rückennumer, Vereinsname oder Nationalität des Spielers

name: Spieler oder Vereinsname

country: Land des Spielers oder des Vereins

type: Art des Akteurs (1=Spieler, 2=Verein)
	


	
NA: definiert fehlende Werte, bei der Datenerhebung das Feld einfach leer lassen, R rechnet NAs (missing values) automatisch raus..
	
