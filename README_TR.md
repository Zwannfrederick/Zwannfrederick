<div align="center">

# Muhammed Emin Çelik

### AI / LLM Sistemleri Mühendisi

**LLM Runtime · Agent & RAG · On-Prem Inference · Robotik & CV · Gerçek Zamanlı AI**

<p>
  <a href="./README.md"><img src="https://img.shields.io/badge/EN-English-1f6feb?style=for-the-badge" alt="English"></a>
  <a href="./README_TR.md"><img src="https://img.shields.io/badge/TR-T%C3%BCrk%C3%A7e-e30a17?style=for-the-badge" alt="Türkçe"></a>
</p>

<i>Runtime kısıtlarından gerçek dünya etkileşimine uzanan, ölçülebilir ve güvenilir AI sistemleri geliştiriyorum.</i>

</div>

---

## `$ whoami`

Üretim odaklı LLM sistemleri, agent iş akışları, yerel inference, bilgisayarlı görü ve robotik üzerinde çalışan bir Bilgisayar Mühendisliği öğrencisiyim. Ana ilgi alanım, etkileyici bir model demosuyla insanların gerçekten güvenebileceği bir yazılım arasındaki mühendislik katmanı.

Retrieval kalitesi, gecikme, değerlendirme, hata biçimleri, GPU kısıtları, model serving ve sürdürülebilirlik üzerine çalışıyorum. Özellikle dil modellerinin bağlam getirdiği, araç kullandığı, kaynaklara dayalı karar verdiği ve insanlarla ya da fiziksel dünyayla etkileştiği sistemlerle ilgileniyorum.

## 🧠 Sistem Odağı

### LLM runtime & on-prem inference

Yerel ve bulut modelleri, gizlilik odaklı dağıtım, model serving ve donanım farkındalıklı optimizasyonlarla çalışıyorum. **ARGUS**, sistem çalışmalarımın merkezinde: KV cache davranışı, GPU bellek baskısı, quantization, paging ve gerçek inference kısıtlarını araştıran bir LLM runtime mühendisliği projesi. Çalışma; C++, CUDA ve Triton, runtime entegrasyonu ve tekrarlanabilir benchmark süreçlerini kapsıyor—tek bir sentetik sonucu üretim iddiası gibi sunmadan.

### RAG, agent & uygulamalı AI

Grounding, bellek ve değerlendirmeyi merkeze alan retrieval hatları ve araç kullanan agent iş akışları tasarlıyorum. Hedef tek seferlik etkileyici bir cevap değil; doğru bağlamı getiren, doğru aracı seçen, hatadan dönebilen ve sonucu incelenebilen bir sistem.

### Robotik, görü & gerçek zamanlı etkileşim

Çalışmalarım YOLO eğitim pipeline’ları, simülasyon tabanlı robot kontrolü, konuşma analizi ve gerçek zamanlı avatarlara da uzanıyor. Yapay zekânın sohbet penceresinden çıkıp algı, planlama, zamanlama, görsel girdi veya insan etkileşimiyle uğraşmak zorunda kaldığı projeleri seviyorum.

## 🚀 Seçili Çalışmalar

- **ARGUS — LLM runtime mühendisliği:** KV cache, GPU belleği, quantization, paging ve inference darboğazlarını C++/CUDA/Triton entegrasyonu ve tekrarlanabilir benchmark’larla araştıran sistem projesi.
- **RoboTeach — LLM kontrollü robotik:** LLM muhakemesini PyBullet simülasyon ortamındaki policy tabanlı robot kontrolüne bağlayan açık kaynak bitirme projesi. Python tabanlı sistem; simulation, planner, perception, skills ve evaluation modüllerini ayırıyor; doğrulanmış stack’inde NumPy ve Groq bulunuyor.
- **Multi-tenant Restoran AI Asistanı:** Özsüt, Taşocak ve Simit Sarayı gibi restoran markaları için, merkez LangChain tarzı agent/node mimarisi ve işletmeye özel tool’larla doğal dilden müşteri siparişi alan AI servis asistanı.
- **Gerçek Zamanlı AI Avatar:** konuşma, ses, lip-sync ve GPU destekli gerçek zamanlı avatar sunumunu daha insansı servis etkileşimleri için birleştiren sisteme teknik mentörlük.
- **Okuma Analizi:** çocukların okuma sesini referans konuşmayla karşılaştırarak okuma farklılıklarını ve performansını analiz eden araştırma odaklı sistem.
- **Erişilebilirlik Asistanı:** görme engelli üniversite kullanıcıları için gerçek dünya ihtiyacına yönelik geliştirilen ve basına yansıyan erişilebilirlik projesi.
- **İHA / YOLO Pipeline:** insansız hava aracı senaryosu için veri seti hazırlama, YOLO eğitimi ve değerlendirmeyi kapsayan bilgisayarlı görü iş akışı.
- **AI Ürün Sistemleri:** doküman ve sunum üretimi ile fikir, senaryo, kapak ve teleprompter süreçlerini destekleyen AI tabanlı içerik iş akışları.

## ⚙️ AI-Native Geliştirme

Agentic coding yaygınlaşmadan önce yazılımı geleneksel biçimde yazıyordum. Bugün coding agent’ları implementasyon, refactoring, test, debugging ve araştırmada yoğun kullanırken mimariyi, sistem tasarımını, değerlendirmeyi ve teknik kararları kendim yönetiyorum.

Bu yaklaşım **agent-assisted engineering** ve **agent-orchestrated development**: agent’lar uygulamayı hızlandırırken sistem sınırları, entegrasyon riskleri, benchmark’lar ve nihai karar benim sorumluluğumda kalıyor. AI-native geliştirme, sistemi anlamanın yerine geçmez; bir mühendislik çarpanıdır.

<div align="center">

<sub><code>Build -> Measure -> Break -> Fix -> Benchmark -> Ship</code></sub>

</div>

## 🛠 Temel Stack

| Alan | Seçili araçlar |
|---|---|
| **Ana diller** | Python · JavaScript · SQL |
| **Sistem / AI** | C · C++ · CUDA · Triton · PyTorch · Transformers · vLLM |
| **Agent / Backend** | LangGraph · FastAPI · PostgreSQL · Redis |
| **Görü / Robotik** | OpenCV · YOLO · PyBullet |
| **Ürün / Dağıtım** | React · Dart / Flutter · Docker · Linux |
| **Ek deneyim** | Java · Ruby on Rails · C# / .NET · Rust |

Runtime mühendisliği için C++, CUDA ve Triton tarafında derinleşmeye devam ediyorum. Go mevcut stack’imin bir parçası değil; doğru sistem problemi gerektirdiğinde öğrenmeye açığım.

<div align="center">

## 🌍 Diller

<p>
  <img src="https://img.shields.io/badge/T%C3%BCrk%C3%A7e-Ana_Dil-e30a17?style=for-the-badge" alt="Türkçe — Ana dil">
  <img src="https://img.shields.io/badge/English-Advanced-1f6feb?style=for-the-badge" alt="İngilizce — İleri">
</p>
<p>
  <img src="https://img.shields.io/badge/Espa%C3%B1ol-Familiar-f1c40f?style=flat-square" alt="İspanyolca — Aşinalık">
  <img src="https://img.shields.io/badge/Fran%C3%A7ais-Familiar-3498db?style=flat-square" alt="Fransızca — Aşinalık">
  <img src="https://img.shields.io/badge/Deutsch-Familiar-555555?style=flat-square" alt="Almanca — Aşinalık">
</p>

<sub>Merak varsayılan ayarım. Problem gerektirdiğinde yeni bir dil veya teknoloji öğrenmekten çekinmem.</sub>

</div>
