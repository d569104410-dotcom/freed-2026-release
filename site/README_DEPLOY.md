# Freed 2026 Navy Glass v1 — Pages Deploy (site/)

هذه الحزمة جاهزة للنشر مباشرة على **GitHub Pages** أو **Cloudflare Pages**.

## 1) GitHub Pages (Root = site)

1) ارفع المجلد `site/` داخل المستودع.
2) من: Settings → Pages
3) Source: Deploy from a branch
4) Branch: `main` (أو branch الحالي)  
5) Folder: **/site**
6) Save

بعدها اختبر الصفحات:

- `/index.html`
- `/preview.html`
- `/ui-kit.html`
- `/tabs-14-shell.html`
- `/selftest.html`

## 2) Cloudflare Pages (Output directory = site)

1) اربط المستودع في Cloudflare Pages.
2) Build command: **(فارغ)** أو `none`
3) Build output directory: **site**
4) Deploy

بعد النشر اختبر نفس الروابط أعلاه.

## صفحات الاختبار (Relative داخل site/)
- `index.html`
- `preview.html`
- `ui-kit.html`
- `tabs-14-shell.html`
- `selftest.html`

## CSS المعتمد
كل الصفحات تربط ملفًا واحدًا فقط:

`freed.identity.bundle.css`

> يوجد مسار تطوير اختياري داخل `site/identity/` (ملفات منفصلة).
