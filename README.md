# PrimeFace Printer Style Issue

The 3 projects demonstrate how CSS Styles are no longer incorporated into the target of the Primefaces Printer Component in PF 11.

Each folder represents the same application but with different versions of PrimeFaces (PF6.2, PF10, and PF11) 

In 6.2 and 10 all CSS styles are applied to the target of the p:printer component.

## Run the project
Requires Java 11 and Maven

```cmd
$ mvn package payara-micro:start
```

The URL and port should be printed to the log

The urls with context root for the projects are:
* http://localhost:8080/pf-11-printer-demo-1.0-SNAPSHOT/index.xhtml
* http://localhost:8080/pf-10-printer-demo-1.0-SNAPSHOT/index.xhtml
* http://localhost:8080/pf-62-printer-demo-1.0-SNAPSHOT/index.xhtml
