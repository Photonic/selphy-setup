# Canon SELPHY Setup

Dit project bevat een complete setup-pagina voor iOS-gebruikers die verbinding willen maken met een Canon SELPHY-printer (CP1500, CP1200, CP910).

## Bestanden

### `index.html`
Een interactieve webpagina die:
- Het lokale IP-adres probeert te detecteren
- De internetverbinding controleert
- Een handmatige link toont naar de printerinterface (`http://192.168.0.1`)
- Toegang geeft tot het `.mobileconfig` profiel
- Duidelijke instructies toont voor installatie via iOS Instellingen
- Een waarschuwing geeft als de gebruiker niet Safari gebruikt (Safari is vereist voor profielinstallatie op iOS)

Deze pagina is geoptimaliseerd voor gebruik met QR-codes en iPhones.

### `SELPHY_CP1500_WiFi_Profile_with_Password.mobileconfig`
Een configuratieprofiel voor iOS dat:
- De netwerken herkent van Canon SELPHY printers (CP1500-, CP1200-, CP910-)
- Het standaard wifi-wachtwoord instelt (`22223333`)
- Een statisch IP-adres instelt (192.168.0.101)
- Autojoin uitschakelt (gebruiker moet bewust verbinden)
- Captive portal detectie uitschakelt (voor snellere verbinding)

## Gebruik

1. Scan de QR-code die naar deze GitHub Pages site verwijst
2. Controleer je netwerk en klik op de profiel-download
3. Open Instellingen > Algemeen > VPN en apparaatbeheer > Profiel gedownload
4. Installeer het profiel

> 📱 Zorg dat je mobiele data beschikbaar blijft tijdens printer-wifi (Instellingen > Mobiel netwerk > Schakel over op mobiele data > Automatisch)

## Opmerking
Dit systeem is ontworpen voor educatief en tijdelijk gebruik door studenten. Geen technische voorkennis vereist.

---

Voor vragen of verbeteringen: [photonic.github.io/selphy-setup](https://photonic.github.io/selphy-setup)
