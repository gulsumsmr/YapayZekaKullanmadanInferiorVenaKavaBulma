# Yapay Zeka Kullanmadan Inferior Vena Kava Bulma

# Inferior Vena Cava Nedir?

**Inferior Vena Cava (IVC)**, vücudun alt kısmındaki (bacaklar, pelvis ve karın) kirli kanı kalbin sağ kulakçığına taşıyan **en büyük toplardamardır**.  
Tıpta sıklıkla görüntüleme ve değerlendirme yapılan bu damar, bazı klinik vakaların analizinde önemli bir rol oynar.

Bu projede, inferior vena cava’ya ait bazı veriler üzerinden yapay zekâ kullanmadan benzer vakalarla eşleştirme yapılmaktadır.
---

## 🔍 Proje Amacı

Yapay zeka yöntemlerine gerek kalmadan, görüntü işleme teknikleriyle tıbbi görüntülerde **Inferior Vena Cava** bölgesini otomatik olarak tespit etmek ve işaretlemek.

Tıbbi uygulamalarda doktorların geçmiş vakaları inceleyerek karar vermesine yardımcı olabilecek basit ama etkili bir algoritma hedeflenmiştir. Bu sistemde:

- Veriler doğrudan karşılaştırılır.
- Özellikler arasında benzerlik oranı hesaplanır.
- Eşik değer üzerindeki en uygun vaka tespit edilir.

## Kullanılan Teknikler

**Görüntü Ön İşleme:** Görseller üzerinde filtreleme, kontrast artırma, gürültü azaltma gibi işlemlerle görüntü kalitesi yükseltilir.

**HOG (Histogram of Oriented Gradients):** Görüntüdeki kenar ve şekil özelliklerinin çıkarılması için kullanılan klasik bir özellik çıkarım yöntemi.

**Co-HOG (Co-occurrence HOG):** HOG özelliklerinin eşzamanlı (co-occurrence) analizine dayanarak daha anlamlı doku ve yapısal özelliklerin yakalanmasını sağlar.

**Alan Tespiti:** Elde edilen özellikler kullanılarak Inferior Vena Cava'nın bulunduğu alan görüntü üzerinde işaretlenir.



