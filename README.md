# AACC Mockup — PMKT Du lịch (Design System & App Shell)

Bản mockup UI self-contained cho AIRDATA-ACCOUNTANT (kế toán du lịch).

- `index.html` — 1 file duy nhất, tự giải nén (base64+gzip) và render trên client. **Không cần build, không cần server.**
- Chỉ là static hosting: mọi CDN/static host đều chạy được, miễn cho JS chạy.

## Xem local

```bash
# mở trực tiếp
open index.html
# hoặc serve tĩnh (tránh vài giới hạn file://)
npx serve .
```
