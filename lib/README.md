due to missing of the jta:jta:1.0.1 in the maven central and atlassian maven proxy, you need to install this jta jar manually to your local maven repository using this command:  

  mvn install:install-file -Dfile=./jta-1.0.1.jar -DgroupId=jta -DartifactId=jta -Dversion=1.0.1 -Dpackaging=jar
