# Dokmentation
Unser Programm nutzt eine Forever-Schleife, um das Programm auszuführen.
Wir verwenden den vorderen Distanzsensor, um auf die Nähe der Wand, auf welche der Roboter zufährt, rechtzeizig reagieren zu können.
Der Roboter misst also ständig die Entfernung zur Wand und reagiert bei einem Abstand von 50cm.
Damit der Roboter nun nicht gegen die Wand fährt,soll er sich anhand einer Entscheidungsschleife, entscheiden, ob er abbiegen muss oder weiterhin gerade aus fahren kann.
Diese Entscheidungsschleife besagt, dass, wenn der rechte Distanzsensor mehr als einen bestimmten Wert anzeigt, das Roboterauto nach rechts abbiegen soll.
Wenn es links aber keine Hindernisse gibt, soll er nach links abbiegen.
(Ansonsten fährt er weiterhin geradeaus)
Die Lenkung wird über die brickinternen Gyrosensoren gesteuert
