=====
Archetipo Template
=====

Requisisti
============

* IDE Java
* Jdk 1.8+

Utilizo
=======
	Per il momento il progetto è in fase di Sviluppo. 
	
Compilazione
==============
	mvn install
	
Utilizzo
==============
1) Dopo che se ha creato il archetipo con mvn install, lanciare il comando -Dmaven.offline.true (Per cercare sul repository locale .mvn, se hai un server nexus o altro, levare questo parametro) 	


comando : 
-------- 

**mvn** -Dmaven.offline.true archetype:generate -DarchetypeGroupId=it.peruvianit -DarchetypeArtifactId=archetipo-archetype -DarchetypeVersion=1.0-SNAPSHOT -DgroupId=it.<TUO GROUP-ID> -DartifactId=<TUO ARTIFACT-ID> -DVersion=<TUA VERSIONE> -Dpackage=<TUO PACKAGE> -Dproject-name=<NOME PROGETTO> -Dmensaje="<PARAMETRO PER LA CLASSE Hello.java>"
