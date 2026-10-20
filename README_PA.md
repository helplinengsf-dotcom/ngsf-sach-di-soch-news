# NGSF Sach Di Soch News — ਪਹਿਲਾ Website Frontend

ਇਹ GitHub Pages ਲਈ responsive Punjabi frontend ਹੈ। ਇਸ ਵਿੱਚ ਮੁੱਖ ਪੰਨਾ, category filters, sample news cards, About ਅਤੇ Contact pages ਹਨ।

## GitHub 'ਤੇ ਲਗਾਉਣ ਲਈ
1. ਆਪਣੀ NGSF Sach Di Soch News repository ਖੋਲ੍ਹੋ।
2. `Add file` → `Upload files` ਚੁਣੋ।
3. ZIP extract ਕਰਕੇ `index.html`, `style.css`, `app.js`, `about.html`, `contact.html` ਅਤੇ `README_PA.md` ਨੂੰ repository ਦੇ root ਵਿੱਚ upload ਕਰੋ।
4. `Commit changes` ਕਰੋ।
5. `Settings` → `Pages` → `Deploy from a branch` → branch `main` → folder `/(root)` ਚੁਣੋ।
6. GitHub Pages ਵੱਲੋਂ ਦਿੱਤੇ URL 'ਤੇ ਜਾਂਚ ਕਰੋ।

## ਅਗਲਾ ਪੜਾਅ
- ਇਹ ਸਿਰਫ਼ frontend ਹੈ; backend/database ਹਾਲੇ ਨਹੀਂ ਜੁੜੇ।
- ਖ਼ਬਰਾਂ demo/sample ਹਨ, ਅਸਲ published news ਨਹੀਂ।
- Contact form ਹੁਣੇ ਡਾਟਾ ਨਹੀਂ ਭੇਜਦਾ।
- ਅਗਲੇ ਪੜਾਅ ਵਿੱਚ Cloudflare Worker + D1 ਨਾਲ live news, secure admin authentication ਅਤੇ publishing ਜੋੜਾਂਗੇ।
- Admin token ਜਾਂ secret ਨੂੰ HTML/JavaScript ਵਿੱਚ ਨਾ ਰੱਖੋ।
