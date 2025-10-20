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

🚀 Uso básico

python3 geo-recon.py -t 8.8.8.8

El comando anterior obtiene información pública sobre la IP:

    País y ciudad aproximados.

    ISP (proveedor de Internet).

    Coordenadas aproximadas.

    Posibles puertos abiertos (si la IP pertenece a un host público).

🔎 ¿Qué puede hacer geo-recon?

    Consultar APIs públicas de geolocalización.

    Agregar datos de múltiples fuentes.

    Mostrar información útil en auditorías o análisis defensivos.

    Comprender qué exposición puede tener una IP pública.

🧠 Ejemplo educativo (laboratorio propio)

Al ejecutar geo-recon sobre mi IP controlada, obtuve:

    ISP local.

    Ciudad aproximada (difusa, no exacta).

    Sin puertos abiertos, ya que mi router bloquea el acceso externo.

⚖️ Uso ético y legal

Estas técnicas deben emplearse solo:

    En sistemas propios o de laboratorio.

    Con consentimiento explícito.

    Para mejorar la seguridad y privacidad, no para invadir la de otros.

### 📸 Capturas (Sección 3 — Técnicas OSINT)

<!-- Imágenes: 9..11 -->
![GeoRecon puertos abiertos](<./capturas/9, con la opcion -n de geo recon=p.abiertos.png>)  
*Figura: 9 — Resultado de geo-recon con opción -n (puertos abiertos).*

![Datos sacados con GeoRecon](<./capturas/10, datos sacados con geo recon.png>)  
*Figura: 10 — Datos públicos recogidos por geo-recon (IP anonimizada).*

![IP del Tor](<./capturas/11, ip del thor.png>)  
*Figura: 11 — IP mostrada por geo-recon cuando se usa Tor (IP del nodo).*

---

## 📸 Capturas del laboratorio — Sección 3

Las siguientes capturas muestran ejemplos prácticos del uso de **geo-recon** en el laboratorio, aplicadas sobre mi propia IP (ocultada).

![9 - GeoRecon opción -n](<./capturas/9, con la opcion -n de geo recon=p.abiertos.png>)  
*Figura 9 — Ejecución de geo-recon con opción `-n` para mostrar puertos abiertos.*

![10 - Datos sacados con GeoRecon](<./capturas/10, datos sacados con geo recon.png>)  
*Figura 10 — Resultados de geolocalización y datos públicos de la IP.*

![11 - IP del Tor](<./capturas/11, ip del thor.png>)  
*Figura 11 — IP mostrada por geo-recon al analizar la IP de salida de Tor.*
