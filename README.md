# Automatisk-Backup-Python-skript
Dette prosjektet er et enkelt Python-verktøy designet for å ta automatisk sikkerhetskopi av valgte mapper på en lokal server.

### Funksjoner og Krav
Følgende funksjoner er inkludert i nåværende versjon:
  * Automatisk komprimering ia python zipfile-biblioteket
  * Loggføring av alle handlinger til en tekstfil
  * Varsling på e-post dersom en feil oppstår

###  Installasjon og oppstart
følg disse trinnene for å sette opp prosjektet
  1. Klon kildekoden fra GitHub.
  2. installer nødvendige avhengigheter.
  3. kjør skriptet fra terminalen
### Eksempel på kjøring
Bruk følgende kommando i terminalen for å starte backupen manuelt:
  >python backup.py --source /data --target /backup
