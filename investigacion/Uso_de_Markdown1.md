# 📌 Sistema de Registro de Usuarios  
**README.md – Documentación del Proyecto**

## 1. 📖 Descripción del caso  
Este proyecto consiste en un **Sistema de Registro de Usuarios** que permite a los usuarios registrarse, iniciar sesión y modificar su información personal. Su propósito es simular las funciones básicas de una aplicación real de gestión de cuentas.

## 2. 🎯 Objetivos del proyecto  
- Implementar un sistema funcional que registre y almacene usuarios.  
- Permitir iniciar sesión verificando credenciales.  
- Facilitar la edición del perfil del usuario.  
- Aplicar buenas prácticas de documentación y control de versiones (Git).  
- Realizar pruebas básicas para validar el correcto funcionamiento del sistema.

---

## 3. ✔️ Requerimientos del sistema

### **Requerimientos funcionales**
1. El sistema debe permitir registrar nuevos usuarios.  
2. Debe validar que el usuario no exista previamente.  
3. Debe permitir iniciar sesión con usuario y contraseña.  
4. El usuario debe poder modificar su perfil.  
5. El sistema debe mostrar mensajes de éxito o error.

### **Requerimientos no funcionales**
1. La interfaz debe ser clara y fácil de usar.  
2. El sistema debe almacenar los datos de forma segura.  
3. El código fuente debe ser mantenible y estar documentado.

---

## 4. 🧪 Tabla de pruebas (Testing)

| Nº | Caso de prueba | Entrada | Proceso | Resultado esperado |
|----|----------------|---------|---------|--------------------|
| 1 | Registro exitoso | Usuario nuevo | Guardar datos | Usuario registrado correctamente |
| 2 | Registro duplicado | Usuario existente | Verificar existencia | Mostrar error de duplicación |
| 3 | Inicio de sesión correcto | Usuario + contraseña válida | Validar credenciales | Acceso permitido |
| 4 | Inicio de sesión incorrecto | Contraseña incorrecta | Validar credenciales | Acceso denegado |
| 5 | Modificación de perfil | Datos actualizados | Guardar cambios | Perfil actualizado |

---

## 5. 🔧 Tipo de mantenimiento propuesto  

### **Mantenimiento perfectivo**
Mejoras futuras como:  
- Mejor interfaz,  
- Mayor seguridad,  
- Nuevas funciones para la gestión de usuarios.

### **Mantenimiento correctivo**
Corrección de errores encontrados durante las pruebas.

---

## 6. 🌀 Reflexión sobre el control de versiones  
El uso de Git y GitHub facilita llevar un registro ordenado de todos los cambios del proyecto. Permite recuperar versiones anteriores, evitar la pérdida de información y trabajar de manera colaborativa.  
El control de versiones mejora la organización, la trazabilidad y la calidad del desarrollo.

---

# 📚 Investigación sobre Markdown

## 1. 📌 ¿Qué es Markdown y por qué se utiliza en proyectos de software?
**Markdown** es un lenguaje de marcado ligero que permite escribir texto formateado de manera sencilla utilizando símbolos como `#`, `-`, `*` y `|`.  

Se usa en proyectos de software porque:  
- Es fácil de aprender y leer.  
- Ideal para documentar proyectos (README, guías, manuales).  
- Compatible con GitHub, GitLab, Bitbucket y más.  
- Se visualiza correctamente en cualquier plataforma.

---

## 2. 📝 Ejemplo práctico de Markdown

### Encabezados
```md
# Título
## Subtítulo
### Sección
Listas
md
Copiar código
- Elemento 1
- Elemento 2
- Elemento 3
Tabla
md
Copiar código
| Nombre | Edad |
|--------|------|
| Ana    | 22   |
| Luis   | 25   |
Enlaces
md
Copiar código
[Visitar GitHub](https://github.com)
Imagen
md
Copiar código
![Descripción](imagen.png)


Ventajas de usar Markdown con GitHub

GitHub convierte automáticamente el Markdown en una vista ordenada.

Permite documentar proyectos de manera clara y profesional.

Fácil de mantener y versionar con Git.

Compatible con Issues, Wikis, Pull Requests y proyectos colaborativos.

Facilita la comunicación entre desarrolladores.