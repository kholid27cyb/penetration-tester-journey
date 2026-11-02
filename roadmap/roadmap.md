# Roadmap 18 Bulan

Setiap bulan = 3 minggu materi + 1 minggu konsolidasi (mini project dan review).
Nama room, lab, dan alat bisa berubah, jadi cek materi terbaru di platformnya.
Centang `[ ]` saat target bulan itu selesai.

---
## Fase 1 — Fondasi (Bulan 1–3)
**Target:** bisa menjelaskan apa yang terjadi saat membuka website, menulis skrip Python kecil, dan menangkap request dengan Burp.

- [ ] **Bulan 1 — Setup dan Linux** ([detail harian](bulan-01.md))
  - Minggu 1: akun TryHackMe, GitHub, Notion; dasar Linux; OverTheWire Bandit
  - Minggu 2: Linux lanjut (pipe, proses, permission)
  - Minggu 3: Bash scripting, proses, log
  - Mini project: skrip Bash yang merangkum login gagal dari log
- [ ] **Bulan 2 — Jaringan**
  - Minggu 1: model OSI, TCP/IP, IP dan subnet
  - Minggu 2: DNS, DHCP, HTTP/HTTPS, port umum
  - Minggu 3: Wireshark dan filter dasar
  - Mini project: tangkap lalu lintas sendiri, buat laporan 1 halaman
- [ ] **Bulan 3 — Web dasar dan Python**
  - Minggu 1: request, response, cookie, session
  - Minggu 2: Burp Suite Community (Proxy, Repeater)
  - Minggu 3: Python dasar, library `requests`, Git
  - Mini project: skrip Python yang mengecek security header sebuah URL (lab/milik sendiri)

## Fase 2 — Recon dan Enumerasi (Bulan 4–5)
**Target:** dari satu IP lab, bisa menyusun daftar layanan dan kemungkinan titik masuk.

- [ ] **Bulan 4 — Nmap dan enumerasi**
  - Minggu 1: Nmap dasar (port scan, deteksi versi, script)
  - Minggu 2: enumerasi HTTP, SSH, FTP
  - Minggu 3: enumerasi SMB dan DNS
  - Mini project: enumerasi lengkap satu mesin lab
- [ ] **Bulan 5 — Recon web**
  - Minggu 1: subdomain dan identifikasi teknologi
  - Minggu 2: direktori dan parameter (ffuf, gobuster)
  - Minggu 3: mini project recon penuh + laporan singkat

## Fase 3 — Pentest Aplikasi Web (Bulan 6–9)
**Target:** menemukan dan mengeksploitasi celah web umum secara manual. Materi utama: PortSwigger Web Security Academy.

- [ ] **Bulan 6 — SQL Injection dan XSS**
  - Minggu 1: SQLi dasar (UNION)
  - Minggu 2: blind SQLi dan mitigasi (prepared statement)
  - Minggu 3: XSS reflected, stored, DOM
  - Mini project: tulis satu temuan lengkap
- [ ] **Bulan 7 — Autentikasi, session, access control**
  - Minggu 1: celah autentikasi
  - Minggu 2: session dan JWT
  - Minggu 3: access control (IDOR) dan CSRF
  - Mini project: dua temuan (IDOR dan autentikasi) lengkap dengan CVSS
- [ ] **Bulan 8 — SSRF, upload, injeksi lain**
  - Minggu 1: SSRF
  - Minggu 2: file upload dan path traversal
  - Minggu 3: command injection, XXE, deserialization, business logic
  - Mini project: rangkum OWASP Top 10 dengan bahasa sendiri
- [ ] **Bulan 9 — API dan Juice Shop**
  - Minggu 1: API testing
  - Minggu 2–3: OWASP Juice Shop dan mini-laporan 3–5 temuan
  - Minggu 4: refleksi Fase 3

## Fase 4 — Eksploitasi, Privesc, Active Directory (Bulan 10–13)
**Target:** menyelesaikan mesin lab tingkat mudah sampai menengah dari awal sampai akhir.

- [ ] **Bulan 10 — Eksploitasi dasar dan persiapan eJPT**
  - Minggu 1: konsep exploit (CVE, searchsploit)
  - Minggu 2: Metasploit dasar
  - Minggu 3: latihan untuk eJPT
  - Minggu 4: jadwalkan ujian eJPT
- [ ] **Bulan 11 — Privilege Escalation Linux**
  - Minggu 1: enumerasi lokal (`sudo -l`, SUID, cron)
  - Minggu 2: misconfiguration service dan kernel (konsep)
  - Minggu 3: mesin latihan
  - Mini project: cheat sheet privesc Linux
- [ ] **Bulan 12 — Privilege Escalation Windows**
  - Minggu 1: dasar Windows (user, service, registry)
  - Minggu 2: teknik umum (service, token, unquoted path)
  - Minggu 3: mesin latihan
  - Mini project: cheat sheet privesc Windows
- [ ] **Bulan 13 — Active Directory**
  - Minggu 1: konsep AD (domain, GPO, dasar Kerberos)
  - Minggu 2: enumerasi AD
  - Minggu 3: serangan umum dan cara bertahan (di lab)
  - Minggu 4: refleksi Fase 4

## Fase 5 — Wawasan Lebih Luas (Bulan 14–15)
- [ ] **Bulan 14 — Cloud dan sisi defensif**
  - Minggu 1: IAM dan misconfiguration cloud (pasang budget alert kalau pakai free tier)
  - Minggu 2: log dan SIEM dasar (Wazuh/Splunk di lab)
  - Minggu 3: membaca alert dan memetakan ke MITRE ATT&CK
- [ ] **Bulan 15 — CTF dan VDP**
  - Minggu 1: CTF pemula (misalnya PicoCTF)
  - Minggu 2: mesin retired + write up
  - Minggu 3: program VDP pertama (baca scope dulu)

## Fase 6 — Pelaporan dan Karier (Bulan 16–18)
- [ ] **Bulan 16 — Metodologi dan pelaporan**
  - Minggu 1: PTES, OWASP WSTG, scoping, rules of engagement
  - Minggu 2: menulis temuan (bukti, dampak, CVSS, rekomendasi)
  - Minggu 3: template laporan dan ringkasan eksekutif
- [ ] **Bulan 17 — Simulasi pentest penuh**
  - Minggu 1: perencanaan dan recon
  - Minggu 2: eksploitasi dan dokumentasi bukti
  - Minggu 3: laporan akhir dan minta umpan balik
- [ ] **Bulan 18 — Portofolio dan melamar**
  - Minggu 1: rapikan GitHub, artikel, dan Notion
  - Minggu 2: sertifikasi lanjutan dan CV
  - Minggu 3: melamar magang/junior dan latihan wawancara
  - Minggu 4: evaluasi 18 bulan dan rencana 6 bulan berikutnya

---
## Kalau jadwal terasa padat
Perpanjang bulan itu jadi 5 minggu. **Jangan memotong minggu konsolidasi.**
Kalau topik terasa mudah, percepat dan pakai sisa waktunya untuk CTF atau menulis.
