# Penetration Tester Journey

Catatan belajar penetration testing selama **18 bulan** (Nov 2026 – Mei 2028), 8–10 jam per minggu.
Repo ini dipakai untuk melacak progres, menyimpan catatan, dan menunjukkan hasil belajar.

## Gambaran singkat
| Fase | Bulan | Fokus | Status |
|---|---|---|---|
| 1 | 1–3 | Fondasi: Linux, Jaringan, Web dasar, Python | 🔄 Berjalan |
| 2 | 4–5 | Recon dan enumerasi (Nmap, ffuf) | ⬜ |
| 3 | 6–9 | Pentest aplikasi web (OWASP, Burp, Juice Shop) | ⬜ |
| 4 | 10–13 | Eksploitasi dasar, Privilege Escalation, Active Directory | ⬜ |
| 5 | 14–15 | Cloud, sisi defensif, CTF, VDP | ⬜ |
| 6 | 16–18 | Pelaporan, simulasi pentest, portofolio | ⬜ |

## Cara pakai repo ini
1. Buka [roadmap](roadmap/roadmap.md) untuk melihat target tiap bulan.
2. Ikuti [ritme mingguan](roadmap/ritme-mingguan.md).
3. Setiap minggu, salin [template log](templates/weekly-log.md) ke `logs/`.
4. Setiap Sabtu, tulis satu artikel di `articles/` (kerangka ada di `templates/article.md`).
5. Setiap lab selesai, catat di `labs/` memakai [template catatan lab](templates/lab-note.md).
6. Perbarui [skill checklist](skill-checklist.md) setiap akhir bulan.

## Isi repo
| Folder / berkas | Fungsi |
|---|---|
| `roadmap/` | Rencana 18 bulan, ritme mingguan, detail harian Bulan 1 |
| `logs/` | Log mingguan dan review bulanan |
| `notes/` | Ringkasan materi per topik |
| `labs/` | Catatan tiap lab |
| `writeups/` | Write up mesin yang boleh dipublikasi |
| `articles/` | Draf artikel mingguan |
| `reports/` | Laporan pentest dari lab |
| `scripts/` | Skrip kecil buatan sendiri |
| `certs/` | Progres sertifikasi |
| `skill-checklist.md` | Daftar skill dan statusnya |
| `templates/` | Template siap salin |

## Aturan wajib
- Latihan **hanya** di lingkungan legal: TryHackMe, PortSwigger Academy, OverTheWire, Hack The Box, OWASP Juice Shop, DVWA, atau VM milik sendiri.
- Jangan menguji sistem orang lain tanpa izin tertulis (bisa dijerat UU ITE).
- Di program bug bounty/VDP, baca scope dulu dan kirim hanya laporan yang jelas dan bisa direproduksi.
- Jangan publikasikan mesin Hack The Box yang masih aktif, kredensial, data target nyata, atau flag yang dilarang dibagikan.
- Pakai perangkat lunak legal (misalnya Burp Suite Community).
- Tulis dengan bahasa sendiri, jangan salin materi kursus.
- Cek ruang disk (`df -h /`) setiap awal bulan. Siapkan 20–30 GB bebas sebelum membuat VM Kali.
