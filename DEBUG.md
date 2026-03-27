# 🔧 Guía de Debugging - Presentación Herimarc

## 📋 Pasos para revisar el problema

### 1. Abre `index.html` en tu navegador
```
Navega a: C:\Users\luzPo\OneDrive\Desktop\pressherimarc\index.html
```

### 2. Abre la Consola del Navegador
- **En Chrome/Edge**: Presiona `F12` → Tab "Console"
- **En Firefox**: Presiona `F12` → Tab "Console"

### 3. Revisa los mensajes en la consola
Deberías ver algo como:
```
✅ Script iniciado
readyState: interactive (o complete)
Slides encontrados: 13
✅ Inicializando con 13 slides
✅ Slide 0 activado
Contador actualizado: 1 / 13
```

### 4. Prueba el navegación
- **Prueba 1**: Haz clic en el botón siguiente (→)
  - En consola debería ver: `changeSlide llamado con direction = 1`
  - El slide debería cambiar
  
- **Prueba 2**: Presiona la flecha derecha del teclado
  - En consola debería ver: `Tecla presionada: ArrowRight`
  - El slide debería cambiar
  
- **Prueba 3**: Usa el scroll del mouse hacia abajo
  - El slide debería cambiar

### 5. Si ves en consola: "❌ No se encontraron slides!"
- Significa que el HTML no se está cargando correctamente
- Revisa que todas las etiquetas HTML estén cerradas

### 6. Si ves en consola errores de sintaxis JavaScript
- Copia el error completo y cuéntame

## ✅ Que debería funcionar ahora

- ✅ Las páginas deben ser visibles (sin imágenes por ahora)
- ✅ Los botones prev/next funcionan
- ✅ Las flechas del teclado funcionan
- ✅ El scroll del mouse funciona
- ✅ El contador se actualiza

## 📤 Cuéntame exactamente:

1. ¿Ves contenido en la página? (Di qué)
2. ¿Qué error muestra en la consola? (Haz screenshot o copia el error)
3. ¿Funciona alguno de: botones, flechas o scroll?
4. ¿Qué dice el contador de slides?

---

**Archivo de prueba alternativo**: También creé `test.html` que puedes probar para verificar que la navegación funciona en general.
