# LA IMPORTANCIA DE TU PRIVACIDAD

> Repositorio educativo sobre la importancia de proteger tu privacidad en Internet, explicando riesgos de exposición de IP y buenas prácticas para navegar de forma segura usando herramientas como Tor Browser.

---

## Resumen
La privacidad en Internet es fundamental: cada vez que nos conectamos dejamos rastros que pueden ser recopilados por terceros. Este repositorio explica cómo proteger tus datos, la importancia de tu IP y cómo herramientas como Tor Browser ayudan a mantener el anonimato.

---

## Índice
1. [Importancia de la privacidad](#importancia-de-la-privacidad)  
2. [El peligro de exponer tu IP](#el-peligro-de-exponer-tu-ip)  
3. [Cómo protegerte: Tor, VPNs y buenas prácticas](#cómo-protegerte-tor-vpns-y-buenas-prácticas)  
4. [Demo segura y ética](#demo-segura-y-ética)  
5. [Instalación de Tor Browser](#instalación-de-tor-browser)  
6. [Cómo interpretar los resultados y actuar responsablemente](#cómo-interpretar-los-resultados-y-actuar-responsablemente)  
7. [Aviso legal y ética](#aviso-legal-y-ética)

---

## Importancia de la privacidad
Proteger la privacidad protege tu libertad y seguridad digital. Exponer datos como tu IP puede permitir inferencias sobre tu ubicación y hábitos, por lo que es clave entender los riesgos y proteger tu información.

---

## El peligro de exponer tu IP
Una IP pública puede permitir:
- Aproximación geográfica.  
- Correlación de actividad en combinación con otros datos.  
- Riesgos de seguridad si se combinan vulnerabilidades en servicios expuestos.

**Nota:** este repositorio solo muestra conceptos educativos. No contiene instrucciones para recolectar datos de terceros.

---

## Cómo protegerte: Tor, VPNs y buenas prácticas
- **Tor Browser:** enruta tu tráfico por nodos cifrados y oculta tu IP.  
- **VPN confiable:** reemplaza tu IP y cifra tu conexión.  
- **HTTPS siempre**, bloquear rastreadores, desactivar WebRTC innecesario.  
- **Educación y consentimiento:** solo realizar pruebas en entornos controlados.

---

## Demo segura y ética
Se puede incluir una demo local que muestre qué información recibe un servidor al hacer peticiones (IP local, cabeceras, user-agent). **Usar únicamente en localhost o con consentimiento explícito.**

---

## Instalación de Tor Browser

### Linux/Ubuntu
\`\`\`bash
sudo apt update
sudo apt install torbrowser-launcher -y
torbrowser-launcher
\`\`\`

### Windows
1. Ir a https://www.torproject.org/download/  
2. Descargar Tor Browser para Windows  
3. Ejecutar el instalador y seguir las instrucciones  

### macOS
1. Ir a https://www.torproject.org/download/  
2. Descargar Tor Browser para macOS  
3. Abrir el archivo `.dmg` y arrastrar a Aplicaciones  

### Android
1. Instalar Tor Browser o Orbot desde Google Play  

### iOS
1. Instalar Tor Browser oficial desde App Store  

**Nota:** Tor enruta tu tráfico por nodos cifrados; el servidor ve la IP del nodo de salida, no la tuya. Limitaciones: no garantiza anonimato absoluto, evita plugins, descargas externas y fugas WebRTC.

---

## Cómo interpretar los resultados y actuar responsablemente
- Navegador normal: servidor ve tu IP real.  
- Tor Browser: servidor ve la IP del nodo de salida.  
- Actúa responsablemente y protege tu información; nunca uses estos conocimientos para perjudicar a otros.

---

## Aviso legal y ética
Este repositorio es **educativo**. No fomenta la recolección de datos de terceros sin consentimiento. Respeta siempre la privacidad y las leyes.
