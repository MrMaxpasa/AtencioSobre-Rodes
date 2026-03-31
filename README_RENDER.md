# 🚀 Com publicar a Render

## Pas 1 – Puja el codi a GitHub

1. Crea un repositori nou a [github.com](https://github.com) (pot ser privat o públic).
2. Puja els fitxers d'aquesta carpeta:
   - `index.html`
   - `logo.svg`
   - `render.yaml`

```bash
git init
git add .
git commit -m "Primera versió web Atenció Sobre Rodes"
git branch -M main
git remote add origin https://github.com/EL-TEU-USUARI/atencio-sobre-rodes.git
git push -u origin main
```

## Pas 2 – Crea el servei a Render

1. Accedeix a [render.com](https://render.com) i inicia sessió.
2. Fes clic a **New → Static Site**.
3. Connecta el repositori de GitHub que acabes de crear.
4. Configura:
   - **Name:** `atencio-sobre-rodes`
   - **Branch:** `main`
   - **Publish directory:** `.` (punt)
5. Fes clic a **Create Static Site**.

✅ En pocs minuts tindràs la web publicada a una URL del tipus:
`https://atencio-sobre-rodes.onrender.com`

## Pas 3 – Domini personalitzat (opcional)

A Render, ves a **Settings → Custom Domains** i afegeix el teu domini propi (per exemple `www.atenciosobrerades.cat`).

---

📩 Per a qualsevol dubte: `info@atenciosobrerades.cat`
