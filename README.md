curly-enigma
Formulario de Contacto Moderno

Un formulario de contacto elegante y moderno con animaciones fluidas y diseño glassmorphism.

✨ Características

- 🎨 Diseño moderno con efectos glassmorphism
- 📱 Totalmente responsive (móvil, tablet, desktop)
- ⚡ Animaciones suaves y transiciones elegantes
- 🎯 Validación de formulario en tiempo real
- ♿ Accesible y compatible con lectores de pantalla
- 🌈 Gradientes dinámicos y efectos visuales

🚀 Inicio Rápido

1. Clona o descarga el archivo HTML
2. Abre `index.html` en tu navegador
3. ¡Listo para usar!

## 📋 Campos del Formulario

- Nombre: Campo de texto requerido
- Apellido: Campo de texto requerido
- Email: Validación de formato email
- Mensaje: Área de texto para mensaje detallado

 🛠️ Tecnologías

- HTML5
- CSS3 (Animaciones, Grid, Flexbox, Gradientes)
- JavaScript Vanilla (Sin dependencias)

## 🎨 Personalización

Colores
Modifica los gradientes en las variables CSS:
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

Animaciones
Ajusta la duración de las animaciones:
```css
animation: fadeInUp 0.8s ease-out;
```

## 📝 Integración con Backend

Actualmente el formulario simula el envío. Para conectarlo a tu backend:
```javascript
form.addEventListener('submit', async function(e) {
    e.preventDefault();
    
    const formData = new FormData(form);
    
    try {
        const response = await fetch('/api/contact', {
            method: 'POST',
            body: formData
        });
        
        if (response.ok) {
            // Mostrar mensaje de éxito
        }
    } catch (error) {
        // Manejar error
    }
});
```

## 🔧 Próximas Mejoras

- [ ] Integración con API de envío de emails
- [ ] Validación avanzada de campos
- [ ] Modo oscuro
- [ ] Multi-idioma (i18n)
- [ ] Captcha anti-spam
- [ ] Guardar borradores automáticamente

## 📱 Compatibilidad

- ✅ Chrome (últimas 2 versiones)
- ✅ Firefox (últimas 2 versiones)
- ✅ Safari (últimas 2 versiones)
- ✅ Edge (últimas 2 versiones)
- ✅ Móviles iOS y Android

## 📄 Licencia

Libre para uso personal y comercial.

🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor:
1. Fork el proyecto
2. Crea una rama para tu feature
3. Commit tus cambios
4. Push a la rama
5. Abre un Pull Request

## 📧 Contacto

Para preguntas o sugerencias, abre un issue en el repositorio.

---

⭐ Si te gusta este proyecto, dale una estrella!
