# Telar — Soporte para VS Code

Extensión oficial de VS Code para el lenguaje de programación [Telar](https://github.com/davidbc01/telar).

## Características

- Resaltado de sintaxis para archivos `.telar`
- Reconocimiento de palabras clave en español
- Comentarios con `#`
- Strings, números y nombres propios diferenciados

## Ejemplo
```telar
aplicación MiTienda

  página inicio en "/"
    título "Bienvenido"

    mostrar productos recientes
      máximo 8
      ordenados por precio

    si el usuario está conectado
      botón "Mi cuenta" ir a cuenta
    si no
      botón "Entrar" ir a login

    optimizar para móvil
    caché 10 minutos
```

## Instalación de Telar
```bash
npm install -g @davidbc01/telar
telar servir app.telar
```

## Más información

- [Repositorio de Telar](https://github.com/davidbc01/telar)
- [npm](https://www.npmjs.com/package/@davidbc01/telar)
