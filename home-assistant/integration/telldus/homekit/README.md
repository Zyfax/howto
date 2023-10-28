# Telldus Znet lite V2

1. Finn IPen til Telldus fra routeren eller App fra telefonen, for eks Fing. (Eksemplet er fra Unifi).

   ![Unifi](img/Pasted%20image%2020231028222531.png?raw=true)

2. Åpne nettleser http://(Telldus IP).
   Hvis du får feilmeldingen 404 som er nevnt nederst, prøv en annen nettleser. Firefox, eventuelt Vivaldi som ble brukt her.
3. Logg inn med Telldus konto.

   ![Telldus](img/Pasted%20image%2020231028222612.png)

5. Velg Plugins (beta) på venstre side-meny.
6. Velg HomeKit (More Info) og Install.
7. Når tillegget er installert, Oppdater nettsiden (F5) og vel tannhjulet på HomeKit.

   ![HomeKit](img/Pasted%20image%2020231028223102.png)

8. Kopier HomeKit koden XXX-XX-XXX.
9. Gå inn i Home Assistant under Settings => Integrations og legg til HomeKit Device.

   ![img](img/Pasted%20image%2020231028224205.png)

10. Velg TellStick (Bridge) og Submit.

    ![img](img/Pasted%20image%2020231028224216.png)

11. Legg til HomeKit koden kopiert fra Telldus og Submit.

    ![img](img/Pasted%20image%2020231028224250.png)

12. Velg rom på enhetene og/eller trykk Finish.

    ![img](img/Pasted%20image%2020231028225506.png)


#### 404 Feilmelding ved Telldus pålogging
   ![img](img/Pasted%20image%2020231028224629.png)
