# Arquivos pom.xml e persistence.xml

Após aprender um pouco sobre a diferença entre a #JDBC e a #JPA, chegou a hora de aprender a colocar a mão na massa e a como finalmente persistir um objeto #Java. Para isso, vi que são necessários dois arquivos cruciais, o pom.xml e o persistence.xml.

📌 pom.xml: arquivo no qual realizamos a configuração das dependências dos drivers tanto do Hibernate quanto do banco de dados que será utilizado, além também de configurar a versão do Java que será utilizada no projeto.

📌 persistence.xml: nele, adicionamos as propriedades de configuração do JPA para que ele consiga se conectar e conversar com o banco de dados através do Hibernate. Vi que esse arquivo precisa obrigatoriamente estar localizado em uma pasta nomeada como “META-INF.

Bom, visto isso, e após ter aprendido a realizar essas primeiras configurações, também aprendi a criar uma entidade, classe a qual a JPA, através do Hibernate, mapeia para o nosso banco de dados. No próximo post falarei um pouco sobre o que aprendi sobre esse processo. 
