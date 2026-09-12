# Megamaxwin88 — GitHub Pages

Custom domain: **https://megamaxwin88.net/**

## Halaman

| Path | Isi |
|------|-----|
| `/` | AMP mobile v2 (default) |
| `/amp.html` | AMP v1 |
| `/amp-v2.html` | AMP v2 |
| `/amp-v3.html` | AMP v3 (felt/brass) |

## DNS (custom domain)

Di registrar / Cloudflare, arahkan domain ke GitHub Pages:

**Apex `megamaxwin88.net`**
- `A` → `185.199.108.153`
- `A` → `185.199.109.153`
- `A` → `185.199.110.153`
- `A` → `185.199.111.153`

**atau** `CNAME` `www` → `USERNAME.github.io` lalu redirect apex.

Lalu di repo: Settings → Pages → Custom domain → `megamaxwin88.net` → Enforce HTTPS.

> Catatan: domain ini sebelumnya mengarah ke platform live (Cloudflare/Next.js). Mengaktifkan GitHub Pages di apex akan mengganti hosting utama kecuali kamu pakai subdomain terpisah.
