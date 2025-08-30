---
layout: page
title: "Enes Kaşoğlu"
---

{% if site.posts and site.posts.size > 0 %}
<div id="son_yazi_banner" style="
background: linear-gradient(to right, rgba(250, 191, 200, 0.3), rgba(23, 86, 169, 0.2));
color: rgb(52, 55, 67);
text-align: center;
padding: 14px 12px;
border-radius: 10px;
box-shadow: 3px 3px 10px rgba(0,0,0,0.06);
margin: 8px 0 18px;">
🚀 Son yazı:&nbsp;<a href="{{ site.baseurl }}{{ site.posts[0].url }}" style="font-weight: 700;">{{ site.posts[0].title }}</a>
</div>
{% endif %}

<img src="{{ site.baseurl }}/assets/img/me.png" alt="Enes Kaşoğlu" style="display:block;margin:0 auto 12px;max-width:180px;border-radius:12px;" />

<p class="text-align-center"><strong>Enes Kaşoğlu</strong></p>
<p class="text-align-center"><em>Embedded & FPGA Engineer</em></p>
<p class="text-align-center"><code>eneskasoglu</code></p>

<p class="text-align-center">
  <a href="https://www.linkedin.com/in/ENES" target="_blank">💼 LinkedIn</a>
  <a href="https://github.com/ENES" target="_blank">🖥️ GitHub</a>
  <a href="https://www.youtube.com/@ENES" target="_blank">🎬 YouTube</a>
  &nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="{{ site.baseurl }}/assets/cv/Enes-Kasoglu-CV.pdf">📄 CV</a>
</p>

---

## About me
Elektronik ve bilgisayara çocukluğumdan beri ilgi duyuyorum.  
**FPGA, gömülü Linux, RTOS ve sürücü geliştirme** üzerine çalışıyorum.  
Projelerimde çoğunlukla donanım bring-up’tan kullanıcı seviyesine kadar **uçtan uca geliştirme** yapıyorum.  
Özellikle **DevOps ve CI/CD** pratiklerini gömülü sistemlere uygulamak ilgimi çekiyor.  

Teknolojinin yanında müzikle ve enstrümanlarla da ilgileniyorum 🎵.

---

## Professional Experience
- **2025 – … · Embedded/FPGA Engineer** — (Şirket/Proje)  
  HDMI/MIPI görüntü hattı, düşük gecikmeli işleme, sürücü entegrasyonu
- **2022 – 2024 · Embedded SW Engineer** — (Şirket)  
  UART/SPI/I2C sürücüleri, test otomasyonu, CI/CD entegrasyonu

---

## Education
- **MSc & BSc · Electrical & Electronics Eng.**

---

## Selected Projects
- **FPGA HDMI Pipeline** — Spartan-7 + ADV7511  
- **Yocto-tabanlı Kamera Aygıtı** — GStreamer + OpenCV

---

## Skills
- **Languages:** C/C++, Python, Bash  
- **Platforms:** FPGA (Xilinx), Embedded Linux, RTOS  
- **Tools:** Vivado/Vitis, Yocto/Buildroot, Git, CI/CD

---

## Contact
E-posta: **enes@example.com**  
veya <a href="https://www.linkedin.com/in/ENES" target="_blank">LinkedIn</a> üzerinden ulaşabilirsin.

---

<div id="progressBar" style="position:fixed;top:0;left:0;height:3px;background:#1f6feb;width:0;z-index:9999;"></div>
<script>
  window.addEventListener('scroll', function(){
    var H=document.documentElement.scrollHeight - document.documentElement.clientHeight;
    var T=window.pageYOffset||document.documentElement.scrollTop;
    document.getElementById('progressBar').style.width=(T/H*100)+'%';
  });
</script>
