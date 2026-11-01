# BisaBikinWeb — App Portal

Repository khusus deployment GitHub Pages untuk `app.bisabikinweb.site`.

Source utama: [mejaviskinc/bisabikinweb](https://github.com/mejaviskinc/bisabikinweb). Workflow `.github/workflows/deploy-pages.yml` membangun `app-dist` dari source utama lalu menerbitkan `pages-app`.

Pengaturan wajib setelah workflow pertama: Repository Settings → Pages → Source: **GitHub Actions**, Custom domain: `app.bisabikinweb.site`.

DNS domain: `CNAME app → mejaviskinc.github.io`. Jangan ubah DNS `@`, `www`, MX atau TXT.

Area admin/seller memakai Supabase dan tetap perlu otorisasi. Halaman area internal diatur noindex.
