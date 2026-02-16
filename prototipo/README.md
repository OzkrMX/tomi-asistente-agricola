# 📱 Prototipo de Tomi Dashboard

## Archivos

- **tomi-app.html** - Dashboard agrícola profesional con diseño moderno y responsive

## 🎨 Características del Dashboard

### Diseño y UX
- ✅ **Tailwind CSS** vía CDN para diseño moderno
- ✅ **Layout responsive** (mobile-first)
- ✅ **Paleta de colores agrícola**: verdes, tierra, cielo
- ✅ **Alto contraste** para uso en exteriores bajo el sol
- ✅ **Iconos SVG** integrados para cada sección
- ✅ **Tipografía legible** Inter (mínimo 16px)

### Componentes Implementados

#### Header/Navbar
- Logo de Tomi (texto estilizado con icono SVG)
- Título "Tomi - Asistente Agrícola"
- Menú hamburger responsive (móvil)
- Indicador de usuario/perfil

#### Sidebar (colapsable en móvil)
- 🏠 Dashboard
- 🌱 Cultivos
- 🌤️ Clima
- 💰 Conciliación
- 🚛 Flotilla
- 💬 Chat con IA
- ⚙️ Configuración

#### Dashboard Principal

**KPIs (4 tarjetas):**
- 🌱 Cultivos Activos: 12 activos
- 💧 Humedad Promedio: 68%
- 🚛 Vehículos en Operación: 8/10
- 💰 Balance Mensual: $45,250

**Widget de Clima:**
- Temperatura actual: 28°C
- Condiciones: Soleado
- Pronóstico 3 días
- Alerta climática

**Estado de Cultivos (tabla):**
- 4 cultivos de ejemplo (Maíz, Tomate, Zanahoria, Lechuga)
- Etapa, días restantes, estado de salud
- Indicadores de color (verde=bien, amarillo=atención)

**Resumen de Flotilla:**
- 6 vehículos con estados
- Próximo mantenimiento
- Estados: operativo, mantenimiento, inactivo

**Acceso rápido a Conciliación:**
- Botón "Ir al Conciliador"
- Resumen de transacciones (8 pendientes, 45 conciliadas)

**Chat Widget:**
- Botón flotante en esquina inferior derecha
- Mensaje de bienvenida al hacer clic

#### Footer
- Copyright 2026
- Enlaces a documentación
- Versión 0.1.0

### Interactividad (JavaScript vanilla)

- ✅ Menú hamburger funcional
- ✅ Sidebar colapsable con overlay
- ✅ Hover effects en tarjetas
- ✅ Chat widget con mensaje de demostración
- ✅ Datos mock para demostración

## 🚀 Cómo usar

### Método 1: Abrir directamente
Simplemente abre `tomi-app.html` en cualquier navegador moderno con conexión a internet.

### Método 2: Servidor local
```bash
cd prototipo
python3 -m http.server 8080
```
Luego visita: http://localhost:8080/tomi-app.html

## 📋 Requisitos

- Navegador moderno (Chrome, Firefox, Safari, Edge)
- Conexión a internet (para cargar Tailwind CSS y fuentes de Google)
- JavaScript habilitado

## 🎯 Principios UX para Agricultura

- **Botones grandes**: Fácil de usar con guantes (mínimo 48px)
- **Alto contraste**: Legible bajo el sol
- **Información crítica destacada**: KPIs visibles de inmediato
- **Navegación simple**: Máximo 2 clics para cualquier función
- **Carga rápida**: CDN optimizado para conexiones lentas

## 🎨 Colores Utilizados

| Color | Código | Uso |
|-------|--------|-----|
| Verde primario | `#10b981` | Cultivos, estado saludable |
| Verde secundario | `#22c55e` | Acciones positivas |
| Amarillo/Ámbar | `#f59e0b` | Alertas, atención requerida |
| Rojo | `#ef4444` | Crítico, urgente |
| Azul | `#3b82f6` | Clima, agua |
| Morado | `#9333ea` | Finanzas, conciliación |
| Gris | `#6b7280` | Texto secundario |

## 📝 Notas Técnicas

- El HTML usa **clases de Tailwind CSS** directamente
- Los iconos son **SVG inline** para mejor rendimiento
- El JavaScript es **vanilla** (sin frameworks)
- Los datos son **mock data** para demostración
- El diseño es **mobile-first** y completamente responsive

## 🔄 Próximos Pasos

- [ ] Conectar con backend real
- [ ] Integrar API de clima real
- [ ] Implementar autenticación
- [ ] Agregar más interacciones
- [ ] Optimizar para PWA (Progressive Web App)
