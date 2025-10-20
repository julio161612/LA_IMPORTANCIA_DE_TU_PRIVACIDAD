# 3️⃣ 🧩 Técnicas OSINT — Ejemplo con geo-recon

> OSINT (Open Source INTelligence) es la recopilación de información pública disponible en Internet.  
> Aquí se muestra cómo usar la herramienta **geo-recon** para analizar una IP propia y entender su potencial.

---

## 🛠️ Instalación de geo-recon

```bash
sudo apt update
sudo apt install -y git python3 python3-pip
git clone https://github.com/thewhiteh4t/geo-recon.git
cd geo-recon
pip install -r requirements.txt

📸 Capturas del laboratorio (Sección 3)
<p align="center"> <img src="./capturas_visible/9_geo_recon_n_p_abiertos.png" alt="9 - geo-recon -n" width="780"/><br> <em>Figura 9 — Ejecución de geo-recon con opción -n (puertos abiertos).</em> </p> <p align="center"> <img src="./capturas_visible/10_datos_geo_recon.png" alt="10 - datos geo-recon" width="780"/><br> <em>Figura 10 — Datos públicos recogidos por geo-recon (IP anonimizada).</em> </p> <p align="center"> <img src="./capturas_visible/11_ip_del_tor.png" alt="11 - IP del Tor" width="780"/><br> <em>Figura 11 — IP mostrada por geo-recon al analizar la IP de salida de Tor.</em> </p>
⚖️ Uso ético y legal

Estas técnicas deben emplearse solo en entornos propios o con permiso explícito; su finalidad es educativa.

---
## 📸 Capturas del laboratorio — Sección 3
A continuación se muestran las capturas (ficheros tal cual en `capturas/`).

<p align="center">
  <img src="./capturas/-" alt="9 - geo-recon -n (puertos abiertos)" />
  <br>
  <em>Figura 9 — 9 - geo-recon -n (puertos abiertos)</em>
</p>

<p align="center">
  <img src="./capturas/-" alt="10 - Datos extraídos con geo-recon" />
  <br>
  <em>Figura 10 — 10 - Datos extraídos con geo-recon</em>
</p>

<p align="center">
  <img src="./capturas/-" alt="11 - IP del nodo Tor" />
  <br>
  <em>Figura 11 — 11 - IP del nodo Tor</em>
</p>
## 📸 Capturas del laboratorio — Sección 3
<p align="center"><img src="./capturas/9%2C%20con%20la%20opcion%20-n%20de%20geo%20recon%3Dp.abiertos.png" alt="9 - geo-recon -n (puertos abiertos)" /><br><em>Figura 9 — 9 - geo-recon -n (puertos abiertos)</em></p>
<p align="center"><img src="./capturas/10%2C%20datos%20sacados%20con%20geo%20recon.png" alt="10 - Datos extraídos con geo-recon" /><br><em>Figura 10 — 10 - Datos extraídos con geo-recon</em></p>
<p align="center"><img src="./capturas/11%2C%20ip%20del%20thor.png" alt="11 - IP del nodo Tor" /><br><em>Figura 11 — 11 - IP del nodo Tor</em></p>
