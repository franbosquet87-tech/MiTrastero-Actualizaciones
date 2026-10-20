# Canal de actualizaciones de Mi Trastero

Este repositorio público distribuye **solo la interfaz HTML** de la aplicación Android. El proyecto Android y el inventario privado se mantienen separados.

## Canal para configurar en la app

```
https://raw.githubusercontent.com/franbosquet87-tech/MiTrastero-Actualizaciones/main/updates/latest.json
```

En el teléfono: **Más → Canal de actualizaciones → Configurar**, pegar la URL y guardar; después **Más → Actualizaciones → Buscar**.

## Publicación actual

- Versión: **V2.2.4 (prueba)**
- Revisión: **1792521447**
- `updates/latest.json`: manifiesto de versión y huella SHA-256
- `updates/app-ui.html`: interfaz HTML

La actualización no reinstala la APK ni modifica directamente los datos almacenados. El primer ensayo debe comprobarse en el teléfono. Se recomienda exportar una copia JSON antes de actualizar.

**Privacidad y seguridad:** No subir fotografías, inventarios, copias de seguridad JSON, contraseñas ni claves privadas. GitHub distribuye código de interfaz públicamente; la huella SHA-256 valida integridad frente al manifiesto, no es una firma digital independiente.
