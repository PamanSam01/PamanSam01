# Setup profil GitHub PamanSam01 — 5 menit

File `README.md` di zip ini = tampilan profil lo nanti (langsung ke-render di
github.com/PamanSam01 begitu repo `PamanSam01/PamanSam01` ada).

## 1. Push README (repo profile WAJIB nama persis username)

```bash
cd PamanSam01-profile
git remote add origin https://github.com/PamanSam01/PamanSam01.git
git push -u origin main
```

Kalo repo belum dibuat: bikin dulu di https://github.com/new
— **name: `PamanSam01`** (sama persis sama username, Public), centang
"Add a README file", terus `git pull --rebase` sebelum push (atau kosongin
README via web, push ini aja).

## 2. Update bio (keliatan di kepala profil)

https://github.com/settings/profile → **Bio** (max 160 char), pakai:

```
Web3 builder 🛠️ Aptos · Sui · Arweave · TS — shipping dApps & hackathon projects from Bandung 🇮🇩
```

Hapus / ganti `Gaming enthuasiast 🎮` (ada typo juga itu). Ini penting karena
bio keliatan sebelum orang buka repo.

## 3. Pinned repos (6 slot, di halaman profil → "Customize your pins")

https://github.com/PamanSam01?tab=repositories → tombol **"Customize your pins"**,
pilih urut ini (paling kuat dulu):

1. `Drift` — hackathon entry, paling fresh
2. `shelbyos-webapp` — punya deskripsi paling lengkap
3. `Chogram` — unik (NFT broadcast studio)
4. `coral-ai-investigator` — AI/SRE, nunjukin range
5. `prooffolio` — Sui, identity
6. `tamasave` — DeFi gamified

## 4. Kasih deskripsi + topics ke repo kosong (biar gak keliatan acak)

Repo **tanpa** deskripsi sekarang: `Chogram`, `prooffolio`, `tamasave`,
`coral-ai-investigator`, `umkm-assistant`, `ArcPass`, `ShelbyOS`, `Guides`.
Copy dari README masing-masing, contoh:

- `Chogram` → `Broadcast studio for your Chog Genesis NFT — summon films, live $CHOG alerts, monthly wraps`
- `prooffolio` → `On-chain professional identity & reputation network built on Sui`
- `tamasave` → `Gamified crypto savings — every DCA goal becomes a Tamagotchi-style pet`
- `coral-ai-investigator` → `AI incident investigator — anomaly correlation & real-time root-cause analysis`
- `ArcPass` → `The human layer of Web3 finance (Arc Testnet)`
- `umkm-assistant` → `AI assistant for Indonesian UMKMs (MSMEs)`

Di Settings repo masing-masing isi **Description** + **Topics** (misal
`chogram`: nft, web3, video, aptos? — sesuai chain aslinya). Topics bantu
discoverability.

Boleh sekalian: `ShelbyOS` & `Guides` yang kosong banget (README 404) — isi
sekecil apa pun atau archive/delete `Guides` (dari 2024, keliatan abandoned).

## 5. Link sosial

Profil Settings → **Website** isi `https://x.com/MrSamweb3` (biar ada outbound
link selain Twitter field).

## 6. GitHub Achievements

Untuk melengkapi lencana profil, merge pull request dan kolaborasi commit aktifkan badge seperti Pull Shark, YOLO, dan Pair Extraordinaire.
