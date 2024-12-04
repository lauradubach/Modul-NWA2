# Cisco Switches

1. Welches Spanning-Tree Protokoll ist aktiv?
 `show spanning-tree`
2. Wie viele VLANs gibt es im Netzwerk?
`show vlan brief`

![vlans](image-5.png)

## SWD-1
![SWD1](image.png)

## SWD-2
![SWD2](image-1.png)

## SWA-1
![SWA1](image-2.png)
![Root](image-4.png)

## SWA-2
![SWA2](image-3.png)

3. Passe die Spanning-Tree Version auf allen Geräten auf Rapid-PVST an.

Zuerst müssen wir den Modus wechseln:
`enable`

Dann in denn Konfigurierungs Modus:
`configure`

Nun die Version anpassen:
`spanning-tree mode rapid-pvst`

Danach aus dem Modus und speichern:
`exit`
`write`

Zum schluss testen:
`show spanning-tree summary`
