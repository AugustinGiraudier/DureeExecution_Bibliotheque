# DureeExecution_Bibliotheque
Augustin GIRAUDIER

* Bibliothèque C++ permettant de récupérer facilement la durée d'un processus
	
	- créez un objet de type ExecutionTime
	- lancez votre processus
	- appelez sa méthode End() qui vous renverra le temps écoulé
	- vous pouvez appeler sa méthode Start() afin de relancer le timer
	- vous pouvez passer en parmetre de la méthode End() l'unite de temps à utiliser (enum TimeUnit)