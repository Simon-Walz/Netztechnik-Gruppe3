# Netztechnik-Gruppe3
In Abgabe.7z befindet sich das gns3-Projekt sowohl als exportiertes portable, daneben befindet sich auch der Projektordner.
Hinsichtlich der Firewalleinstellungen hat sich während der Implementierung (im Vergleich zum Entwurf) noch folgendes geändert:

-es wird nun doch auch Port 80 (http) erlaubt, da überraschend viele Webseiten noch nicht auf https umgestellt sind

-auch DNS auf Port 53 wird erlaubt, um Surfen zu ermöglichen

-auf eine Blacklist von Webinhalten wurde verzichtet, da 'Surfen' in den Anforderungen nicht näher eingegrenzt wurde

-es gibt nur eine Verbindung zur Firewall, da keine Redundanz für die Internetanbindung gefordert war
