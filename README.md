# 👁️ PaliGemma 2 Visual Question Answering (VQA) & OCR Benchmark

Bu proje, **Google PaliGemma 2** multimodal (Vision-Language) modelinin farklı Türkçe ve İngilizce görsel soru-cevaplama (VQA) ve metin okuma (OCR) görevlerindeki performansını ölçmek ve değerlendirmek amacıyla hazırlanmıştır.

Deney kapsamında model; fiş tutarı okuma, müzik notası tanıma, nesne sayma ve medikal görüntü (röntgen) analizi gibi farklı alanlardaki görsellerle test edilmiştir.

---

## 📸 Test Edilen Senaryolar

| Görsel | Görev Türü | Türkçe Soru | İngilizce Soru | Beklenen Yanıt (Ground Truth) |
| :--- | :--- | :--- | :--- | :--- |
| **`tabela.jpg`** | OCR | *(Metin Okuma)* | - | `Marmaris Datça Ula Muğla İzmir Köyceğiz Dalaman Antalya` |
| **`fis.jpg`** | VQA / OCR | Fişin toplam tutarı nedir? | What is the total amount on the receipt? | `82,55` |
| **`nota.jpg`** | VQA | Portedeki notaları soldan sağa sırasıyla yaz (Örn: la si do). | List all notes on the staff from left to right (e.g. la si do). | `A, B, C, D, E, D, C, B.` |
| **`nota.jpg`** | VQA / Count | Bu portede kaç nota var? | How many notes are on this staff? | `8` |
| **`hayvan.jpg`** | VQA / Count | Fotoğrafta kaç hayvan var? | How many animals are in the photo? | `2` |
| **`rontgen.jpg`** | VQA / Medikal | Görseldeki el röntgeninde kaç tane vida var? Sadece tek bir rakam yaz (Örn: 3). | How many screws are there in the hand X-ray shown in the image? Write only a single number (e.g., 3). | `5` |

---