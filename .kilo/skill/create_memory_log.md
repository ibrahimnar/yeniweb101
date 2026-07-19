
---

## 🛠️ Notlar & İpuçları
- Skill, **git** deposu içinde çalışıyorsa `git status --porcelain` kullanarak değişiklikli dosyaları otomatik algılayabilir; aksi takdirde kullanıcıdan “Değişen dosyalar: …” şeklinde bir liste istemeyi de destekler.  
- Eğer `memory.md` zaten çok uzun (> 2000 satır) olduğu tespit edilirse, skill en eski oturum başlığını arşive taşıyarak dosya boyutunu sınırlı tutar (isteğe bağlı).  
- Bu skill’i kendi iş akışınıza göre özelleştirmek isterseniz, dosyanın başındaki **Amaç** ve **Kullanım** bölümlerini düzenleyebilir, ek adım ekleyebilir veya çıktı biçimini (JSON, YAML vb.) değiştirebilirsiniz.

---

*Bu skill, Kilo’nun yerleşik `skill` aracılığıyla yüklenir ve her seferinde aynı yapıyı tekrar tekrar yazmanızı önler.*  
*/skill create_memory_log ile çağırılayor.*