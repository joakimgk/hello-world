git
	versjonskontrollsystem 
	i utg.punktet veldig velegnet for ren tekst (men kan hive inn andre ting, binære bildefiler etc)
	(asyklisk) grafstruktur (DAG)
	
	commit er samme som i SVN (men den er altså OFFLINE!)
	
git vs SVN
	git er desentralisert, mens SVN har tankegang om at gjeldende versjon til enhver tid ligger på en SERVER et sted
	(selv om man kan ha SVN installert lokalt, på samme PC, så er det jo fremdeles kun tilgjengelig på EN maskin)
	git laster til enhver tid ned HELE versjonssystemet (hele grafen, alle brancher) før man begynner å jobbe (lokalt)  <-- CLONE
	kan også laste ned (sjekke ut) én spesifikk node på en parallell branch -- feks en kritisk bug fix -- til min branch
	
	MYE bedre på branching (og gjør det sjeldnere at man trenger å merge) <-- ikke BEDRE på merge, sånn sett
	
	man committer ikke uferdig arbeid; kun én ting om gangen (små commits), og denne skal være FERDIG  <-- best practice
	
	git har altså lokal commit, men resulterer i en PUSH
	
Når man gjør git CLONE, så legges det inn en link til location
så gjør man gir PULL
PULL ofte, små COMMITs