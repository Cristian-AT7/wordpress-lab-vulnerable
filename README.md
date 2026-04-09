# Wordpress-Lab-Vulnerable

# WordPress Vulnerable Lab (Docker)

## 🎯 Objetivo
Realizar una evaluación de seguridad sobre una instancia vulnerable de WordPress desplegada en un entorno controlado, con el fin de identificar y explotar vulnerabilidades conocidas.

## 🧱 Entorno
- Aplicación vulnerable obtenida desde Dockerlabs.es
- Despliegue mediante Docker
- Sistema atacante: Kali Linux
- Red local aislada

## ⚠️ Disclaimer
Este laboratorio fue realizado en un entorno controlado y autorizado con fines estrictamente educativos.

## 🚀 Despliegue del laboratorio
1. Descarga del entorno vulnerable desde Dockerlabs

## 🛠️ Herramientas utilizadas
- Nmap (reconocimiento de red)
- WPScan (enumeración de WordPress)
- Netcat (Hailitar puerto para escucha)
- Exploit público basado en CVE
- Reverse shell (payload web)

## 🔍 Reconocimiento
- Escaneo de puertos con Nmap para identificar servicios activos
- Identificación de WordPress como CMS en ejecución
- Enumeración de usuarios y plugins con WPScan

## 📌 Análisis de vulnerabilidades
- Identificación de plugin vulnerable: Pie Register
- Búsqueda de vulnerabilidad asociada mediante CVE
- Confirmación de que la versión instalada es vulnerable

## 🚪 Explotación
- Uso de exploit público dirigido a la vulnerabilidad de Pie Register
- Manipulación de cookies para suplantación de sesión administrativa
- Acceso no autorizado al panel de administración de WordPress

## 🧑‍💻 Post-explotación
- Carga de reverse shell en el servidor
- Establecimiento de conexión remota usando Netcat
- Obtención de acceso al sistema desde la máquina atacante

## 🛡️ Mitigación
- Actualización del plugin vulnerable a su última versión
- Eliminación de plugins no confiables
- Implementación de controles de autenticación seguros
- Uso de firewall de aplicaciones web (WAF)

## 📸 Evidencias
