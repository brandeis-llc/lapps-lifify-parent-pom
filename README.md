# lapps-lifify-parent-pom
A parent pom for Brandeis LAPPS Grid applications for LIF-ification. 
This parent pom is inheriting [`org.lappsgrid.maven:parent-pom`](https://github.com/lapps/org.lappsgrid.maven.parent-pom), then is setting Brandeis nexus as distribution repository. 

LIF-ification Java applications based on this pom can, in turn, be wrapped into a LAPPS web service, inheriting [`org.lappsgrid.maven:war-parent-pom`](~/Dropbox/Projects/lapps/lappsgrid/brandeis-lapps-lifify-parentpom).

