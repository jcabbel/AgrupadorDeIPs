# 🌐 Agrupador de IPs

Pequeña herramienta web para analizar y agrupar direcciones IP por subredes `/24`.

## 🚀 Funcionalidad

* Permite pegar una lista de direcciones IP o cargar un archivo `.txt`
* Valida automáticamente las IPs
* Separa IPs **públicas** y **privadas**
* Agrupa IPs en subredes `/24` cuando hay **5 o más direcciones en la misma subred**
* Muestra:

  * Subredes agrupadas
  * IPs individuales no agrupadas
* Permite descargar el resultado como archivo `.txt`

## 🖥️ Uso

1. Abre el archivo `index.html` en tu navegador
2. Pega las IPs o carga un archivo `.txt`
3. Haz clic en **"Agrupar"**
4. Visualiza o descarga el resultado

## 📂 Formato de entrada

Una IP por línea:

```
192.168.1.1
192.168.1.2
8.8.8.8
```

## ⚙️ Tecnologías

* HTML
* JavaScript (Vanilla)
* TailwindCSS (CDN)

## 📌 Notas

* No requiere instalación ni servidor
* Funciona completamente en el navegador

## 📄 Licencia

Libre para uso personal y profesional
