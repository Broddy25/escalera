# Escaleras – APK (WebView)

App Android que abre tu aplicación web de Apps Script.

1. Edita `app/src/main/res/values/strings.xml` y pega tu URL `.../exec` en `app_url`.
2. Sube todo este proyecto a un repositorio de GitHub (rama `main`).
3. Ve a la pestaña **Actions** → **Compilar APK** → espera el check verde.
4. Entra a esa ejecución y descarga **escaleras-apk** (Artifacts). Descomprime y instala `app-debug.apk`.

Tu app de Apps Script debe estar implementada con acceso **Cualquiera**:
Google bloquea el inicio de sesión dentro de un WebView.
