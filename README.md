# Unser Schulprojekt über das Client Hardening 

Das Ziel des Projektes war es, einen Linux-Client so zu härten, dass es Angreifer möglichst schwer haben, diesen zu kompromittieren. In unserem Fall war das ein Laptop mit Ubuntu 24.04 LTS.

Wir hatten knapp eine Woche Zeit, dies umzusetzen und zu lernen, wie man damit umgeht.

Unsere Anpassungen waren unter anderem:
1. [Allgemeine Analysen](./weitere_themen/allg_analysen.md)
2. System up-to-date halten (durch regelmäßige Updates)
3. Konfiguration der Firewall ([UFW-Regeln](./weitere_themen/ufw_regeln.md))
4. [Beenden unnötiger Dienste](./weitere_themen/beenden_unnötiger_dienste.md) 
5. Änderung der Default-Ports
6. Nutzung von Programmen wie AppArmor --> aufgrund von Zeitmangel nicht umgesetzt.
7. [Monitoring](./weitere_themen/monitoring.md) (journalctl, systemctl)
8. Nicht als root angemeldet sein (minimale Privilegien haben - Least-Privilege-Prinzip)
9. Bildschirmsperre
10. [Festplatte verschlüsseln](./weitere_themen/festplatte_verschlüsseln.md)
11. [Secure Boot konfigurieren](./weitere_themen/secure_boot.md)
12. BIOS-Passwort
13. Getrennte Accounts (zweiter Nutzer ohne Root-Rechte)

