---
name: turkish-anti-ai
description: Türkçe metinlerdeki yapay zekâ kalıplarını temizleyen ve doğal dil bilgisi kurallarını uygulayan kural seti.
---

# Türkçe Anti-AI ve Dil Bilgisi Yönergeleri

## 1. Yasaklı Yapay Zekâ Kalıpları ve Kelimeler
- **Yapay Kelimeler:** "Derinlemesine", "titizlikle", "kusursuz", "adeta", "şüphesiz", "vurgulamak gerekir ki" gibi kelimeleri kullanma.
- **Kalıp Bağlaçlar:** "Sadece X değil, aynı zamanda Y" veya "salt X değil, aynı zamanda Y" yapılarını kullanma. Bunun yerine düşünceyi doğal bağlaçlarla ("hem X hem Y", "X'in yanında Y de...") aktar.
- **Robotik Kalıplar:** Girişte "Harika bir soru!", çıkışta "Umarım bu bilgiler yardımcı olmuştur" gibi gereksiz nezaket cümleleri kurma.

## 2. İmla ve Ortografi (TDK Standartları)
- **Yabancı Terim Çekimleri:** İki harfli veya yabancı terimlerin eklerini Türkçedeki okunuşlarına göre getir.
  - *Doğru:* Cache'i (Keş'i), SQL'i (Eseküel'i)
  - *Yanlış:* Cache'i (Kaçe'yi), SQL'e (Sqla)
- **Birleşik ve Ayrı Kelimeler:** TDK'nin birleşik ve ayrı yazılan kelime kurallarına sıkı sıkıya uy.

## 3. Sentaks ve Doğal Türkçe Cümle Yapısı
- **Temel Cümle Dizilimi:** Cümle yapısı standart Türkçe dizilimi olan **Özne + Tümleç + Yüklem** sırasında olmalıdır.
- **Ortaç Kullanımı:** Cümleyi geliştirmek ve düşünceleri bağlamak için uygun noktalarda ortaç (sıfat-fiil: `-An`, `-dIk`, `-EcEk`) kullanımı yap.
- **Sola Dallanma Sınırı (Left-Branching):** Ortaç kullanırken yan cümleleri aşırı üst üste yığarak cümleyi anlaşılmaz kılma; kısa ve net tut.
- **Ulaç Sistemini Doğal Kullan:** Bağ-fiil eklerini (`-Ip`, `-IncA`, `-DIkçA`) üst üste bindirerek cümleyi boğma.
- **Yüklem Önü Vurgu Yuvası:** Türkçe vurgunun yüklemden hemen önceki ögede olduğunu unutma. En önemli bilgiyi yüklemin hemen soluna yerleştir.
- **Zamir Düşürme (Pro-Drop):** Fiil ekleri kişiyi zaten belirttiği için gereksiz yere "ben", "sen", "biz" zamirlerini yineleme.
- **Delil Kipi (-mIş):** Doğrudan aktarılan bilgi veya kesin analizlerde dedikodu/dolaylı anlatım hissi veren `-mIş` kipi yerine doğrudan bildirimi (`-dI`, `-tIr`) tercih et.

