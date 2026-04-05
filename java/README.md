# Java Project

Java code van CP4 met jdtls support voor Neovim.

## Structuur

```
java/
├── .java-root          # jdtls project root marker
├── .classpath          # source: src/, output: out/
├── .project            # Eclipse project descriptor
├── .gitignore          # jdtls cache
├── out/                # compiled classes
└── src/
    ├── ch1/            # basic IO, strings
    ├── ch2/            # data structures
    ├── ch3/            # problem solving paradigms
    ├── ch4/            # graph algorithms
    ├── ch5/            # mathematics
    ├── ch6/            # string processing
    ├── ch7/            # computational geometry
    ├── ch8/            # advanced graph algorithms
    └── ch9/            # advanced topics
```

## Setup

Open een `.java` bestand in `java/src/` met nvim — jdtls detecteert `.java-root` automatisch.

## Run Code

```bash
cd java/src
java ch4/sssp/dijkstra.java
```

## Notes

- 99 Java bestanden, 22 test data `.txt` bestanden
- `IntegerPair.java` en `IntegerTriple.java` komen 1x voor in `ch4/` (duplicaten verwijderd)
- Originele `ch*/` folders in de root zijn ongewijzigd
- Geen packages — alles zit in de default package
