# UDP-TCP-Chat-2025S

## Aufgabe 2: UDP
Nehmen sie nc_udp als Ausgangspunkt, und bauen Sie es zu einem Chatprogramm um. Jede Instanz des Programms
soll einen Namen haben und sich bei einer anderen Instanz registrieren können (also so etwas wie „Hallo, hier ist
Marvin, meine IP-Adresse ist die 192.168.0.42 und du kannst mich unter Port-Nummer 31337 erreichen.“).
Anschließend sollen die Instanzen, die sich kennen, über einen Befehl „send name message“ sich gegenseitig
Nachrichten senden können (name für den Ansprechpartner, message für die Nachricht).

## Aufgabe 3: TCP
Verändern Sie nc_tcp ebenfalls zu einem Chatprogramm. Allerdings soll die Registrierung der Instanzen hier über den
Server ablaufen. Nach der Registrierung soll es den Instanzen jedoch auch hier möglich sein, sich gegenseitig mit
„send name message“ Nachrichten zu senden. Beachten Sie hier, dass bei TCP über die gesamte Dauer des Sendens
und Empfangens eine Verbindung bestehen muss
