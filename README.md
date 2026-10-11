# Araştırma Paneli — Dr. Öğr. Üyesi Tolga Topçubaşı

Makaleler, projeler, bildiriler, kitaplar ve etik kurul onaylarının tek sayfada toplandığı kişisel araştırma paneli.
Site GitHub Pages ile yayınlanır; içerik `data.json` dosyasından okunur.

## Yeni çalışma eklemek

1. GitHub'da `data.json` dosyasını açın, sağ üstteki kalem simgesine tıklayın.
2. İlgili listeye (`makaleler`, `projeler`, `bildiriler`, `etikKurul`, `kitaplar`) yeni bir satır ekleyin. Örnek:

```json
{
  "baslik": "Yeni makalenin başlığı",
  "durum": "Gönderime hazır",
  "yil": 2026,
  "etiketler": ["Yapay Zekâ Etiği"],
  "drive": "https://drive.google.com/drive/folders/KLASOR_ID"
}
```

3. "Commit changes" deyin. Site bir iki dakika içinde güncellenir.

## Gizlilik

- Drive bağlantıları dosyaların paylaşım ayarına bağlıdır. Dosyalar "Kısıtlı" kaldıkça yalnızca sahibi açabilir; sitede sadece başlıklar görünür.
- Kitaplar `"goster": false` ile gizli tutulur; yayınlamak istediklerinizi `true` yapın.
- Öğrenci çalışmalarında öğrenci adları yalnızca baş harfle gösterilir.
