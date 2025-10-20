# 2️⃣ 🌍 Cómo obtienen tu IP

> Laboratorio educativo en entorno controlado: se usa mi propia IP, correctamente ocultada en las capturas.  
> Objetivo: entender cómo se filtra una IP al visitar ciertos enlaces.

---

## 🧪 Demostración con IPLogger (uso ético)

IPLogger permite crear enlaces que registran la IP del visitante antes de redirigir a una página legítima.

---

## 📸 Capturas del laboratorio (Sección 2)

<p align="center">
  <img src="./capturas_visible/1_IPLOGGER.png" alt="1 - IPLOGGER" width="780"/><br>
  <em>Figura 1 — Página principal de IPLogger usada en el laboratorio (IP ocultada).</em>
</p>

<p align="center">
  <img src="./capturas_visible/2_url_iplogger.png" alt="2 - URL IPLogger" width="780"/><br>
  <em>Figura 2 — URL generada por IPLogger que redirige a YouTube.</em>
</p>

<p align="center">
  <img src="./capturas_visible/3_ytb_de_url.png" alt="3 - Redirección YouTube" width="780"/><br>
  <em>Figura 3 — Comprobación de la redirección legítima a YouTube.</em>
</p>

<p align="center">
  <img src="./capturas_visible/4_saco_mi_ip.png" alt="4 - Obtención de IP" width="780"/><br>
  <em>Figura 4 — Resultado: IP registrada por IPLogger (oculta).</em>
</p>

<p align="center">
  <img src="./capturas_visible/5_nav_thor.png" alt="5 - Navegador Tor" width="780"/><br>
  <em>Figura 5 — Uso del navegador Tor para acceder al mismo enlace.</em>
</p>

<p align="center">
  <img src="./capturas_visible/6_tmb_me_redirige_a_ytb.png" alt="6 - Redirección Tor" width="780"/><br>
  <em>Figura 6 — Redirección a YouTube desde Tor (sin exponer IP real).</em>
</p>

<p align="center">
  <img src="./capturas_visible/7_enruta_mi_ip_y_me_pone_otra.png" alt="7 - IP distinta" width="780"/><br>
  <em>Figura 7 — IP registrada distinta (nodo de salida diferente).</em>
</p>

<p align="center">
  <img src="./capturas_visible/8_lo_vuelvo_a_hacer_y_me_da_otra_ip.png" alt="8 - Otra IP" width="780"/><br>
  <em>Figura 8 — Segunda ejecución: otra IP de salida de Tor.</em>
</p>

---

⚠️ **Advertencia ética:**  
Nunca uses IPLogger o técnicas similares para obtener información de terceros. Este ejemplo solo se realiza en un entorno cerrado con fines educativos.

---
## 📸 Capturas del laboratorio — Sección 2
A continuación se muestran las capturas (ficheros tal cual en `capturas/`).

<p align="center">
  <img src="./capturas/-" alt="1 - IPLogger" />
  <br>
  <em>Figura 1 — 1 - IPLogger</em>
</p>

<p align="center">
  <img src="./capturas/-" alt="2 - URL IPLogger" />
  <br>
  <em>Figura 2 — 2 - URL IPLogger</em>
</p>

<p align="center">
  <img src="./capturas/-" alt="3 - Redirección YouTube" />
  <br>
  <em>Figura 3 — 3 - Redirección YouTube</em>
</p>

<p align="center">
  <img src="./capturas/-" alt="4 - Obtención de IP" />
  <br>
  <em>Figura 4 — 4 - Obtención de IP</em>
</p>

<p align="center">
  <img src="./capturas/-" alt="5 - Navegador Tor" />
  <br>
  <em>Figura 5 — 5 - Navegador Tor</em>
</p>

<p align="center">
  <img src="./capturas/-" alt="6 - Redirección Tor" />
  <br>
  <em>Figura 6 — 6 - Redirección Tor</em>
</p>

<p align="center">
  <img src="./capturas/-" alt="7 - IP distinta (nodo Tor)" />
  <br>
  <em>Figura 7 — 7 - IP distinta (nodo Tor)</em>
</p>

<p align="center">
  <img src="./capturas/-" alt="8 - Otra IP distinta (nodo Tor)" />
  <br>
  <em>Figura 8 — 8 - Otra IP distinta (nodo Tor)</em>
</p>
