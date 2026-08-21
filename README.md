# a433-microservices

Repository ini digunakan untuk kebutuhan kelas Belajar Membangun Arsitektur Microservices

Silakan clone dengan perintah berikut.<br>
`git clone -b proyek-pertama https://github.com/dicodingacademy/a433-microservices.git`

---

## Submission Proyek Pertama — Proyek Deploy Aplikasi Item App dengan Docker Compose

- **Repository (fork):** https://github.com/arighmt67-bit/a433-microservices
- **Branch:** `proyek-pertama`
- **Image container (GitHub Packages/GHCR):** https://github.com/arighmt67-bit/pkgs/container/item-app

### Berkas Submission
- `Dockerfile` — membangun image `item-app` (Node.js 14, production mode, DB host `item-db`, port 8080)
- `build_push_image.sh` — script build & push image ke GitHub Packages
- `docker-compose.yml` — menjalankan `item-app` (port 80) + `item-db` (MongoDB 3, volume `app-db`)
- `log.txt` — logs saat `docker compose` berjalan
- `link.txt` — tautan image container di GitHub Packages

Dibuat oleh: **Ari Rahmat Romadhon**
