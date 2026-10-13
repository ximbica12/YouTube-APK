# YouTube-APK

Arquivo original: **YouTube.apk** (75 MB)

## Como colocar no Release (recomendado)

A integração atual do Grok **não tem ferramenta para criar Releases nem fazer upload de assets binários** no GitHub.

Faça você mesmo (leva 30 segundos):

1. Baixe os 3 arquivos do Google Drive (links abaixo)
2. Vá em: https://github.com/ximbica12/YouTube-APK/releases/new
3. Tag: `v1.0` (ou qualquer nome)
4. Title: `YouTube APK`
5. Arraste os 3 arquivos (`YouTube.zip`, `YouTube.z01`, `YouTube.z02`)
6. Clique em **Publish release**

Pronto. Os arquivos ficam no Release e qualquer um pode baixar.

---

## Arquivos prontos (Google Drive)

| Arquivo | Tamanho | Link |
|---------|---------|------|
| **YouTube.zip** | 10 MB | https://drive.google.com/file/d/1d0uXsZ5xC6yYryXAHEplqxZ3_6EEhbF4/view?usp=drivesdk |
| **YouTube.z01** | 24 MB | https://drive.google.com/file/d/1fncsKlL1hwWdFtf7qWBbhHYn-mWRmBTO/view?usp=drivesdk |
| **YouTube.z02** | 24 MB | https://drive.google.com/file/d/1fjmWMYIjq2E4-ycPM0PMLS2Cj-9BXX3z/view?usp=drivesdk |

### Como juntar as partes depois de baixar:

```bash
zip -s 0 YouTube.zip --out YouTube-completo.zip
```

(Windows: 7-Zip / WinRAR juntam automaticamente)
