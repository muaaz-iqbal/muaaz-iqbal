# 📦 MIZANORAORG 3D Animated README — Kit

Ye folder **`muaaz-iqbal/MIZANORAORG`** repo ke naye animated README ka poora kit hai.
Is session ke sandbox token ko `MIZANORAORG` par push ki ijazat nahi thi (403), is liye
kit yahan session branch par mehfooz hai.

## Apply karne ka tareeqa (MIZANORAORG repo me)

1. **Arena me `MIZANORAORG` repo par naya coding session kholein** aur bole:
   “`muaaz-iqbal/muaaz-iqbal` repo ki branch `arena/2fd46761-muaaz-iqbal` se
   `mizanoraorg-readme/` folder ka README.md + assets/readme meri repo me apply karo.”
   (Wo session api.github.com se files utha sakta hai:
   `GET /repos/muaaz-iqbal/muaaz-iqbal/contents/mizanoraorg-readme?ref=arena/2fd46761-muaaz-iqbal`)
2. **Ya manually (GitHub web):**
   - `mizanoraorg-readme/README.md` ko MIZANORAORG ke root `README.md` par replace karein
   - `mizanoraorg-readme/assets/readme/` folder ko repo ke `assets/readme/` par upload karein
   - Commit → done. GitHub par sab animations live chalengi.

## Files
- `README.md` — naya 3D animated README (drop-in replacement)
- `assets/readme/hero3d.svg` — 3D isometric hero (extruded gold title, fly-through floor, floating cubes + orbit)
- `assets/readme/eco3d.svg` — 3D ecosystem floor (floating project tiles)
- `assets/readme/ticker.svg`, `wave.svg`, `bars.svg` — live animations
- `assets/readme/photos/` — founder photos
- `preview.html` — local live preview (gitignored)

Site ke existing assets (`assets/hero.svg` waghera) bilkul untouched hain — naye files sirf `assets/readme/` me jaate hain.
