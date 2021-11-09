# Parser Chat Antlr
Projeto de parser de um chat utilizando Antlr

## Tasks do gradle

### Gerar o Parser ANTLR4
```
./gradlew generateGrammarSource
```
As sources geradas se encontram na pasta [main](./build/generated-src/antlr/main)

### Compilar o programa
```
./gradlew compileJava
```
As classes compiladas se encontram em [chatLanguage](./build/classes/java/main/lucas/chatLanguage)
