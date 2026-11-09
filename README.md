# Def-ensio

Abre `index.html` en un navegador moderno para jugar. El juego es autónomo y ocupa menos de 32 KiB.

- Los Stickman alternan tres poses de artes marciales al eliminar una enemiga. Cada pose dura 0,2 s desde el último golpe y después vuelve a neutra.
- Cada túnel cuesta 35 de saldo y conecta una dirección aleatoria con el imán durante 60 s. Hasta 8 activos, con temporizadores independientes y sin recarga de compra.

Para ejecutar las autopruebas, abre `index.html?test=1` y consulta la consola: debe mostrar `98 autopruebas correctas`. Comprueban compras, duración, límites, poses, colisiones y reinicio, entre otras reglas.

La portada y sus archivos de edición se conservan localmente en `portada/` y están excluidos de Git.
