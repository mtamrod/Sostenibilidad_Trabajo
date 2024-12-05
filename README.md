# Creación de una Página Web sobre la Agenda 20/30 en Raspberry Pi

## Objetivo General
Desarrollar una página web informativa sobre la Agenda 20/30, alojarla en una Raspberry Pi alimentada por energía solar y calcular el consumo energético del proyecto.

---

## Materiales Necesarios
- **Hardware:**
  - Raspberry Pi (cualquier modelo compatible, recomendado Raspberry Pi 4).
  - Tarjeta microSD con Raspberry Pi OS instalado.
  - Fuente de energía solar:
    - Panel solar.
    - Controlador de carga.
    - Batería de respaldo (para la noche).
  - Sensor de consumo eléctrico (opcional, como un medidor USB).
- **Software:**
  - Servidor web: Apache, Nginx o Python con Flask/Django.
  - Lenguajes: HTML, CSS, JavaScript (Dependiendo del consumo).
  - Librerías para cálculo de consumo (opcional): Python con bibliotecas como `psutil`.

---

## Pasos a Seguir

### 1. Configuración del Entorno
#### 1.1 Instalación de Raspberry Pi OS
- Descargar e instalar Raspberry Pi Imager.
- Configurar el sistema operativo en la tarjeta SD.
- Configurar red WiFi y SSH.

#### 1.2 Configuración del Sistema Solar
- Instalar y conectar los paneles solares al controlador de carga.
- Verificar el funcionamiento de la batería y la Raspberry Pi con energía solar.

---

### 2. Desarrollo de la Página Web
#### 2.1 Contenido de la Página Web
- Crear secciones básicas:
  - Introducción a la Agenda 20/30.
  - Objetivos de Desarrollo Sostenible (ODS).
  - Acciones locales e internacionales.
  - Recursos y enlaces útiles.

#### 2.2 Diseño y Desarrollo
- Utilizar HTML, CSS y JavaScript para el diseño responsivo.
- Implementar funcionalidades interactivas (como gráficos sobre los ODS).

#### 2.3 Implementación del Servidor Web
- Instalar Apache/Nginx o configurar un servidor simple con Flask o Django.
- Configurar el sitio web como servicio en la Raspberry Pi.

---

### 3. Medición del Consumo Energético
#### 3.1 Métodos de Medición
- Utilizar sensores o herramientas como medidores USB.
- Alternativamente, calcular el consumo teórico basado en:
  - Potencia del panel solar.
  - Consumo nominal de la Raspberry Pi.

#### 3.2 Registro y Análisis
- Registrar los datos de consumo durante un período de prueba (por ejemplo, 24 horas).
- Analizar la viabilidad energética del proyecto.

---

## Producto Final
- Página web funcional alojada en la Raspberry Pi.
- Informe sobre:
  - Diseño y funcionalidad del sistema.
  - Datos de consumo energético.
  - Conclusiones sobre sostenibilidad.

---

## Objetivos Extra
- Monitorear el sistema solar en diferentes condiciones climáticas.
- Optimizar el código y la configuración del servidor para reducir el consumo energético.
- Agregar un sistema de monitoreo en tiempo real para el consumo energético y la producción de energía.
