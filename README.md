# networking-notes (german)
Notes for the networking module at HdM Stuttgart

# Experiment 1 - Troubleshooting TCP/IP

The goal of this experiment is to learn about essential tools to detect network related problems.

Häufige Probleme:
- Keine oder nur temporäre Verbindungen
- Zu geringer Datendurchsatz (dauerhaft oder temporär)
- Zu hohe Broadcast-Belastung des Netzes
- Start schwankende Laufzeiten
- Probleme in der Adress- und Namensauflösung
- Fehler im Routing bzw. der Netzwerkvermittlung

- PC-Adresse beginnt immer mit 141.62.66.x
	- Subnet innerhalb HdM-Netz
	- "ipconfig" kann die IP-Adresse feststellen (windows)
	- IP kann manuell geändert werden oder automatisch vom zentralen DHCP-Labor-Server bezogen werden.

- Die wichtigsten Tools des Betriebssystems, um tiefergehende Aussagen zur Verbindung zum Datenfluss zu erhalten, sind:
	- hostname: Zeigt den Namen des Computers an
 	- ipconfig: IP-Konfiguration
	- ping: Konnektivitätstest
	- pathping: Wie traceroute
	- arp: Überprüfung des ARP-Cache
	- tracert: Routeneermittlung
	- netstat: Anzeige der Netzstatistik
	- route: Anzeige der Routingtabelle
	- nslookup: DNS-Diagnose
