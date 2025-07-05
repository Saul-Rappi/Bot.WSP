# WhatsApp Bot CRM Dashboard

Un dashboard interactivo para gestionar y monitorear las interacciones de un bot de WhatsApp con clientes.

## 🚀 Características

- **Panel de Control en Tiempo Real**
  - Visualización de estadísticas clave
  - Monitoreo de mensajes enviados y pendientes
  - Gráficos interactivos de distribución por ciudad y compañía

- **Gestión de Interacciones**
  - Seguimiento de chats pendientes
  - Sistema de comentarios y notas
  - Marcado de estados (Atendido, Reagendado, No concluido)
  - Historial completo de interacciones

- **Filtros Avanzados**
  - Filtrado por base de datos
  - Filtrado por compañía telefónica
  - Filtrado por ciudad

- **Control del Bot**
  - Activación/desactivación del bot
  - Confirmación de envíos masivos
  - Monitoreo de estado del bot

## 📋 Requisitos Previos

```bash
Python 3.8 o superior
Excel (para las bases de datos)
```

## 🛠️ Instalación

1. Clonar el repositorio:
```bash
git clone [url-del-repositorio]
cd [nombre-del-directorio]
```

2. Instalar dependencias:
```bash
pip install -r requirements.txt
```

3. Configurar el archivo Excel:
- Asegurarse de tener el archivo `base_bot.xlsx` con las pestañas:
  - BaseDeEnvio: Para los números a contactar
  - ChatEntrante: Para el registro de respuestas

## 🚀 Uso

1. Iniciar el servidor:
```bash
python app.py
```

2. Acceder al dashboard:
```
http://localhost:5000
```

## 📊 Estructura de Datos

### BaseDeEnvio
- Ciudad
- Número
- Compañía
- Estado

### ChatEntrante
- Fecha
- Número
- Respuesta
- Estado
- Comentarios

## 🔧 Configuración

El sistema permite personalizar:
- Filtros de visualización
- Estados de atención
- Tipos de respuesta
- Formato de comentarios

## 📱 Funcionalidades Principales

1. **Gestión de Leads**
   - Marcado de estados
   - Registro de comentarios
   - Seguimiento de interacciones

2. **Monitoreo**
   - Estadísticas en tiempo real
   - Gráficos de distribución
   - Contadores de interacción

3. **Control de Bot**
   - Inicio/Parada del servicio
   - Confirmación de envíos
   - Estado del servicio

## 🤝 Contribuir

Si deseas contribuir al proyecto:
1. Haz un Fork
2. Crea una rama para tu feature
3. Commit tus cambios
4. Push a la rama
5. Crea un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo LICENSE.md para detalles

## ✨ Agradecimientos

- Equipo de desarrollo
- Contribuidores
- Usuarios que proporcionan feedback 