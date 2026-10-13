# YouTube-APK

Arquivo original: **YouTube.apk** (75 MB)

Como o APK já é um arquivo ZIP (comprimido), a compressão extra não reduz muito o tamanho. Por isso criei um **ZIP dividido em partes de ~24 MB** para facilitar download/upload.

## Download das partes (Google Drive)

1. **YouTube.zip** (parte principal - 10 MB):
   https://drive.google.com/file/d/1d0uXsZ5xC6yYryXAHEplqxZ3_6EEhbF4/view?usp=drivesdk

2. **YouTube.z01** (24 MB):
   https://drive.google.com/file/d/1fncsKlL1hwWdFtf7qWBbhHYn-mWRmBTO/view?usp=drivesdk

3. **YouTube.z02** (24 MB):
   https://drive.google.com/file/d/1fjmWMYIjq2E4-ycPM0PMLS2Cj-9BXX3z/view?usp=drivesdk

### Como juntar as partes
Baixe os 3 arquivos no **mesmo diretório** e execute:

```bash
zip -s 0 YouTube.zip --out YouTube-completo.zip
```

Ou no Windows use 7-Zip / WinRAR (eles juntam automaticamente partes .z01 .z02).

Depois é só renomear o resultado ou extrair o APK de dentro.

**APK original completo (75 MB):**
https://drive.google.com/file/d/116NcTXQex_Knw54UwgrWRbhD6cCAEFxY/view?usp=drivesdk
