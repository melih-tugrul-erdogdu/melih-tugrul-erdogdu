# 👋 Hi, I'm Melih Tuğrul Erdoğdu; (EN)

### 🎓 About Me
I'm a third-year Computer Engineering student at Galatasaray University, currently spending the year at the University of Lille on an Erasmus+ exchange. I'm deeply interested in software development, algorithm design and data-driven problem solving, and I have a strong curiosity about artificial intelligence.

### 💡 Technologies I Know
- **Programming Languages:** C, Python, Java, SQL, HTML
- **Data Science and Libraries:** Pandas, NumPy, Matplotlib, Seaborn, statsmodels, SciPy
- **Optimization and Algorithms:** OR-Tools (vehicle routing, constraint programming), spatial indexing, fuzzy text matching (thefuzz / Levenshtein)
- **Application and Data Layer:** Streamlit, SQLite, openpyxl, Folium, REST API integration (Google Maps Platform — Places, Geocoding, Maps JavaScript, Directions)
- **Tools:** VS Code, Git, GitHub, LaTeX, IntelliJ
- **Other:** Basic to intermediate electronics (Arduino IDE, Vivado, Verilog)

### 🚀 Projects

**1. 🚚🗺️ [Field Lead Discovery and Route Integration Engine](https://github.com/melih-tugrul-erdogdu/lead-discovery-route-engine)**
* An end-to-end lead discovery system for field sales teams: it compares a Google Places scan against a CRM customer base and works out which businesses are genuinely new.
* Matching engine: name normalization, spatial indexing and a five-layer promotion architecture ordered by quality of evidence, built to resolve the mismatch between a company's tax office title and the name painted on its sign.
* Route integration: vehicle routing with time windows (VRP) using OR-Tools; leads are slotted into the route a rep already drives, each one costed as a detour in minutes.
* Cost architecture: four separate SKUs tracked, tiered query strategy, adaptive subdivision of saturated grid cells, per-run and monthly budget brakes, and checkpoints that resume an interrupted run where it stopped.
* SQLite state management: opening and closure detection across runs, and a closed loop that feeds field feedback back into the next run.
* Streamlit panel (8 tabs, live map through the Google Maps JavaScript API), a synthetic sample data generator and bilingual documentation. ~11,800 lines of Python across 17 modules.

**2. 📊 [Stack Overflow Survey Data Analysis](https://github.com/melih-tugrul-erdogdu/StackOverflow-Survey-Data-Analysis)**
* Comprehensive descriptive and inferential statistical analysis of the 2024 Stack Overflow Developer Survey (N=20,754).
* Mathematically disproving the "AI raises salaries" assumption using hypothesis testing (t-test, ANOVA) and multiple linear regression (OLS).
* A two-stage academic paper written in IEEE format using LaTeX.

**3. ⏳ [ChronoRift (Java OOP Game)](https://github.com/melih-tugrul-erdogdu/ChronoRift-OOP)**
* A time-travel themed RPG built around five different historical chapters.
* Written from scratch in Java using object-oriented principles: inheritance, polymorphism, interfaces and custom exception handling.
* Designed with a modular architecture, including a dynamic combat loop, inventory and shop management systems.

**4. ⚙️ [8-Bit ALU Design on Basys 3 FPGA](https://github.com/melih-tugrul-erdogdu/Basys3-8Bit-ALU-Design)**
* An 8-bit Arithmetic Logic Unit designed in Verilog for the Basys 3 FPGA board.
* Built with 256 bytes of RAM, sixteen 8-bit registers and support for 16 different operations.
* BCD converter integrated for decimal and signed number display on the 7-segment displays.

**5. 🔍 [Modularity Detection on Zachary Karate Club (C)](https://github.com/melih-tugrul-erdogdu/Community-Detection-Algorithms-C)**
- A modularity detection algorithm for social network analysis.
- Implemented in C.
- Computes and prints the best possible community structures.

**6. 🌱 [Automatic Plant Watering System](https://github.com/melih-tugrul-erdogdu/Arduino-Automatic-Plant-Watering-System)**
- An Arduino-based automatic irrigation system.
- Measures soil moisture with a humidity sensor.
- Waters the plant automatically when moisture drops below a set level.
- [Watch the demo](https://youtube.com/shorts/vhjwoos76hg)

**7. 🐍 [Snake Game (C)](https://github.com/melih-tugrul-erdogdu/Snake-Game-C)**
- The classic snake game, running in the console.
- Developed in C.
- Played with the arrow keys.

### 📚 Currently Learning
- Web Development
- Data Analysis
- Machine Learning
- Neural Networks
- Functional Programming (Haskell)
- Operating Systems

### 🎯 Goals
- Learn C++ and become properly fluent in SQL
- Build web development projects
- Produce more data science projects
- Contribute actively on GitHub
- Take part in open source projects
- Publish my own projects regularly

### 📫 Contact
- **Email:** mlhtugrul07@gmail.com
- **LinkedIn:** https://www.linkedin.com/in/melih-tuğrul-erdoğdu-b222422b0/

⭐ **Thanks for visiting my profile!**

# 👋 Merhaba, Ben Melih Tuğrul Erdoğdu; (TR)

### 🎓 Hakkımda
Galatasaray Üniversitesinde 3. sınıf Bilgisayar Mühendisliği öğrencisiyim. Şuanda 3. sınıfı Erasmus+ kapsamında Lille Üniversitesinde okuyorum. Yazılım geliştirme, algoritma tasarımı ve veriye dayalı problem çözme konularına yoğun ilgi duyuyorum. Yapay zeka üzerine de derin bir merak besliyorum.

### 💡 Bildiğim Teknolojiler
- **Programlama Dilleri:** C, Python, Java, SQL, HTML
- **Veri Bilimi ve Kütüphaneler:** Pandas, NumPy, Matplotlib, Seaborn, statsmodels, SciPy
- **Optimizasyon ve Algoritma:** OR-Tools (araç rotalama, kısıt programlama), uzamsal indeksleme, bulanık metin eşleştirme (thefuzz / Levenshtein)
- **Uygulama ve Veri Katmanı:** Streamlit, SQLite, openpyxl, Folium, REST API entegrasyonu (Google Maps Platform — Places, Geocoding, Maps JavaScript, Directions)
- **Araçlar:** VS Code, Git, GitHub, LaTeX, IntelliJ
- **Diğer:** Temel-orta elektronik (Arduino IDE, Vivado, Verilog)

### 🚀 Yaptığım Projeler

**1. 🚚🗺️ [Saha Lead Keşif ve Rota Entegrasyon Motoru](https://github.com/melih-tugrul-erdogdu/lead-discovery-route-engine)**
* Google Places taramasını bir CRM müşteri tabanıyla karşılaştırarak gerçekten yeni olan işletmeleri ayıklayan, saha satış ekipleri için uçtan uca lead keşif sistemi.
* Eşleştirme motoru: vergi unvanı ile tabela adı arasındaki uyuşmazlığı çözmek için isim normalizasyonu, uzamsal indeksleme ve kanıt kalitesine göre sıralanmış beş katmanlı terfi mimarisi.
* Rota entegrasyonu: OR-Tools ile zaman pencereli araç rotalama (VRP); lead'ler temsilcinin mevcut günlük rotasına, her biri için dakika cinsinden sapma maliyeti hesaplanarak yerleştiriliyor.
* Maliyet mimarisi: dört ayrı SKU takibi, kademeli sorgu stratejisi, doygun ızgara karelerinde uyarlamalı alt bölme, koşu başına ve aylık bütçe frenleri, kesinti hâlinde kaldığı yerden devam eden kurtarma noktaları.
* SQLite tabanlı durum yönetimi: koşular arası açılış ve kapanış tespiti, sahadan gelen geri bildirimin bir sonraki koşuya beslendiği kapalı döngü.
* Streamlit paneli (8 sekme, Google Maps JavaScript API ile canlı harita), sentetik örnek veri üreteci ve iki dilli dokümantasyon. ~11.800 satır Python, 17 modül.

**2. 📊 [Stack Overflow Anketi Veri Analizi](https://github.com/melih-tugrul-erdogdu/StackOverflow-Survey-Data-Analysis)**
* 2024 Stack Overflow Geliştirici Anketi üzerinde kapsamlı betimsel ve çıkarımsal istatistiksel veri analizi (N=20.754).
* Hipotez Testleri (T-Test, ANOVA) ve Çoklu Doğrusal Regresyon (OLS) kullanılarak "Yapay Zeka Maaşı Artırır" yanılgısının matematiksel olarak çürütülmesi.
* LaTeX kullanılarak IEEE formatında, iki aşamalı akademik makale yazımı.

**3. ⏳ [ChronoRift (Java OOP Oyunu)](https://github.com/melih-tugrul-erdogdu/ChronoRift-OOP)**
* 5 farklı tarihsel bölümden oluşan, zaman yolculuğu temalı RPG (Rol Yapma) oyunu.
* Java dilinde; Kalıtım, Çok Biçimlilik, Arayüzler ve Özel Hata Yönetimi gibi Nesne Yönelimli Programlama (OOP) prensipleri kullanılarak sıfırdan geliştirildi.
* Modüler bir mimariyle tasarlanmış olup dinamik savaş döngüsü, envanter ve mağaza yönetim sistemleri içerir.

**4. ⚙️ [Basys 3 FPGA Üzerinde 8-Bit ALU Tasarımı](https://github.com/melih-tugrul-erdogdu/Basys3-8Bit-ALU-Design)**
* Verilog kullanılarak Basys 3 FPGA kartı üzerinde 8-bitlik Aritmetik Mantık Birimi (ALU) donanım tasarımı.
* 256 bayt RAM, 16 adet 8-bitlik yazmaç (register) ve 16 farklı işlem (komut) desteği ile kurgulandı.
* 7-segment ekranlarda onluk tabanda ve işaretli sayı gösterimi için BCD dönüştürücü entegrasyonu sağlandı.

**5. 🔍 [Modularity Detection on Zachary Karate Club (C)](https://github.com/melih-tugrul-erdogdu/Community-Detection-Algorithms-C)**
- Sosyal ağ analizi için modularity detection algoritması.
- C dilinde implementasyon.
- Olası en iyi topluluk yapılarını hesaplama ve ekrana bastırma.

**6. 🌱 [Automatic Plant Watering System](https://github.com/melih-tugrul-erdogdu/Arduino-Automatic-Plant-Watering-System)**
- Arduino tabanlı otomatik sulama sistemi.
- Nem sensörü ile toprak nemini ölçme.
- Belirlenen seviyenin altına düştüğünde otomatik sulama.
- [Demoyu İzle](https://youtube.com/shorts/vhjwoos76hg)

**7. 🐍 [Snake Game (C)](https://github.com/melih-tugrul-erdogdu/Snake-Game-C)**
- Konsol üzerinde çalışan klasik yılan oyunu.
- C programlama dili ile geliştirildi.
- Klavye üzerindeki yön tuşları ile oynanabilir.  

### 📚 Şu Anda Öğrendiklerim
- Web Geliştirme
- Veri Analizi
- Makine Öğrenmesi
- Nöral Ağlar
- Fonksiyonel Programlama (Haskell)
- İşletim Sistemleri

### 🎯 Hedeflerim
- C++ öğrenmek ve SQL'de ustalaşmak
- Web geliştirme projeleri yapmak
- Daha çok veri bilimi projesi üretmek
- GitHub'da aktif katkı sağlamak
- Açık kaynak projelere katılmak
- Kendi projelerimi düzenli olarak yayımlamak

### 📫 İletişim
- **E-posta:** mlhtugrul07@gmail.com
- **LinkedIn:** https://www.linkedin.com/in/melih-tuğrul-erdoğdu-b222422b0/

⭐ **Profilimi ziyaret ettiğiniz için teşekkür ederim!**
