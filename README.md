# java-for-web-cap4-cad-usuarios

01-1-20 

Arquivo pom.xml erros :
1 - JAX-RS (REST Web Services) 2.0 can not be installed : One or more constraints have not been satisfied.

2 - JAX-RS (REST Web Services) 2.0 requires Java 1.6 or newer.

Solu��o 
Right click on the project -> properties -> Java Compiler -> Look at compliance level

01-17-20
Erro :
Java compiler level does not match the version of the installed Java project facet.
01-18-20
Erro :
java.lang.ClassNotFoundException: javax.faces.webapp.FacesServlet
Solu��o :
Verifique se os jars do que est�o no seu pom tamb�m se encontram na pasta lib do projeto. Sen�o estiverem fa�a o seguinte: Properties" --> "Deployment Assembly", adicione "Java Build Path Entries -> Maven Dependencies"
=======
Java compiler level does not match the version of the installed Java project facet.

