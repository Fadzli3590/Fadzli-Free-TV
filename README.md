# Fadzli Free TV

Playlist IPTV percuma untuk saluran TV Malaysia dengan siaran dalam talian yang boleh dicapai secara terbuka.

## Saluran dalam playlist

TV1, TV2, TV OKEY, Berita RTM, Sukan RTM, TV6, Dewan Rakyat dan Dewan Negara.

## TV3

TV3 ialah saluran sasaran projek, tetapi belum dimasukkan sebagai URL M3U kerana siaran langsung rasmi disediakan melalui [Tonton](https://www.tonton.com.my/) dan mungkin memerlukan akaun percuma. Saya tidak akan masukkan URL tidak rasmi atau pautan yang memintas log masuk. Gunakan aplikasi rasmi Tonton untuk TV3.

## Guna pada Android TV

1. Pasang pemain IPTV yang menyokong M3U, HLS dan HTTP headers (contohnya VLC atau Kodi).
2. Masukkan URL playlist ini:
   `https://raw.githubusercontent.com/Fadzli3590/Fadzli-Free-TV/main/playlist.m3u`
3. Jika saluran tidak dimainkan, semak semula siaran melalui platform rasmi RTMKlik.

## Tambah atau buang saluran

Edit fail `playlist.m3u`. Setiap saluran mempunyai blok `#EXTINF` dan URL HLS. Untuk tambah saluran, masukkan blok baharu dengan URL siaran awam yang sah. Untuk buang saluran, padam blok tersebut.

## Nota

- URL siaran boleh berubah, tamat tempoh atau tertakluk kepada lokasi dan hak siaran.
- Pemain mungkin perlu menyokong header `Referer` dan `User-Agent`.
- Projek ini tidak mengehos atau mengedarkan semula video dan tidak berafiliasi dengan RTM atau Media Prima.

## Platform rasmi

- [RTMKlik](https://rtmklik.rtm.gov.my/)
- [Tonton](https://www.tonton.com.my/)
- [RTMKlik Android TV](https://play.google.com/store/apps/details?id=my.gov.rtm.tv)
