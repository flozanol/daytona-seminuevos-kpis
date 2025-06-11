# 🚀 INSTRUCCIONES PARA PUBLICAR EN GITHUB PAGES

## 📁 ARCHIVOS CREADOS

He preparado todos los archivos necesarios para tu dashboard:

1. **`index.html`** - Página principal con todo el código
2. **`package.json`** - Configuración del proyecto  
3. **`README.md`** - Documentación del proyecto

## 🔧 PASOS PARA PUBLICAR

### **PASO 1: Crear el repositorio**
1. Ve a [GitHub.com](https://github.com)
2. Inicia sesión con tu cuenta
3. Clic en el botón **"New"** (verde) o **"+"** arriba a la derecha
4. Selecciona **"New repository"**

### **PASO 2: Configurar el repositorio**
1. **Repository name**: `daytona-seminuevos-kpis`
2. **Description**: `Dashboard de KPIs para Seminuevos - Grupo Daytona`
3. ✅ Marcar **"Public"** (debe ser público para GitHub Pages gratuito)
4. ✅ Marcar **"Add a README file"**
5. Clic en **"Create repository"**

### **PASO 3: Subir los archivos**
1. En tu nuevo repositorio, clic en **"uploading an existing file"**
2. Arrastra y suelta los 3 archivos que creé:
   - `index.html`
   - `package.json`  
   - `README.md`
3. En "Commit changes":
   - **Título**: `Agregar dashboard de KPIs Daytona`
   - **Descripción**: `Dashboard inicial con conexión a Google Sheets`
4. Clic en **"Commit changes"**

### **PASO 4: Activar GitHub Pages**
1. En tu repositorio, ve a **"Settings"** (pestaña arriba)
2. Scroll hacia abajo hasta encontrar **"Pages"** (menú izquierdo)
3. En **"Source"**, selecciona **"Deploy from a branch"**
4. En **"Branch"**, selecciona **"main"**
5. Deja **"/ (root)"** seleccionado
6. Clic en **"Save"**

### **PASO 5: ¡Listo!**
En 1-2 minutos tu dashboard estará disponible en:

**`https://TU_USUARIO_GITHUB.github.io/daytona-seminuevos-kpis`**

GitHub te mostrará la URL exacta en la sección Pages.

## 🎯 CONFIGURACIÓN DE GOOGLE SHEETS

Para que funcione con tu Google Sheets:

### **PASO 1: Hacer público tu Google Sheets**
1. Abre tu Google Sheets con los datos de KPIs
2. Clic en **"Compartir"** (botón azul arriba a la derecha)
3. Cambiar de "Restringido" a **"Cualquier persona con el enlace"**
4. Permisos: **"Visor"** (solo lectura)
5. Clic en **"Copiar enlace"**

### **PASO 2: Estructura requerida**
Cada hoja debe llamarse exactamente:
- `GWM Iztapalapa`
- `GWM Morelos`
- `Honda Cuajimalpa`
- `Honda Interlomas`
- `KIA Interlomas`
- `KIA Iztapalapa`
- `MG Cuajimalpa`
- `MG Interlomas`
- `MG Iztapalapa`

### **PASO 3: Formato de datos**
```
| KPI              | Enero | Febrero | Marzo |
|------------------|-------|---------|-------|
| Ventas Totales   | 150   | 180     | 200   |
| Leads Generados  | 45    | 52      | 48    |
| Conversión %     | 12.5  | 15.2    | 14.8  |
```

## ✅ VERIFICACIÓN

Una vez publicado:

1. **Abre tu dashboard** en la URL de GitHub Pages
2. **Pega la URL de tu Google Sheets** en el campo verde
3. **Clic en "Conectar Google Sheets"**
4. **¡Deberías ver tus datos cargados!**

## 🔄 ACTUALIZACIONES FUTURAS

Para actualizar el dashboard:
1. Ve a tu repositorio en GitHub
2. Clic en el archivo que quieres editar
3. Clic en el ícono de lápiz ✏️ (Edit)
4. Haz los cambios
5. Scroll abajo y clic en "Commit changes"
6. Los cambios se publican automáticamente en 1-2 minutos

## 🆘 PROBLEMAS COMUNES

### ❌ "Error de conexión"
- Verifica que Google Sheets sea público
- Revisa que las hojas tengan nombres exactos de agencias

### ❌ "No se encontraron KPIs"
- Primera fila debe tener encabezados
- Debe existir columna "KPI" o "Indicador"
- Debe haber columnas con nombres de meses

### ❌ "Página no carga"
- Espera 2-3 minutos después de activar GitHub Pages
- Verifica que el repositorio sea público
- Revisa que `index.html` esté en la raíz del repositorio

## 📞 URL FINAL

Tu dashboard estará en:
**`https://TU_USUARIO.github.io/daytona-seminuevos-kpis`**

**¡Comparte esta URL con tu equipo y tendrán acceso 24/7 al dashboard!** 🎉