Run with

``` sh
mvn -e compile exec:java -Dexec.classpathScope=compile -Dexec.mainClass="TopologyMain" -Dexec.args="src/main/resources/words.txt"
```