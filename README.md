# Tersine Mühendislik | Reverse Engineering

### İnteraktif Uzmanlık Portalı ve Analiz Laboratuvarı

**Geliştirici: Ayhan (AI’Han) Bozkurt — AI’Han Academy**

---

## Türkçe

### Proje Hakkında

Tersine Mühendislik Uzmanlık Portalı; fiziksel, dijital ve yapay zekâ tabanlı sistemlerin çalışma prensiplerini anlamak, bileşenlerini çözümlemek, tasarım mantığını keşfetmek ve elde edilen bilgileri mühendislik uygulamalarına dönüştürmek amacıyla geliştirilmiş interaktif bir eğitim ve teknik başvuru kaynağıdır.

Portal, tersine mühendisliği yalnızca teorik bir kavram olarak ele almak yerine kullanıcıların deneyler yapabileceği, hipotezler geliştirebileceği, teknik verileri inceleyebileceği ve kendi çözümlerini doğrulayabileceği çok disiplinli bir öğrenme ortamı sunar.

Temel kavramlardan ileri düzey mühendislik uygulamalarına uzanan içerik; üç boyutlu animasyonlar, hesaplamalı simülasyonlar, gerçek veri setleri, teknik çizimler, algoritmalar, araştırma senaryoları ve uygulamalı laboratuvarlarla desteklenmektedir.

### Temel Yaklaşım

**Gözlem → Ayrıştırma → Analiz → Modelleme → Doğrulama → Yeniden Mühendislik**

Portalın temel amacı, kullanıcıların bir teknolojiyi yalnızca kullanmalarını değil, o teknolojinin nasıl ve neden çalıştığını anlamalarını sağlamaktır.

### Eğitim Modülleri

| Modül | İçerik ve uygulamalar |
|---|---|
| 01 — Sistematik Metodoloji | Tersine mühendislik süreçleri, hipotez geliştirme, deney tasarımı, kanıt zinciri |
| 02 — Yazılım ve İkili Kod Analizi | ELF dosyaları, x86-64 Assembly, register, breakpoint, kontrol akışı, statik ve dinamik analiz |
| 03 — Kara Kutu Analizi | Sistem davranışı, histerezis, girdi-çıktı ilişkileri, parametre kestirimi |
| 04 — Fiziksel Mühendislik ve CAD/CAM | 3B tarama, parametrik modelleme, teknik çizim, sanal CNC, takım yolları |
| 05 — Hukuk ve Etik | Fikrî mülkiyet, analiz yetkisi, temiz oda mühendisliği ve teknik şartname |
| 06 — Metroloji ve Fiziksel Sistemler | Nokta bulutu, ICP algoritması, endüstriyel tomografi, geometrik sapma analizi |
| 07 — Elektronik ve Dijital Sistemler | PCB, UART, sanal multimetre, devre analizi, netlist, FFT, CRC |
| 08 — Yapay Zekâ ve Doğrulama | Sinir ağı eğitimi, mekanistik yorumlanabilirlik, ablasyon, diferansiyel test ve bitirme projesi |
| 09 — Teknik Kaynak Kütüphanesi | Teknik raporlar, bilimsel kanıt araştırması, kavram sözlüğü ve vaka atlası |

### İnteraktif Laboratuvarlar

#### Yazılım Tersine Mühendisliği

- Gerçek derlenmiş ELF dosyalarının incelenmesi
- Farklı derleyici optimizasyonlarının karşılaştırılması
- Hexadecimal ve ikili veri analizi
- x86-64 makine komutlarının adım adım yürütülmesi
- Register değerlerinin gözlemlenmesi
- Breakpoint kullanımı
- Kontrol akış grafiklerinin çözümlenmesi
- Sembolik yürütme
- Algoritma ve sistem davranışının yeniden yapılandırılması

#### Makine Mühendisliği ve CAD/CAM

- Etkileşimli üç boyutlu parça inceleme
- Yüksek yoğunluklu nokta bulutu analizi
- Geometrik unsur ve boyut kestirimi
- En küçük kareler yöntemi
- Sürüklenebilir geometrik kontrol noktaları
- Parametrik CAD modelleme
- Dinamik teknik resim ve ölçülendirme
- Takım yolu hesaplama
- Sanal CNC frezeleme
- Talaş kaldırma simülasyonu
- Takım erişilebilirliği analizi
- Geometrik tolerans ve sapma hesaplamaları
- ICP — Iterative Closest Point algoritması
- Endüstriyel bilgisayarlı tomografi
- Hacimsel kusur ve porozite incelemesi

#### Elektronik ve Donanım Mühendisliği

- Üç boyutlu PCB katmanlarının incelenmesi
- Bakır yollar ve elektriksel bağlantılar
- Netlist çıkarımı
- Sanal multimetre ve prob kullanımı
- Elektronik arıza teşhisi
- Kirchhoff yasaları
- RC ve RLC devreleri
- Rezonans ve frekans cevabı
- UART haberleşme protokolü
- Mantık analizörü
- Veri çerçeveleri ve CRC hesaplamaları
- FFT — Hızlı Fourier Dönüşümü ile titreşim analizi

#### Yapay Zekâ Tersine Mühendisliği

Yapay zekâ sistemleri hem tersine mühendislik çalışmalarında kullanılan bir araç hem de doğrudan incelenebilen bir araştırma nesnesidir.

Bu bölüm, yapay zekâ modellerinin iç temsil ve karar mekanizmalarını deneysel olarak incelemeye olanak tanır.

- Kara kutu ve beyaz kutu analizi
- Gerçek görüntü verileriyle model eğitimi
- Yapay sinir ağları
- İleri yayılım ve geri yayılım
- Aktivasyon fonksiyonları
- Ağırlık ve aktivasyon incelemesi
- Mekanistik yorumlanabilirlik
- Nöron ablasyonu
- Nedensel müdahale
- Karışıklık matrisi
- Model performansının değerlendirilmesi
- Kullanıcının çizdiği rakamların sınıflandırılması

### Yapay Sinir Ağı Mimarisi

Portal içerisinde doğrudan tarayıcıda eğitilebilen, iki gizli katmanlı bir yapay sinir ağı bulunmaktadır.

| Katman | Yapı |
|---|---|
| Girdi katmanı | 64 nöron — 8 × 8 piksel |
| Birinci gizli katman | 32 nöron — ReLU |
| İkinci gizli katman | 16 nöron — ReLU |
| Çıktı katmanı | 10 nöron — Softmax |
| Eğitilebilir parametre | 2.778 |
| Veri seti | 1.797 el yazısı rakam görüntüsü |

Modelin eğitim süreci, ağırlık güncellemeleri, tahminleri ve ablasyon deneyleri tarayıcı içerisinde hesaplanmaktadır.

### Veri Setleri ve Teknik Materyaller

Portal, yaklaşık 19 MB büyüklüğündeki tek bir HTML dosyasında kapsamlı teknik materyaller barındırmaktadır.

| Veri | Kapsam |
|---|---|
| Üç boyutlu nokta bulutu | 223.737 nokta |
| Endüstriyel tomografi | 2.457.600 voksel |
| El yazısı rakam görüntüleri | 1.797 örnek |
| Titreşim sinyali | 288.000 örnek |
| Derlenmiş yazılım örnekleri | Farklı optimizasyon düzeylerinde ELF dosyaları |
| Teknik kaynak kütüphanesi | 32 sayfalık araştırma raporu |

Fiziksel sistemlerin ölçüm verileri kontrollü mühendislik simülasyonlarıyla oluşturulurken el yazısı rakam görüntüleri gerçek veri setinden, derlenmiş yazılım örnekleri ise gerçek derleme işlemlerinden elde edilmektedir.

### Eğitim ve Öğrenme Tasarımı

Portal, pasif bilgi aktarımı yerine deneyimsel öğrenme ve araştırma temelli problem çözme yaklaşımını benimsemektedir.

Her disiplinin doğasına uygun farklı etkileşim mekanikleri kullanılır:

- Kanıt zinciri oluşturma
- Makine komutlarını adım adım yürütme
- Girdi sinyali çizme
- Üç boyutlu modelleri döndürme ve inceleme
- Parametrik geometrileri değiştirme
- Tomografi kesitlerinde kusur bölgelerini seçme
- Sanal ölçüm problarını kullanma
- Yapay sinir ağlarını eğitme
- Nöronları susturarak model davranışını karşılaştırma
- Teknik şartname hazırlama
- Bilimsel kaynaklardan kanıt toplama

Kuramsal açıklamalar, matematiksel hesaplamalar, uygulamalı görevler, çözümlü alıştırmalar ve teknik sınırlılıkların açıklanması öğrenme sürecinin ayrılmaz parçalarıdır.

### Dosya Dışa Aktarma

Laboratuvarlarda üretilen uygun veriler ve modeller farklı dosya formatlarında dışa aktarılabilir.

| Format | Kullanım amacı |
|---|---|
| CSV | Ölçüm verileri ve deney sonuçları |
| JSON | Model ağırlıkları, teknik raporlar ve yapılandırmalar |
| DXF | İki boyutlu teknik çizimler |
| OpenSCAD | Parametrik katı modeller |
| PLY | Üç boyutlu nokta bulutları |
| SVG | Vektörel teknik çizimler |
| WAV | Sinyal verileri |
| RAW | Ham hacimsel veriler |
| PNG | Görsel analiz çıktıları |
| G-code | Eğitim amaçlı sanal CNC takım yolları |

### Kullanılan Teknolojiler

- HTML5
- CSS3
- Vanilla JavaScript
- Canvas API
- SVG
- Üç boyutlu matematiksel projeksiyon
- Typed Arrays
- File API
- Blob API
- İstemci taraflı veri işleme
- Sayısal hesaplama ve optimizasyon algoritmaları
- Yapay sinir ağı eğitim algoritmaları

Haricî JavaScript kütüphanesi, sunucu, API anahtarı veya zorunlu kullanıcı hesabı gerektirmez.

### Kurulum ve Kullanım

1. Depodaki HTML dosyasını bilgisayarınıza indirin.
2. Dosyayı güncel bir web tarayıcısıyla açın.
3. İlgilendiğiniz mühendislik modülünü seçin.
4. Konu anlatımlarını inceleyin.
5. Deney parametrelerini değiştirerek sonuçları gözlemleyin.
6. Araştırma görevlerini ve doğrulama testlerini tamamlayın.
7. İhtiyaç duyduğunuz deney çıktılarını dışa aktarın.

Portal doğrudan tarayıcıda çalışır ve temel uygulamalar için internet bağlantısı gerektirmez. Haricî kaynak bağlantılarına erişmek için internet bağlantısı gerekir.

### GitHub Pages Üzerinden Yayınlama

1. HTML dosyasının adını `index.html` olarak değiştirin.
2. Dosyayı GitHub deponuzun ana dizinine yükleyin.
3. **Settings → Pages** bölümüne gidin.
4. Kaynak olarak **Deploy from a branch** seçeneğini belirleyin.
5. `main` dalını ve `/ (root)` dizinini seçin.
6. Ayarları kaydedin.

GitHub Pages tarafından oluşturulan bağlantı üzerinden portala erişebilirsiniz.

### Kimler İçin?

- Bilgisayar mühendisliği öğrencileri
- Makine mühendisliği öğrencileri
- Elektrik ve elektronik mühendisliği öğrencileri
- Yazılım geliştiriciler
- Yapay zekâ ve veri bilimi araştırmacıları
- CAD/CAM uzmanları
- Siber güvenlik araştırmacıları
- Teknik eğitimciler ve akademisyenler
- Disiplinler arası mühendislik çalışmalarıyla ilgilenenler
- Teknolojilerin çalışma prensiplerini merak eden herkes

### Bilimsel ve Teknik Kaynaklar

Portalın kavramsal çerçevesi ve teknik içeriği geliştirilirken tersine mühendislik, metroloji, yazılım analizi, elektronik mühendisliği ve yapay zekâ yorumlanabilirliği alanlarındaki literatürden yararlanılmıştır.

İlgili teknik kaynaklar ve araçlar:

- [IEEE Xplore](https://ieeexplore.ieee.org/)
- [Ghidra](https://ghidra-sre.org/)
- [ELF Generic ABI](https://gabi.xinuos.com/)
- [Microsoft PE Format](https://learn.microsoft.com/en-us/windows/win32/debug/pe-format)
- [NIST](https://www.nist.gov/)
- [OpenSCAD](https://openscad.org/)
- [FreeCAD](https://www.freecad.org/)
- [Open3D](https://www.open3d.org/)
- [KiCad](https://www.kicad.org/)
- [Wireshark](https://www.wireshark.org/)
- [sigrok](https://sigrok.org/)
- [Scikit-learn](https://scikit-learn.org/)
- [Anthropic Interpretability Research](https://transformer-circuits.pub/)
- [Neuronpedia](https://www.neuronpedia.org/)
- [arXiv](https://arxiv.org/)

### Teknik Sınırlılıklar

Portal eğitim, araştırma ve kavramsal mühendislik analizi amacıyla geliştirilmiştir.

Fiziksel sistemlere ilişkin uygulamalar kontrollü sayısal simülasyonlardır. Matematiksel hesaplamalar, dosya ayrıştırma, geometrik analizler ve yapay sinir ağı eğitimleri ise tarayıcı içerisinde gerçekleştirilmektedir.

CAD/CAM laboratuvarı profesyonel endüstriyel üretim yazılımlarının, elektronik laboratuvarı fiziksel ölçüm cihazlarının, yazılım analiz laboratuvarı ise genel amaçlı tersine mühendislik araçlarının yerine geçmez.

Üretilen eğitim amaçlı G-kodları gerçek CNC tezgâhlarında doğrudan kullanılmamalıdır.

Yazılım ve donanım analizleri yalnızca hukuka uygun biçimde edinilmiş, inceleme yetkisi bulunan sistemler üzerinde gerçekleştirilmelidir.

### Gizlilik ve Veri Güvenliği

- Kullanıcı hesabı gerektirmez.
- Analitik takip sistemi içermez.
- Kullanıcı verilerini sunucuya göndermez.
- Laboratuvar hesaplamalarını yerel olarak gerçekleştirir.
- Yüklenen dosyaları tarayıcı içerisinde işler.
- Kullanıcı verilerini kalıcı olarak depolamaz.
- Üretilen dosyalar kullanıcının kontrolünde dışa aktarılır.

---

## English

# Reverse Engineering — Interactive Expertise Portal

### About the Project

The Reverse Engineering Expertise Portal is a multidisciplinary interactive educational platform and technical reference resource designed to explore, analyze, understand, and reconstruct the operating principles of physical, digital, and artificial intelligence systems.

Rather than presenting reverse engineering exclusively as a theoretical discipline, the platform provides hands-on computational laboratories, interactive three-dimensional visualizations, real datasets, engineering simulations, and research-oriented learning activities.

### Core Methodology

**Observation → Decomposition → Analysis → Modeling → Validation → Reengineering**

The primary objective is to help learners understand not only how to use technology, but also how and why technological systems work.

### Educational Modules

| Module | Scope |
|---|---|
| 01 | Reverse engineering methodology and experimental design |
| 02 | Software engineering, binary analysis, and x86-64 Assembly |
| 03 | Black-box analysis and system identification |
| 04 | Physical reverse engineering, CAD/CAM, and virtual manufacturing |
| 05 | Legal frameworks, ethics, and clean-room engineering |
| 06 | Metrology, point clouds, ICP, and industrial tomography |
| 07 | Electronics, PCB analysis, signal processing, and communication protocols |
| 08 | Artificial intelligence, mechanistic interpretability, and validation |
| 09 | Technical reference library and scientific evidence exploration |

### Key Features

#### Software Reverse Engineering

- Real compiled ELF binary inspection
- Compiler optimization comparison
- Hexadecimal and binary data analysis
- Instruction-level x86-64 execution
- Register inspection and breakpoints
- Control-flow visualization
- Symbolic execution
- Algorithm reconstruction and behavioral validation

#### Mechanical Engineering and CAD/CAM

- Interactive three-dimensional models
- High-density point cloud analysis
- Geometric feature estimation
- Least-squares fitting
- Parametric CAD modeling
- Dynamic technical drawings
- Virtual CNC milling
- Toolpath computation
- Material removal simulation
- Geometric deviation analysis
- Iterative Closest Point registration
- Industrial computed tomography
- Volumetric defect inspection

#### Electronics and Hardware

- Multilayer PCB visualization
- Netlist reconstruction
- Interactive virtual multimeter
- Circuit fault diagnosis
- RC and RLC circuit analysis
- UART communication
- Logic analyzer simulation
- CRC computation
- Frequency response analysis
- Fast Fourier Transform

#### Artificial Intelligence

- Black-box and white-box analysis
- Browser-based neural network training
- Forward propagation and backpropagation
- Weight and activation inspection
- Mechanistic interpretability
- Neuron ablation
- Causal intervention
- Handwritten digit recognition
- Model evaluation and validation

### Neural Network Architecture

| Layer | Architecture |
|---|---|
| Input | 64 neurons |
| Hidden layer 1 | 32 neurons — ReLU |
| Hidden layer 2 | 16 neurons — ReLU |
| Output | 10 neurons — Softmax |
| Trainable parameters | 2,778 |
| Dataset | 1,797 handwritten digit images |

### Embedded Datasets

- 223,737 three-dimensional measurement points
- 2,457,600 volumetric tomography voxels
- 1,797 handwritten digit images
- 288,000 vibration signal samples
- Real compiled ELF binary examples
- A 32-page embedded technical research report

Physical measurement datasets are generated through controlled engineering simulations. Handwritten digit images and compiled binary examples are based on real data and compilation processes.

### Learning Experience

Each engineering discipline includes distinct interaction mechanisms, research scenarios, visualization techniques, and problem-solving activities.

The portal combines theoretical explanations with computational experiments, adjustable parameters, scientific reasoning, practical exercises, and validation procedures.

### Technology Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Canvas API
- SVG
- Mathematical 3D projection
- Client-side numerical computing
- Digital signal processing
- Neural network training algorithms
- Local file processing

### Getting Started

1. Download the HTML file from this repository.
2. Open it using a modern web browser.
3. Select an engineering module.
4. Explore the theoretical explanations.
5. Conduct interactive experiments.
6. Complete research and validation tasks.
7. Export your results.

The portal is distributed as a single HTML file of approximately 19 MB. No installation, backend server, API key, or mandatory user account is required.

Core laboratories can operate offline.

### Educational and Technical Disclaimer

This platform is intended for educational, scientific, and research purposes.

Physical engineering experiments are controlled numerical simulations. Computational algorithms, file parsing, numerical analysis, and neural network training are performed directly within the browser.

The platform does not replace professional industrial CAD/CAM software, certified measurement equipment, or general-purpose reverse engineering tools.

Generated G-code is intended exclusively for educational simulations and must not be used directly on industrial CNC machines.

Reverse engineering activities must respect applicable laws, intellectual property rights, contractual obligations, and authorization requirements.

### Privacy

The application processes laboratory data locally within the browser. It does not require user registration, include analytics tracking, transmit user data to a server, or permanently store personal information.

---

## Geliştirici | Developer

**Ayhan (AI’Han) Bozkurt**

AI’Han Academy

Yapay zekâ, Python, veri bilimi, oyunlaştırma, etkileşimli öğrenme ortamları ve disiplinler arası eğitim teknolojileri.

Artificial intelligence, Python, data science, gamification, interactive learning environments, and interdisciplinary educational technologies.

[Kitapyurdu](https://www.kitapyurdu.com/yazar/ayhan-bozkurt/260288.html) · [AI’Han Academy](https://ayhanbzkrt.github.io/benaihan/) · [LinkedIn](https://www.linkedin.com/in/ayhanbozkurt/) · [GitHub](https://github.com/ayhanbzkrt) · [Medium](https://medium.com/@ayhanbzkrt) · [YouTube](https://www.youtube.com/@ayhanbzkrt/videos)

---

## Telif Hakları | Copyright

© 2026 Ayhan Bozkurt — AI’Han Academy. Tüm hakları saklıdır.

İzinsiz ve ticari amaçlı kullanılamaz. Eğitim amaçlı hazırlanmıştır.

Bilgi toplamaz, kaydetmez ve paylaşmaz.

All rights reserved. Unauthorized use and commercial use are prohibited. Developed for educational purposes.

Does not collect, store, or share user data.

---

**Keywords:** Reverse Engineering, Tersine Mühendislik, CAD, CAM, CNC, Metrology, Point Cloud, ICP, Computed Tomography, Binary Analysis, Assembly, ELF, PCB, UART, FFT, Artificial Intelligence, Neural Networks, Mechanistic Interpretability, Engineering Education, Interactive Simulation, AI’Han Academy.
