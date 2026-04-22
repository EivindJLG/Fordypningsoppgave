# Fordypningsoppgave
IT-Drift fordypning subnetting og containers

07.04.2026 - 10.04.2026 - Start av fordypningsoppgave
Jeg bestemte meg til å lære om containers og subnetting.


Jeg lærte mest praktisk om containers, men litt teoretisk om subnetting også.
Installerte Docker Desktop der jeg kan lage containers som kjører applikasjoner i isolerte miljøer. Jeg installerte også Linux på windows med WSL (Windows Subsystem for Linux) --install. Lagde min første container med kommandoen: docker run hello-world. Siste container lagde jeg en nginx http server med kommandoen: docker run -d -p 8080:80 nginx. Når det kommer til subnetting så lærte jeg at det er en prossess der man deler opp en stor IP nettverk til mindre, men håndterbar subnets. Det som er bra med subnetting er at nettverket, sikkerheten, og IP-adressene blir mer effektive. For eksempel subnetting er bra for bedrifter fordi at det er bedre bruker/systemadministrasjon.

Subnetting = Nettverkssegmentering/Undernetting

# Fordypningsoppgave – IT-Drift TLDR
## Subnetting og Containere

 **Startdato:** 07.04.2026  

---

I denne fordypningsoppgaven har jeg valgt å jobbe med temaene:
- Subnetting  
- Containere  

Målet er å lære både **praktisk og teoretisk** hvordan disse brukes i IT-drift, og hvordan de kan kombineres i virkelige systemer.

---

##  Start av prosjekt
Jeg bestemte meg for å fokusere på subnetting og containere fordi:
- Det er relevant i moderne IT-drift  
- Det kombinerer nettverk og systemer  
- Det gir mulighet for både teori og praksis  

---

## Praktisk arbeid – Containere

### Installasjon
For å jobbe med containere installerte jeg:
- Docker Desktop  
- Linux på Windows ved hjelp av WSL (Windows Subsystem for Linux)  

Kommando brukt:
```bash
wsl --install
docker run -d -p 8080:80 nginx
docker run hello-world
