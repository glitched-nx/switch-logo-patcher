Hier ist die Übersetzung:

# Switch Logo Patcher

Erstellt die IPS-Patches, die benötigt werden, um das Switch-Logo beim Start zu ersetzen.

Das Logo, das du als Switch-Logo verwenden möchtest, muss die gleiche Größe wie das Originallogo haben, nämlich 308x350 Pixel. Andernfalls lässt dich das Programm nicht fortfahren.

Du musst das Originallogo nicht dumpen, um dies zu verwenden, aber wenn du das Originallogo nicht angibst, werden die Patches jeweils über 400 KiB groß.

### Verwendung

```
Verwendung: gen_patches.py [-h] [-o OLD_LOGO] patches_dir new_logo

Positionale Argumente:
  patches_dir           Das Verzeichnis, in dem die generierten Patches abgelegt werden
  new_logo              Das neue Logobild

Optionale Argumente:
  -h, --help            Zeige diese Hilfe-Meldung und beende das Programm
  -o OLD_LOGO, --old_logo OLD_LOGO
                        Das Originallogobild
```