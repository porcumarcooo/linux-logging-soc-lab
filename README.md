# Linux Logging for SOC - Lab & Notes

Repository contenente appunti tecnici, scenari pratici e analisi dei log focalizzati sui sistemi Linux in ottica SOC (TryHackMe).

**Concetti Chiave Appresi:**
* **Struttura dei Log Linux:** Analisi dei principali file di log in `/var/log` (`auth.log`/`secure`, `syslog`, `kern.log`).
* **Tracciamento Accessi e Privilegi:** Identificazione di tentativi di connessione SSH anomali, attacchi brute-force ed escalation dei privilegi (abuso di `sudo` o `su`).
* **Gestione Log con Systemd & Auditd:** Utilizzo avanzato di `journalctl` e configurazione delle regole di monitoraggio con `auditd`.

**Strumenti Utilizzati:**
* Linux CLI (`grep`, `awk`, `cut`, `journalctl`)
* Auditd / Systemd
* TryHackMe Virtual Labs
