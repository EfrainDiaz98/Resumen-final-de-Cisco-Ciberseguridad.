# Resumen de Lectura: Módulos 7 al 10
**Estudiante:** EFRAIN

---

## ☁️ MÓDULO 7: Computación en la Nube

### 1. Contexto General
Las organizaciones migran a la nube o modelos híbridos, enfrentando retos como el robo o manipulación de datos. Se utilizan estándares como los del **NIST** para proteger la información.

### 2. Beneficios y Características
* **Almacenamiento distribuido** y escalabilidad.
* Acceso bajo demanda y desde cualquier lugar.
* Administración automatizada y recursos compartidos.

### 3. Tipos de Nube
* **Pública:** Para todo el público.
* **Privada:** Exclusiva para una organización.
* **Comunitaria:** Intereses comunes entre organizaciones.
* **Híbrida:** Combinación de las anteriores.

### 4. Modelos de Servicio
| Modelo | Descripción |
| :--- | :--- |
| **IaaS** | Infraestructura (servidores, redes). |
| **PaaS** | Plataforma para desarrollo (sin gestionar infraestructura). |
| **SaaS** | Aplicaciones listas para usar (software como servicio). |

### 5. Amenazas y Ataques
* **Recolección de credenciales:** Phishing y sitios falsos.
* **Escalamiento de privilegios:** Obtener más permisos de los debidos.
* **Secuestro de cuentas:** Acceso no autorizado para manipular datos.
* **Malware e Inyección:** Inserción de código malicioso.
* **Canal lateral:** Análisis del comportamiento físico del sistema.

---

## 🛠️ MÓDULO 8: Persistencia y Control

La **Persistencia** permite al atacante mantener el acceso continuo mediante puertas traseras (*backdoors*), nuevos usuarios o tareas programadas.

### Canales de Comunicación (Shells)
* **Shell de enlace (Bind Shell):** Abre un puerto en la víctima para recibir la conexión.
* **Shell inverso (Reverse Shell):** La víctima se conecta al atacante (evita firewalls).

### Sistemas C2 (Comando y Control)
Infraestructura que permite enviar instrucciones remotas a sistemas comprometidos usando servidores externos.

---

## 📄 MÓDULO 9: Informes y Gestión

### 1. Estructura del Informe
Un informe de *pentesting* debe ser útil para el cliente, equilibrando lo técnico con lo ejecutivo. Debe incluir:
* Alcance, metodología y hallazgos.
* Análisis de causa raíz.
* Evidencias sólidas.

### 2. Gestión de Controles
Las recomendaciones se dividen en:
1.  **Técnicos:** Soluciones tecnológicas.
2.  **Administrativos:** Normas y políticas.
3.  **Operativos:** Ejecución diaria del personal.
4.  **Físicos:** Protección de instalaciones.

---

## 🧰 MÓDULO 10: Herramientas de Seguridad

1.  **Análisis de vulnerabilidades:** Escáneres automáticos (ej. Nessus, Nmap).
2.  **Ataques de credenciales:** Fuerza bruta y diccionarios (ej. John the Ripper).
3.  **Persistencia:** Herramientas para mantener el acceso.
4.  **Evasión:** Anonimato y cifrado para evitar antivirus/firewalls.
5.  **Marcos de explotación:** Entornos como Metasploit.
6.  **Análisis Forense:** Recuperación de evidencias post-incidente.
7.  **Esteganografía:** Ocultar información en imágenes o audios.
8.  **Herramientas Cloud:** Auditoría de infraestructuras en la nube.
