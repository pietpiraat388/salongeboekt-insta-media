# QC TikTok-focus 17 nov 2026 (7 TikTok-video's, 1080x1920, 30 fps, 9,0 s)
Scripts: posts/2026-10-25_maandcontent/_werk/qa/safezone_check.py --margin 0.06 --step 0.04 en center_divider_check.py --src <video>/render.py --step 0.04
| Video | Soort | Safe zone 6% | Centrering/lijnen |
|---|---|---|---|
| 01-vergeten | recycle | 224 frames, 0 fout | 224 frames, 0 fout |
| 02-bon-overtypen | recycle | 224 frames, 0 fout | 224 frames, 0 fout |
| 03-wie-morgen | recycle | 224 frames, 0 fout | 224 frames, 0 fout |
| 04-negen-appjes | recycle (carrousel) | 224 frames, 0 fout | 224 frames, 0 fout |
| 05-cadeaubon | nieuw | 224 frames, 0 fout | 224 frames, 0 fout |
| 06-vaste-klant | nieuw | 224 frames, 0 fout | 224 frames, 0 fout |
| 07-week-verdiend | nieuw | 224 frames, 0 fout | 224 frames, 0 fout |
Logs en CSV's: _qc/. Per video contactsheet-qc.jpg (18 frames incl. overgangen). Set-contactsheet: contactsheet-tiktok-focus.png (zelf bekeken).
Bijgestuurd: eerste run gaf 4 + 1 + 13 fouten in 01/04/05: heldere fotoranden (stoelrand, dressoir, wandplank) werden als horizontale lijn gezien. Opgelost met zachte lokale demping van die fotostukjes (cfg 'soft'), daarna opnieuw gerenderd: 0 fouten.
Regels: haak + Ken Burns vanaf frame 1, vraag in beeld (haak), geen tekst of pill over de mockup (koppen y 330, toestel vanaf ~y 560), alle tekst op de inkt gecentreerd, geen dividers. Eindkaart: 30 dagen gratis proberen, geen creditcard nodig, salongeboekt.nl. Geen SALON50. Geen em-dashes.
Mensen: zelf gegenereerd (GenerateImage 17 nov), fotorealistisch, geen stock, geen echte personen. TikTok-label AI-gegenereerd aan.
Schermen: live salongeboekt.nl/app mobiel (demo Studio Linde) 17 nov; mail-herinnering en boekingspagina-datum van 29 okt (zelfde ontwerp). Alleen leesacties bij laden toegestaan, elke opslaan-actie geblokkeerd; niets in het account gewijzigd. Verborgen in beeld: proef-verlopen-melding, wachtlijst-toast, 'opslaan'-spinner, en bij sparen de regel 'staat uit'. Herinneringen en sparen staan in de demo uit; aan is alleen lokaal in beeld gezet.

## Varianten
| | Haak | Persoon/setting | Overgang | App-deel |
|---|---|---|---|---|
| 1 | kicker DINSDAG 11:00, pop | kapster bij lege stoel | crossfade | rise |
| 2 | regel voor regel | barbier-eigenaar schrijft bon, klant wacht | wipe | swap |
| 3 | kicker ZONDAG 22:10, pop | eigenaresse op de bank, telefoon | iris | rise |
| 4 | regel voor regel | nagelstyliste met telefoon, klant onder de lamp | crossfade | zoom |
| 5 | kicker CADEAUBON € 50, pop | klant 60+ geeft envelop, jonge kapper | wipe | swap |
| 6 | regel voor regel | vaste klant in spiegel met kapster | iris | zoom |
| 7 | kicker VRIJDAG 18:00, pop | barbier na sluiting telt bonnetjes | crossfade | rise |
