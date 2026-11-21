# Kolumbia 2026 - správa zo zahraničnej pracovnej cesty

Webová stránka k ZPC Ing. Antona Marciho, PhD. (KÚA FHI EU v Bratislave) do Kolumbie, 30. 10. - 18. 11. 2026:
hosťovské prednášky na Universidad Externado de Colombia, Universidad del Valle a Pontificia Universidad Javeriana Cali
a príspevok na kongrese REDICEAC 2026 (UNIMINUTO Ibagué).

Statická stránka bez build kroku: `index.html`, fotky v `img/` (náhľady v `img/t/`), videá v `video/`.
Jazyky SK / ES / EN (prepínač v hlavičke; španielsky prehliadač dostane ES automaticky).

## Nasadenie (GitHub + Vercel)
1. Nový repozitár, napr. `kolumbia-2026-marci`, a push obsahu tohto priečinka do koreňa repozitára.
2. Vercel: Add New Project, import repozitára, Framework Preset `Other`, bez build príkazu, Output Directory `.`.
3. Adresa projektu musí sedieť s odkazom a QR kódom v správe: `https://kolumbia-2026-marci.vercel.app`.
   Ak Vercel pridelí inú adresu, treba upraviť správu (odkaz aj QR).

## Úpravy
- Odkazy (aplikácie, YouTube, Facebook, Zenodo) sú v objekte `LINKS` na začiatku skriptu v `index.html`.
  `javerianaApp` je prázdne - po doplnení adresy sa odkaz zobrazí automaticky.
- Program dní je v poli `DAYS`, popisy fotiek v `PH` a `VID`, štatistiky Slido v `RATINGS`, `SHIFT`, `QUIZ`, citáty v `QUOTES`.

Mapa: Leaflet + dlaždice OpenStreetMap. Fotografie a videá: autor a hostiteľské inštitúcie.
