# MCBP Web / PWA

První webová verze MCBP určená pro iPhone/iPad a další moderní prohlížeče.

## Co je v první verzi
- Laboratoř
- databáze barev
- vyhledávání
- RGB ruční ovládání a slidery
- tolerance R/G/B a L
- zámek odstínu
- okolní odstíny
- Odstíny ±5 L podle stejné přechodové logiky
- historie měření
- podržení barvy a porovnání
- skupiny
- uložené barvy
- DEBUG simulace měření
- PWA manifest + service worker

## Spuštění
Projekt je statický. Pro PWA instalaci na iPhone musí být nasazen přes HTTPS.

Přímé BLE připojení k LS170 není v této první verzi zapojené; DEBUG režim simuluje měření. Android verze zůstává samostatná.
