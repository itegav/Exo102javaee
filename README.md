# Exercice 1/02

* unzip assets.zip dans ce répertoire
* copier ce répertoire dans le répertoire webapps de Tomcat
* compiler AuthServlet.java
* lancer Tomcat
* compléter AuthServlet, auth.jsp, welcome.jsp de façon à ce que
  * on ne puisse s'authentifier qu'avec admin@greta.fr/admin
  * un message d'erreur s'affiche si l'authentification échoue
  * on ne puisse pas accéder à welcome.jsp sans authentification
  * lorsque l'on se déconnecte avec le lien correspondant présent sur la page welcome.jsp, le formulaire d'authentification s'affiche de nouveau ainsi qu'un message confirmant la déconnexion
