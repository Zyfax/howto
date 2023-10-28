# Telldus Znet lite V2

1. Finn IPen til Telldus fra routeren eller App fra telefonen, for eks Fing. (Eksemplet er fra Unifi).
   ![[Pasted image 20231028222531.png]]
2. Åpne nettleser http://(Telldus IP).
   Hvis du får feilmeldingen 404 som er nevnt nederst, prøv en annen nettleser. Firefox, eventuelt Vivaldi som ble brukt her.
3. Logg inn med Telldus konto.
   ![[Pasted image 20231028222612.png]]
5. Velg Plugins (beta) på venstre side-meny.
6. Velg HomeKit (More Info) og Install.
7. Når tillegget er installert, Oppdater nettsiden (F5) og vel tannhjulet på HomeKit.
   ![[Pasted image 20231028223102.png]]
8. Kopier HomeKit koden XXX-XX-XXX.
9. Gå inn i Home Assistant under Settings => Integrations og legg til HomeKit Device.
   ![[Pasted image 20231028224205.png]]
10. Velg TellStick (Bridge) og Submit.
    ![[Pasted image 20231028224216.png]]
11. Legg til HomeKit koden kopiert fra Telldus og Submit.
    ![[Pasted image 20231028224250.png]]
12. Velg rom på enhetene og/eller trykk Finish.
    ![[Pasted image 20231028225506.png]]


#### 404 Feilmelding ved Telldus pålogging
![[Pasted image 20231028224629.png]]