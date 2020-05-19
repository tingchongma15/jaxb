# JAXB

`JAXB` The Java™ Architecture for XML Binding (JAXB) provides an API and tools that automate the mapping between XML documents and Java objects.
[JAXB][].

[JAXB]: https://javaee.github.io/jaxb-v2/

## example
I downloaded and modified the [JAXB]: https://javaee.github.io/jaxb-v2/ example source codes.
jaxb-ri-2.3.1 has error with Java version: 1.8.0_251.
I downloaded [JAXB 2.2.11 jar files] from mvnrepository:  https://mvnrepository.com/artifact/com.sun.xml.bind/
JAXB 2.2.11 jar files worked with Java version: 1.8.0_251, Apache Ant version 1.10.1 (on Linux Mint 18.3 Cinnamon 64-bit).

### Eclipse

```

Run->External Tools->External Tools Configurations

External Tools configuration dialog, JRE tab, add VM arguments
-Djavax.xml.accessExternalSchema=all
```

