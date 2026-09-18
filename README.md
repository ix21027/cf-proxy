# Cloudflare Tunnel Reverse Proxy

Цей репозиторій створено для обходу блокування IP-адрес Cloudflare провайдерами через Vercel або Netlify.

### Цільова адреса:
`https://atom-continued-retail-frequency.trycloudflare.com/`

---

## 🚀 Як запустити через Vercel (1 хвилина):

1. Відкрийте [vercel.com/new](https://vercel.com/new).
2. Виберіть цей репозиторій (`ix21027/cf-proxy`).
3. Натисніть **Deploy** (ніяких додаткових налаштувань змінювати не потрібно).
4. Отримайте посилання виду `https://cf-proxy-xxx.vercel.app`, яке відкривається **без VPN**.

---

## ⚠️ Важлива примітка:
Адреса `atom-continued-retail-frequency.trycloudflare.com` є тимчасовим Quick Tunnel (`cloudflared tunnel --url ...`). 
Якщо тунель перезапуститься і згенерується нове посилання, просто оновіть URL у файлах `vercel.json` та `netlify.toml` і зробіть `git push`.
