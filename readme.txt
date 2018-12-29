1.	Exceute:
    mvn archetype:generate -DgroupId=com.loki.manymodule -DartifactId=parent-project
2.	This will create a complete structure for you.
3.	Inside the pom change the packaging to pom
4.	Now go inside the project directory and execute the following commands:
    mvn archetype:generate -DgroupId=com.loki.manymodule  -DartifactId=loki-model
    mvn archetype:generate -DgroupId=com.loki.manymodule  -DartifactId=loki-web
5.	Inside the folder, 2 new folders will get created with parent property set.
6.	At last you can run:
    mvn package
