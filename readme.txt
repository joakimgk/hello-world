git
	versjonskontrollsystem 
	i utg.punktet veldig velegnet for ren tekst (men kan hive inn andre ting, bin�re bildefiler etc)
	(asyklisk) grafstruktur (DAG)
	
	commit er samme som i SVN (men den er alts� OFFLINE!)
	
git vs SVN
	git er desentralisert, mens SVN har tankegang om at gjeldende versjon til enhver tid ligger p� en SERVER et sted
	(selv om man kan ha SVN installert lokalt, p� samme PC, s� er det jo fremdeles kun tilgjengelig p� EN maskin)
	git laster til enhver tid ned HELE versjonssystemet (hele grafen, alle brancher) f�r man begynner � jobbe (lokalt)  <-- CLONE
	kan ogs� laste ned (sjekke ut) �n spesifikk node p� en parallell branch -- feks en kritisk bug fix -- til min branch
	
	MYE bedre p� branching (og gj�r det sjeldnere at man trenger � merge) <-- ikke BEDRE p� merge, s�nn sett
	
	man committer ikke uferdig arbeid; kun �n ting om gangen (sm� commits), og denne skal v�re FERDIG  <-- best practice
	
	git har alts� lokal commit, men resulterer i en PUSH
	
N�r man gj�r git CLONE, s� legges det inn en link til location
s� gj�r man gir PULL
PULL ofte, sm� COMMITs