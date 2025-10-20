# 2️⃣ 🌍 Cómo obtienen tu IP

> Laboratorio educativo en entorno controlado: se usa mi propia IP, correctamente ocultada en las capturas.  
> Objetivo: entender cómo se filtra una IP al visitar ciertos enlaces.

---

## 🧪 Demostración con IPLogger (uso ético)

### ¿Qué es IPLogger?
Es un servicio web que permite crear enlaces que registran la IP de quien hace clic, antes de redirigir a otra página legítima.

---

## 🧩 Ejemplo educativo paso a paso

1. Accedo a [https://iplogger.org](https://iplogger.org).  
2. Creo una URL que redirige a `https://www.youtube.com`.  
3. El sitio genera un enlace acortado, por ejemplo:

https://iplogger.org/XXXXXX
4. Si alguien (en mi laboratorio) hace clic desde un navegador normal:
- IPLogger registra la IP pública, país y navegador.
- Luego redirige automáticamente a YouTube.

---

## 🔍 Resultados de la prueba

### 🔸 Desde Firefox o Chrome
- IPLogger muestra mi IP pública real (la del proveedor de Internet).  
- Desde esta IP, se puede estimar mi ubicación aproximada con herramientas OSINT.

### 🔸 Desde Tor Browser
- IPLogger **no** ve mi IP real.  
- Solo aparece la IP del **nodo de salida** de la red Tor.  
- Esa IP pertenece a un país o región diferente, sin conexión con mi ubicación.

---

## 🧠 Conclusión

El navegador Tor o una VPN pueden **romper la relación directa entre IP y ubicación real**, protegiendo tu privacidad.

---

## 🛡️ Recomendaciones

- No hagas clic en enlaces acortados desconocidos.  
- Usa servicios de previsualización de URL.  
- Configura extensiones de bloqueo de scripts.  
- Utiliza Tor o VPN para separar tu identidad real del tráfico en línea.

---

⚠️ **Advertencia ética:**  
Nunca uses IPLogger o técnicas similares para obtener información de terceros.  
Este ejemplo solo se realiza en un entorno cerrado con fines de concienciación y defensa digital.

### 📸 Capturas (Sección 2 — Cómo obtienen tu IP)

A continuación se muestran las capturas demostrativas (todas anonimizadas en las imágenes del laboratorio):

<!-- Imágenes: 1..8 -->
![IPLOGGER](<./capturas/1,IPLOGGER.png>)  
*Figura: 1 — IPLogger: captura de la página que registra IPs (IP oculta).*

![URL IPLogger](<./capturas/2,url de iplogger.png>)  
*Figura: 2 — URL generada por IPLogger (acortador/registro).*

![YouTube redirige](<./capturas/3,ytb de url.png>)  
*Figura: 3 — Redirección a YouTube tras registro.*

![Saco mi IP](<./capturas/4,saco mi ip.png>)  
*Figura: 4 — Captura mostrando la IP registrada (IP modificada por privacidad).*

![Navegador Tor navegación](<./capturas/5, nav thor.png>)  
*Figura: 5 — Navegador Tor en uso (navegación por la red Tor).*

![Me redirige a YTB](<./capturas/6,tmb me redirige a ytb.png>)  
*Figura: 6 — Otra captura de la redirección a YouTube.*

![Enruta mi IP y pone otra](<./capturas/7, enruta mi ip y me pone otra.png>)  
*Figura: 7 — La IP registrada cambia (nodo intermedio).*

![Lo vuelvo a hacer y me da otra IP](<./capturas/8, lo vuelvo a hacer y me da otra ip.png>)  
*Figura: 8 — Segunda ejecución: IP distinta (nodo distinto).*

---

## 📸 Capturas del laboratorio — Sección 2

A continuación se muestran las capturas del proceso realizado en el laboratorio personal (todas las IPs han sido ocultadas o modificadas).

![1 - IPLogger principal](<./capturas/1,IPLOGGER.png>)  
*Figura 1 — Página principal de IPLogger usada en el laboratorio.*

![2 - URL generada por IPLogger](<./capturas/2,url de iplogger.png>)  
*Figura 2 — URL creada que redirige a YouTube tras registrar la IP.*

![3 - Redirección a YouTube](<./capturas/3,ytb de url.png>)  
*Figura 3 — Comprobación de la redirección legítima a YouTube.*

![4 - Obtención de IP](<./capturas/4,saco mi ip.png>)  
*Figura 4 — Resultado: IP registrada por IPLogger (oculta).*

![5 - Navegador Tor](<./capturas/5, nav thor.png>)  
*Figura 5 — Uso del navegador Tor para acceder al mismo enlace.*

![6 - Redirección Tor](<./capturas/6,tmb me redirige a ytb.png>)  
*Figura 6 — Redirección a YouTube, idéntica pero sin exponer la IP real.*

![7 - IP diferente con Tor](<./capturas/7, enruta mi ip y me pone otra.png>)  
*Figura 7 — IPLogger detecta otra IP (nodo de salida de Tor).*

![8 - Nueva IP diferente](<./capturas/8, lo vuelvo a hacer y me da otra ip.png>)  
*Figura 8 — Segundo intento: Tor usa otro nodo y por tanto otra IP.*
