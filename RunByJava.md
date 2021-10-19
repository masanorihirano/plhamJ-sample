# How to run by java (CUI)

## Before running
Please use java environment.

#### Linux or Windows WSL(WSL2)
```bash
$ sudo apt install default-jdk
```

#### MacOS
```bash
$ brew install java
```
Then, set up environment path according to the output from the command above.

#### Windows
TBD

## Run Program
```bash
(plhamJ-sample) $ javac -cp lib/plhamj-v1.0.0-jar-with-dependencies.jar:src src/CI2002/CI2002Main.java
(plhamJ-sample) $ java -cp lib/plhamj-v1.0.0-jar-with-dependencies.jar:src CI2002.CI2002Main src/CI2002/config.json
```

## Run and Analyze
```bash
(plhamJ-sample) $ javac -cp lib/plhamj-v1.0.0-jar-with-dependencies.jar:src src/CI2002/CI2002Main.java
(plhamJ-sample) $ java -cp lib/plhamj-v1.0.0-jar-with-dependencies.jar:src CI2002.CI2002Main src/CI2002/config.json > data_CI2002.dat
(plhamJ-sample) $ Rscript src/CI2002/plot.R data_CI2002.dat CI2002.png
```
