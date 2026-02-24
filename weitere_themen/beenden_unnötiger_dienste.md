# Beenden unnötiger Dienste

Um dafür zu sorgen, dass unser System möglichst sicher ist, ist es wichtig, die Angriffsfläche so klein wie möglich zu halten. Durch das Abschalten von Diensten, die nicht benötigt werden, erreichen wir genau das. 

Unnötige Dienste in bestimmten Fällen sind z. B. Bluetooth, Avahi, Apache und CUPS.

Da diese Dienste in unserem Fall nicht notwendig sind, werden sie beendet. Dies machen wir mit dem Befehl:

1. systemctl stop \<Name des Dienstes>
2. systemctl disable \<Name des Dienstes>

Der Dienst muss auch deaktiviert werden, damit dieser nach dem Booten nicht mehr startet und nicht mehr mit ihm interagiert werden kann.

Grundsätzlich sollte man beachten, ob diese Dienste benötigt werden. Im Falle, dass man doch einen Dienst benötigt, welcher deaktiviert wurde, kann man ihn einfach wieder einschalten und im Zweifel den PC neu starten.  
