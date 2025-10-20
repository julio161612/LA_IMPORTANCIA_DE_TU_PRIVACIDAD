# 2️⃣ 🌍 Cómo obtienen tu IP

Laboratorio educativo en entorno controlado: se usa mi propia IP, correctamente ocultada en las capturas.  
Objetivo: entender cómo se filtra una IP al visitar ciertos enlaces.

## 🧪 Demostración con IPLogger (uso ético)

IPLogger (y servicios similares) permiten crear enlaces que registran la IP del visitante antes de redirigir a una página legítima. A continuación se explica de forma didáctica y se muestran capturas realizadas en un entorno controlado.

### Ejemplo resumen
1. Se crea un enlace en IPLogger que redirige a `https://www.youtube.com`.  
2. Cuando se hace clic desde un navegador convencional (Chrome/Firefox), IPLogger registra la IP pública del usuario.  
3. Si se hace clic desde Tor Browser, IPLogger registra la IP del **nodo de salida** de Tor (no la IP real del usuario).

---

## 📸 Capturas del laboratorio — Sección 2

![Figura 1](./capturas/1_IPLOGGER.png)
![Figura 2](./capturas/2_url_iplogger.png)
![Figura 3](./capturas/3_ytb_de_url.png)
![Figura 4](./capturas/4_saco_mi_ip.png)
![Figura 5](./capturas/5_nav_thor.png)
![Figura 6](./capturas/6_tmb_me_redirige_a_ytb.png)
![Figura 7](./capturas/7_enruta_mi_ip_y_me_pone_otra.png)
![Figura 8](./capturas/8_lo_vuelvo_a_hacer_y_me_da_otra_ip.png)

---

⚠️ **Advertencia ética:**  
Nunca uses IPLogger ni técnicas similares para obtener información de terceros sin su consentimiento. Este material se realiza exclusivamente con fines educativos y de concienciación en un entorno controlado.
