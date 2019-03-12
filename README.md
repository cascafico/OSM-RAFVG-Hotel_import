## source
https://www.dati.friuliveneziagiulia.it/Turismo/Strutture-Alberghiere-e-RTA/fiiw-i5su
##geocoding
Prior of running csvgeocode, reconcile with OSM authoritative highway names:
reconcile service: https://github.com/okfn/reconcile-csv
run service: java -Xmx2g -jar reconcile-csv-0.1.2.jar <file> <primary search column> <column with id's>
