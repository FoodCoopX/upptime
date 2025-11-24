# Upptime Workflow-Dateien

Dieses Verzeichnis enthält die korrekten und vollständigen Workflow-Dateien für eine funktionierende Upptime-Instanz. Diese Dateien beheben den Fehler "Unable to find workflow".

## 🔧 Verwendung

Falls in deinem Repository unter `.github/workflows/` Dateien fehlen oder die Workflows nicht korrekt unter "Actions" angezeigt werden, gehe wie folgt vor:

1. **Lösche** alle vorhandenen `.yml`-Dateien in deinem `.github/workflows/`-Verzeichnis auf GitHub.
2. **Lade alle `.yml`-Dateien** aus diesem Verzeichnis in dein `.github/workflows/`-Verzeichnis hoch.

Du kannst dies direkt über die GitHub-Weboberfläche tun:

- Navigiere zu `.github/workflows/` in deinem Repository.
- Klicke auf **"Add file"** → **"Upload files"**.
- Ziehe alle `.yml`-Dateien aus diesem Ordner in das Upload-Feld.
- Klicke auf **"Commit changes"**.

## ✅ Enthaltene Dateien

- `graphs.yml`
- `response-time.yml`
- `setup.yml`
- `site.yml`
- `summary.yml`
- `update-template.yml`
- `updates.yml`
- `uptime.yml`

Nachdem du diese Dateien hochgeladen hast, sollten alle Workflows korrekt im "Actions"-Tab deines Repositorys angezeigt werden. Führe anschließend den "Setup CI"-Workflow manuell aus, um die Einrichtung abzuschließen.
