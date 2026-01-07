# 🌍 Odoo-Open — Repositorio de módulos y apps libres para Odoo

<div align="center">

[![Hits](https://hits.sh/github.com/EpOpenLabs/Odoo-Open.svg?style=flat-square&label=hits)](https://hits.sh/github.com/EpOpenLabs/Odoo-Open/)
[![GitHub issues](https://img.shields.io/github/issues/EpOpenLabs/Odoo-Open?style=flat-square)](https://github.com/EpOpenLabs/Odoo-Open/issues)
[![GitHub forks](https://img.shields.io/github/forks/EpOpenLabs/Odoo-Open?style=flat-square)](https://github.com/EpOpenLabs/Odoo-Open/network)
[![GitHub stars](https://img.shields.io/github/stars/EpOpenLabs/Odoo-Open?style=flat-square)](https://github.com/EpOpenLabs/Odoo-Open/stargazers)
[![License](https://img.shields.io/github/license/EpOpenLabs/Odoo-Open?style=flat-square)](LICENSE)
[![Buy Me A Coffee](https://img.shields.io/badge/☕%20Buy%20me%20a%20coffee-Support%20EpOpenLabs-5865F2?style=flat-square)](https://www.buymeacoffee.com/epolabs)

</div>

## 🚀 ¿Qué es **Odoo-Open**?

**Odoo-Open** es una colección abierta de **módulos, aplicaciones y personalizaciones** para **Odoo**, creadas y mantenidas por la comunidad de **EpOpenLabs**.  
Nuestro objetivo es construir herramientas libres, documentadas y reutilizables que potencien el ecosistema Odoo en proyectos empresariales, educativos y de investigación.

🧩 Incluye:
- Módulos personalizados para Odoo POS, Ventas, Inventario, entre otros.  
- Integraciones con plataformas externas (ej. VisualPay, APIs, ERP externos).  
- Ejemplos, guías y buenas prácticas de desarrollo Odoo.  

---

## 🛠️ Estructura del proyecto

```bash
Odoo-Open/
├── pos_visualpay/            # Módulo para pagos visuales en POS

```

> 📘 Cada módulo cuenta con su propio `README.md`, dependencias y licencias.

---

## 💡 Cómo empezar

1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/EpOpenLabs/Odoo-Open.git
   cd Odoo-Open
   ```

2. **Copiar tus módulos al directorio de addons**
   ```bash
   cp -r ./pos_visualpay /opt/odoo/custom_addons/
   ```

3. **Actualizar Odoo**
   ```bash
   sudo -u odoo odoo -d <nombre_bd> -u all --stop-after-init
   ```

---

## 🤝 Cómo contribuir

Nos encanta recibir contribuciones 💬  
Puedes participar de muchas formas:

- 🪄 **Reporta errores:** [Abrir un issue](https://github.com/EpOpenLabs/Odoo-Open/issues)
- 💡 **Propón nuevas ideas:** [Crear una discusión](https://github.com/EpOpenLabs/Odoo-Open/discussions)
- 🧰 **Envía un Pull Request:** Mejora el código o la documentación
- 🧑‍💻 **Únete al equipo:** participa en revisiones o pruebas

Antes de contribuir, revisa la guía 👉 [`CONTRIBUTING.md`](./CONTRIBUTING.md)

---

## 📬 Contacto y soporte

Si deseas colaborar o necesitas ayuda:

- ✉️ **Email:** lpachecoby@gmail.com  
- 💬 **Issues y soporte técnico:** [Abrir un issue](https://github.com/EpOpenLabs/Odoo-Open/issues)  
- 🧭 **Organización:** [EpOpenLabs en GitHub](https://github.com/EpOpenLabs)

---

## 🌱 Filosofía

> _“El código abierto no solo se comparte, se cultiva.”_  
Creemos en el software libre como una herramienta para **educar, innovar y conectar** comunidades técnicas en Latinoamérica y el mundo.

---

## 📄 Licencia

Este proyecto está licenciado bajo la GNU General Public License v3.0 (GPLv3) — publicada el 29 de junio de 2007 por la Free Software Foundation.

📚 Puedes:

Usar, modificar y distribuir este software libremente.

Hacer versiones derivadas, manteniendo la misma licencia GPLv3.

Acceder al texto completo de la licencia aquí 👉 [GNU GPL v3](/LICENSE)

---
## ☕ Apoya este proyecto

Si **Odoo-Open** te resulta útil y quieres apoyar el desarrollo de módulos libres para la comunidad Odoo, puedes invitarnos un café 💙  
Tu apoyo ayuda a mantener el proyecto activo, documentado y en constante mejora.

<div align="center">
  <a href="https://www.buymeacoffee.com/epolabs" target="_blank">
    <img src="https://cdn.buymeacoffee.com/buttons/v2/default-violet.png"
         alt="Apóyanos con un café"
         style="height: 55px;width: 200px;">
  </a>
</div>

<div align="center">

🧡 **Hecho con pasión por [EpOpenLabs](https://github.com/EpOpenLabs)**  
y la comunidad de desarrolladores de **Odoo Open Source**  

</div>
