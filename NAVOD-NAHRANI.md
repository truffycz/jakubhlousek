# Jak dostat portfolio na GitHub (cca 10 minut)

## 1. Účet
Zaregistruj se na https://github.com. **Uživatelské jméno bude v adrese webu.**
Tahle složka počítá se jménem `jakubhlousek` → web bude na `https://jakubhlousek.github.io`.
Pokud bude jméno jiné, viz bod „Jiné uživatelské jméno“ dole.

## 2. Repozitář
1. Vpravo nahoře **+** → **New repository**.
2. Repository name: přesně `jakubhlousek.github.io` (stejně jako tvoje jméno + `.github.io`).
3. Nech **Public**, nic dalšího nezaškrtávej → **Create repository**.

## 3. Nahrání souborů
1. Na stránce nového repozitáře klikni na odkaz **uploading an existing file**.
2. Rozbal ZIP a **přetáhni do okna obsah složky** (ne složku samotnou):
   `index.html`, `jakub-hlousek-cv.pdf`, `README.md`, `.nojekyll` a složku `images`.
   - `.nojekyll` je skrytý soubor – na Macu ho zobrazíš ve Finderu zkratkou Cmd+Shift+. ; ve Windows Zobrazit → Skryté položky. Kdyby se nenahrál, nevadí, web funguje i bez něj.
3. Dole klikni **Commit changes**.

## 4. Zapnutí webu
1. V repozitáři **Settings** → v levém menu **Pages**.
2. Source: **Deploy from a branch**, Branch: **main**, složka **/ (root)** → **Save**.
3. Po 1–2 minutách je web na `https://jakubhlousek.github.io`. (Nahoře v Pages se objeví zelený odkaz „Your site is live“.)

## 5. Kontrola
- Otevři web na počítači i na mobilu.
- Klikni na „Stáhnout CV (PDF)“ a na všechna videa a články.

## Jiné uživatelské jméno
Když budeš mít jiné jméno (např. `kubahlousek`):
- repozitář pojmenuj `kubahlousek.github.io`,
- v `index.html` přepiš 2× `https://jakubhlousek.github.io/` (řádky s `og:image` a `og:url`),
- v CV je odkaz na `jakubhlousek.github.io` – napiš Claudovi nové jméno a vygeneruje nové PDF.

## Úpravy později
V repozitáři klikni na soubor → ikona tužky (Edit) → uprav → **Commit changes**.
Nový obrázek: **Add file → Upload files** do složky `images`.
