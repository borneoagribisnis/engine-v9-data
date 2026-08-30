
# engine-v9-data - Data untuk Engine V9 Frontend Netlify

## Cara Update Lewat Chat ke Meta AI:

1. Upload file Excel baru di chat Meta AI:
   - SESI_2_29_Agustus_2026.xlsx
   - SDPC_Agustus_2026.xlsx
   - BWPT_Agustus_2026.xlsx
   - Update_Broksum_29_Agustus_2026.xlsx
   - Format: IHSG -0.30%

2. Meta AI parse:
   - SDPC XA 38M vs PD 25.2M
   - BWPT HP 2.2B vs AK 3B
   - Teknikal 560 -> 288 filter
   - Return 3 JSON baru

3. Download 3 JSON dari Meta AI
4. Upload ke repo ini (drag & drop di github.com) -> Commit
5. Frontend Netlify auto-fetch JSON terbaru - Orang banyak langsung lihat update!

## File:
- news_terbaru.json - Real news IHSG 26-28 Aug + alasan demo, properti +1.41%, minyak turun, Nvidia +106% - Update tiap pagi 08:30
- teknikal_terbaru.json - 288 filter 51-599 + SDPC 200 +5.26% HOLD + BWPT 107 +4.90% HOLD/WAIT + Real Backtest 72.3%
- broksum_terbaru.json - 55 emiten + DMAS AK 33.1B + SSTM YP 113M + RMKO XL 890M vs CC 947M + SDPC XA 38M + BWPT HP 2.2B

## Frontend:
Frontend di Netlify fetch dari:
https://raw.githubusercontent.com/USERNAME/engine-v9-data/main/news_terbaru.json
https://raw.githubusercontent.com/USERNAME/engine-v9-data/main/teknikal_terbaru.json
https://raw.githubusercontent.com/USERNAME/engine-v9-data/main/broksum_terbaru.json

Ganti USERNAME dengan username GitHub Anda di frontend HTML.

## Link Frontend:
https://engine-v9.netlify.app (ganti dengan link Netlify Anda)
