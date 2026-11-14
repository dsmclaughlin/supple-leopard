# Becoming a Supple Leopard

A password-protected four-week mobility plan, served as a single static file via GitHub Pages.

`index.html` is self-contained: the page and its images are AES-256-GCM encrypted
inside it. The browser derives the key from a shared passphrase (PBKDF2-SHA256, 600k
iterations) and decrypts locally. No server, no accounts, nothing transmitted.

Source and build scripts live elsewhere. This repo holds only the built artefact.
