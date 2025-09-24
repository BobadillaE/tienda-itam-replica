# Réplica de la Tienda ITAM

Este proyecto es una réplica fiel de la página principal de la tienda del ITAM, construida con Bootstrap 5.3 y CSS personalizado.

---

## 🚀 Enlace a la Página Desplegada

**Puedes ver el sitio en vivo aquí:** [https://bobadillae.github.io/tienda-itam-replica/](https://bobadillae.github.io/tienda-itam-replica/)


---

## 🗂️ Comandos Utilizados

A continuación se documenta el flujo de comandos de Git utilizados para la creación y gestión de este proyecto.

1.  **Configuración Inicial:**
    ```bash
    git init
    git remote add origin [https://github.com/BobadillaE/tienda-itam-replica]
    ```

2.  **Creación de la Rama de Desarrollo:**
    ```bash
    git checkout -b desarrollo
    ```

3.  **Flujo de Trabajo Típico (Guardar Cambios):**
    ```bash
    git add .
    git commit -m "Mensaje descriptivo del commit"
    ```

4.  **Subir Cambios a GitHub:**
    ```bash
    git push origin desarrollo
    ```

5.  **Corrección de Ramas (Aplicado una vez):**
    ```bash
    git branch -m desarrollo main
    git push origin main
    git checkout -b desarrollo
    git push origin desarrollo
    ```

---

##  Pull Requests

Se utilizó un flujo de trabajo basado en Pull Requests para integrar los cambios a la rama principal (`main`).

* **Pull Request #1: Código de la Página**
    * **Enlace:** [feat: Implementar menú desplegable de colecciones #1](https://github.com/BobadillaE/tienda-itam-replica/pull/1)


* **Pull Request #2: Evidencias de Video**
    * *Enlace se añadirá cuando se completen las grabaciones.*