# How to run with Ant

## Before running
please install ant

### Linux or Windows WSL(WSL2)
```bash
sudo apt install ant
```

### MacOS
```bash
brew install ant
```

## How to use
At first, you should modify `build.xml`, especially "plhamj_version"
```bash
ant build
```
Then, you can get jar file in `dist` directory.
Using the jar, you can run your code:
```bash
java -jar ./dist/CI2002.jar src/CI2002/config.json
```

## Note
If you want to add your source code originally, please edit `build.xml`.
`build.xml` is only necessary for ant.
