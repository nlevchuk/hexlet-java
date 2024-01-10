## My first project on Hexlet

### Run

* From the main directory

```
java -classpath ./ io.hexlet.One
```

* From the package directory

```
java -classpath ../.. io.hexlet.One
```

* JAR file

```
java -jar build.jar
```

### Compile

* To a directory

```
javac One.java Two.java -d build
```

### Packaging

```
jar -cvfm build.jar manifest.MF .
```
