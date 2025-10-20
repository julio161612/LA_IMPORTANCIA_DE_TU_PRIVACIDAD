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
