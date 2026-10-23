# ponyWhisper

Dictado por voz para Mac. Hablas, vuelves a pulsar el atajo y el texto se pega donde tengas el cursor. Todo corre en tu Mac: el audio no sale del equipo.

**Requisitos:** Mac con chip Apple (M1 o posterior) y unos 2 GB libres.

## Descargar

Baja el archivo `.dmg` de la última versión en **[Releases](../../releases/latest)**.

## Instalar

1. Abre el `.dmg` que descargaste.
2. Copia **ponyWhisper** a la carpeta **Aplicaciones de tu usuario**: en Finder, menú *Ir → Inicio* y abre `Aplicaciones` (si no existe, créala). Así no necesitas permisos de administrador.
3. Ábrela con doble clic. La primera vez macOS la bloquea porque no viene de la App Store:
   - Ve a **Ajustes del Sistema → Privacidad y seguridad**, baja hasta el aviso de ponyWhisper y pulsa **Abrir de todas formas**.
4. Dale los dos permisos que pide:
   - **Micrófono**: para oírte.
   - **Accesibilidad**: para escuchar el atajo y pegar el texto.
5. Deja que descargue **Whisper Medium** (0,8 GB, una sola vez).

## Usar

| Qué | Cómo |
|---|---|
| Dictar | Pulsa **⌥ Espacio**, habla y vuelve a pulsar **⌥ Espacio**. El texto se pega donde está el cursor. |
| Cancelar | **Esc** mientras dictas. |
| Ver el texto mientras hablas | Ajustes → **Texto en pantalla**. Descarga Voxtral (3 GB); es más pesado. Ahí mismo eliges el color del texto. |
| Volver al modo liviano | Apaga **Texto en pantalla** (en Ajustes o en el menú de la barra). |
| Que reconozca tus palabras | Pantalla **Mis palabras**: agrega nombres y términos que dices seguido. |
| Copiar lo último que dictaste | Botón **Copiar** en la pantalla principal, o el menú de la barra. |

## Si algo no funciona

| Pasa esto | Haz esto |
|---|---|
| El atajo no hace nada | Revisa que ponyWhisper tenga **Accesibilidad** en Privacidad y seguridad. Si tienes la app **Handy** abierta, ciérrala: las dos usan el mismo atajo. |
| Dicta pero no sale texto | Revisa el micrófono en Ajustes y el permiso de **Micrófono**. |
| Con el texto en pantalla va lento | Apaga **Texto en pantalla** para usar el modo liviano. |

## Actualizar

Descarga el `.dmg` nuevo de [Releases](../../releases/latest) y reemplaza la app en tu carpeta Aplicaciones. Tus ajustes y permisos se conservan.

## Desinstalar

Cierra ponyWhisper desde el menú de la barra y borra la app de tu carpeta Aplicaciones. Para borrar también los modelos y ajustes, elimina la carpeta `~/Library/Application Support/com.stevenson.ponywhisper`.

---

ponyWhisper se basa en [Handy](https://github.com/cjpais/Handy), de CJ Pais, distribuido bajo [licencia MIT](LICENSE).
