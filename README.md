<!--
  PORTADA DEL REPOSITORIO PÚBLICO DE DESCARGAS.

  No se edita allí: el trabajo `publicar` de .github/workflows/instaladores.yml copia este archivo
  como README.md del repositorio público en cada release, junto con la licencia y el aviso de
  terceros. Cualquier cambio hecho a mano en el otro repositorio se pierde en la siguiente
  publicación; se edita aquí.
-->

<div align="center">

<img src="Assets/Icons/judo-256.png" alt="JudoCrono" width="128">

# JudoCrono

**El crono y el marcador del tatami, conectados a la competición.**

[![Descargar](https://img.shields.io/badge/Descargar-última%20versión-brightgreen?logo=github)](../../releases/latest)
[![Licencia](https://img.shields.io/badge/Licencia-Uso%20libre%20·%20sin%20derivados-green.svg)](LICENSE)
[![Windows · macOS · Linux](https://img.shields.io/badge/Windows%20·%20macOS%20·%20Linux-multiplataforma-informational)](#instalación)

</div>

---

## Qué es

La aplicación que se usa **en la mesa del tatami**: lleva el tiempo del combate, el marcador de los
dos competidores y manda el resultado al servidor de la competición en cuanto termina.

Es un cliente de [**JudoAdministración**](https://github.com/JuSaFe/JudoAdministracion-Releases).
No tiene base de datos propia ni funciona sola: se conecta por HTTPS al mismo servidor que los
puestos de administración, con las mismas credenciales y en la misma red local del pabellón.

## Instalación

Descarga el instalador de tu sistema desde la [**última versión**](../../releases/latest):

| Sistema | Archivo |
|---|---|
| Windows 10/11 (x64) | `.exe` |
| macOS (Apple Silicon) | `.dmg` |
| Linux (x64) | `.AppImage` |

Es **autocontenido**: no hace falta instalar .NET en el equipo del tatami. Sí hace falta un
servidor de [JudoAdministración](https://github.com/JuSaFe/JudoAdministracion-Releases) ya en
marcha en la misma red, y un usuario con rol `marcador`.

## Soporte

¿Un fallo, una duda o una propuesta? Abre una
[**incidencia**](../../issues/new) describiendo qué ocurre, en qué sistema y con qué versión.

El desarrollo se lleva en un repositorio privado; este de aquí es el punto de descarga y el canal
de incidencias.

## Licencia

Software **de código propietario y uso gratuito**. Texto completo en **[LICENSE](LICENSE)**.

**Se permite**, gratis y sin límite de equipos, usuarios ni tiempo:

- Descargar, instalar y ejecutar el programa, incluso con fines profesionales o comerciales.
- Redistribuirlo **íntegro y sin modificar**, a título gratuito y conservando todos los avisos.

**No se permite** modificarlo, crear obras derivadas, distribuir versiones modificadas, republicarlo
en otro repositorio ni reutilizar partes de él en otros proyectos.

La **propiedad intelectual del programa es de Juan Cotolí San Félix**.

> **Marcas y logotipos.** Los escudos federativos que incluye la aplicación son propiedad de sus
> respectivas entidades y no están cubiertos por esta licencia.

Las bibliotecas de terceros que incorpora se rigen por sus propias licencias, detalladas en
[TERCEROS.md](TERCEROS.md).

---

<div align="center">
<sub>Hecho para el tatami. 🥋</sub>
</div>
