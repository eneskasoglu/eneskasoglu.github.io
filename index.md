---
layout: page
title: "About me"
---

<img src="{{ '/assets/img/me.jpg' | relative_url }}" alt="Enes Kaşoğlu" width="180" style="border-radius:12px;display:block;margin:0 auto 10px;" />

# Enes Kaşoğlu
Embedded & FPGA Engineer · Köln, DE  
✉️ enes@example.com · 🔗 [LinkedIn](https://www.linkedin.com/in/eneskasoglu) · 💻 [GitHub](https://github.com/eneskasoglu)

[📄 CV’mi indir]({{ '/assets/cv/Enes-Kasoglu-CV.pdf' | relative_url }}){: .btn .btn-primary }

---

## Özet
Gerçek zamanlı gömülü sistemler, FPGA ve Linux tabanlı çözümler geliştiriyorum. Donanımdan uygulamaya **uçtan uca** geliştirme (driver ↔ userspace entegrasyonu), **düşük gecikmeli görüntü işleme**, **Yocto/Buildroot**, **GStreamer**, **DMA** ve **CI/CD** rutinleri temel uzmanlık alanlarım.

> Focus: Zynq/ZU+ MPSoC, Spartan-7, Vitis/Vivado, device-tree, U-Boot, kernel modülleri, userspace I/O (UIO).

---

## Deneyim
- **Embedded Software Engineer — Bertrandt (DE)** · *2023–güncel*  
  - Raylı sistem konvertör projeleri (örn. B7 serisi **Aux-Converter**), otomotiv/rail validasyon & test.  
  - **C/C++** (RTOS & Linux), **Python** test/araç scriptleri, **Git & JIRA** süreçleri, ASPICE uyumlu geliştirme.  
  - Gömülü Linux üzerinde sürücü ↔ uygulama entegrasyonu, dokümantasyon ve saha test desteği.

- **FPGA & Görüntü İşleme — Staj & R&D** · *2024–2025*  
  - **Spartan-7 SP701 + ADV7511**: MIPI giriş → PL’de temel işleme → HDMI çıkış pipeline denemeleri.  
  - **ZUBoard 1CG**: Tiny-YOLO tabanlı nesne algılama PoC; düşük gecikme optimizasyonları (GStreamer + appsink).  
  - **Yocto/Buildroot** imajları, kernel konfigürasyonu, DTS/overlay düzenleme, kullanıcı-uzayı arayüzleri.

---

## Seçili Projeler
- **Low-Latency Video Pipeline (FPGA + Linux)**  
  PL tarafında minimal görüntü işleme; PS tarafında GStreamer ile encode/display; buffer yönetimi ve **<10–20 ms** hedef gecikme için profil/optimizasyon.
- **UIO ile IP Kontrolü (Userspace I/O)**  
  Vivado IP’lerinin Linux userspace’ten register erişimi; basit CLI aracı ve Python wrapper.
- **Yocto + GStreamer + OpenCV Entegrasyonu**  
  Özel katman, paket tarifleri, appsink ile frame yakalama ve C++/Python demo uygulamaları.
- **Test & Araç Scriptleri**  
  Python/Batch ile otomasyon; log toplama, ölçüm raporu oluşturma, donanım-in-the-loop yardımcıları.

---

## Teknik Beceriler
**Diller:** C, C++, Python, Bash  
**FPGA/EDA:** Vivado/Vitis, HLS (temel), Verilog/VHDL (temel-orta)  
**Linux (Embedded):** Yocto, Buildroot, Device-Tree, U-Boot, Kernel modülleri, systemd  
**Multimedya:** GStreamer (appsink/appsrc), v4l2, OpenCV  
**Araçlar:** Git, CMake, JIRA, Docker/Podman, VS Code, Markdown  
**Alanlar:** Düşük gecikmeli video, DMA & bellek eşlemesi, sürücü-kullanıcı uzayı köprüleri, ASPICE pratikleri

---

## Eğitim & Sertifikalar (özet)
- **Embedded Linux / Yocto** – Udemy (2023)  
- **C Programlama** – C ve Sistem Programcıları Derneği (çeşitli dönemler)  
- **Python** – C ve Sistem Programcıları Derneği (2024)  
- **FreeRTOS / RTOS**, **Vivado Timing & VHDL** – Çeşitli eğitimler  
> Sertifika/detaylar CV’de.

---

## Topluluk & İlgi Alanları
FPGA tabanlı görüntü işleme, endüstriyel Linux sistemleri, gerçek zamanlılık ve **HW-SW co-design**. Boş zamanlarda maker projeleri, Raspberry Pi ve açık kaynak.

---

## Dillerr
Türkçe (ana dil), İngilizce (ileri), Almanca (A2–B1, sınav hazırlık)

---

## İletişim
- LinkedIn: [linkedin.com/in/eneskasoglu](https://www.linkedin.com/in/eneskasoglu)  
- GitHub: [github.com/eneskasoglu](https://github.com/eneskasoglu)  
- E-posta: enes@example.com
