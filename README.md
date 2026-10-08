# danenco-hartslag

Kleine geplande aanroepen die niet van één computer mogen afhangen. Openbare repo met opzet: GitHub Actions
heeft daar onbeperkt minuten, en er staat niets geheims in (de adressen met sleutel zitten in GitHub-secrets).

| Workflow | Wat | Hoe vaak |
| --- | --- | --- |
| `helpdesk-mail` | haalt nieuwe mail van de Sticker-helpdesk op (`HELPDESK_IMAP_URL`) | elke 5 minuten |
| `keepalive` | zet de geplande workflows wekelijks opnieuw aan (GitHub zet ze anders na 60 dagen stil) | wekelijks |

Eerder draaide dit als crontab op een Mac, elke minuut (8-10-2026 verhuisd).
