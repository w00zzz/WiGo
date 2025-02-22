# **WiGo: The Next-Gen Wi-Fi Security Toolkit**

![WiGo Banner](https://via.placeholder.com/800x200?text=WiGo+Logo)  
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE) [![Go Version](https://img.shields.io/badge/go-%3E%3D1.20-blue)](https://golang.org/) [![Contributors](https://img.shields.io/badge/contributors-welcome-green)](CONTRIBUTING.md)

**WiGo** (Wi-Fi + Go) es una suite moderna y eficiente de herramientas de auditoría y análisis de redes inalámbricas, desarrollada en **Go (Golang)**. Inspirada en **Aircrack-ng**, esta suite combina rendimiento, simplicidad y potencia para ayudarte a explorar, analizar y proteger redes Wi-Fi.

## **Características principales**
- **Interfaz CLI interactiva**: Diseñada con **Bubble Tea**, ofrece una experiencia visual dinámica y colorida que guía al usuario paso a paso.
- **Herramientas modulares**: Cada herramienta está diseñada para realizar tareas específicas, desde escaneo de redes hasta cracking de contraseñas.
- **Escrito en Go**: Rápido, ligero y multiplataforma. Compatible con Linux, macOS y Windows.
- **Notificaciones en tiempo real**: Mantente informado sobre cada paso del proceso con mensajes claros y detallados.
- **Banners llamativos**: Un diseño profesional inspirado en herramientas de agencias de seguridad y hacking ético.

---

## **Herramientas incluidas**
### **Exploración y Monitoreo**
- **WiGo-Scan**: Escanea redes Wi-Fi disponibles mostrando SSID, BSSID, canales y cifrado.
- **WiGo-Dump**: Captura tráfico en tiempo real para análisis posterior.
- **WiGo-Sniff**: Analiza paquetes en tiempo real para identificar patrones y actividades sospechosas.

### **Ataques y Explotación**
- **WiGo-Replay**: Realiza ataques de repetición de paquetes para pruebas avanzadas.
- **WiGo-Jam**: Interfiere señales Wi-Fi mediante ataques de denegación de servicio (DoS).
- **WiGo-FakeAP**: Crea puntos de acceso falsos para simular entornos controlados.

### **Cracking y Descifrado**
- **WiGo-Crack**: Rompe claves WEP/WPA/WPA2 utilizando fuerza bruta o diccionarios.
- **WiGo-Decrypt**: Descifra paquetes capturados para análisis profundo.
- **WiGo-Brute**: Ejecuta ataques de fuerza bruta optimizados.

### **Análisis y Visualización**
- **WiGo-Analyze**: Extrae información detallada de archivos PCAP.
- **WiGo-Wardrive**: Mapea redes Wi-Fi mientras te mueves.
- **WiGo-Map**: Genera mapas visuales de redes detectadas.

---

## **Capturas de pantalla**
### **Interfaz principal**
![WiGo Interface](https://via.placeholder.com/600x400?text=WiGo+CLI+Interface)

### **Banner de inicio**
██████╗ ██╗   ██╗██╗███████╗██╗  ██╗
 ██╔══██╗██║   ██║██║██╔════╝██║ ██╔╝
 ██████╔╝██║   ██║██║███████╗█████╔╝ 
 ██╔══██╗██║   ██║██║╚════██║██╔═██╗ 
 ██║  ██║╚██████╔╝██║███████║██║  ██╗
 ╚═╝  ╚═╝ ╚═════╝ ╚═╝╚══════╝╚═╝  ╚═╝

 
---

## **Requisitos**
- **Sistema operativo**: Linux, macOS o Windows.
- **Hardware**: Adaptador Wi-Fi compatible con modo monitor (para ciertas herramientas).
- **Dependencias**: Instala Go (`>=1.20`) y las bibliotecas necesarias (detalladas en la documentación).

---

## **Instalación**
```bash
git clone https://github.com/tuusuario/wigo.git
cd wigo
go build -o wigo main.go
sudo ./wigo --help
```

## **Uso**

# Escanear redes Wi-Fi
```bash
sudo ./wigo scan
```

# Capturar tráfico
```bash
sudo ./wigo dump
```

# Romper claves WPA2
```bash
sudo ./wigo crack --file capture.pcap --wordlist passwords.txt
```

## **Contribuciones**
¡Las contribuciones son bienvenidas! Si deseas mejorar WiGo , reportar errores o agregar nuevas herramientas, consulta nuestra guía de contribución . Únete a nuestra comunidad y ayúdanos a hacer de WiGo  la mejor suite de auditoría de redes Wi-Fi.

## **Licencia**
Este proyecto está bajo la licencia MIT . Consulta el archivo LICENSE  para más detalles.

## **Agradecimientos**  

Inspirado en Aircrack-ng  y otras herramientas de seguridad Wi-Fi.
Gracias a la comunidad de Go por su apoyo y recursos.
     
