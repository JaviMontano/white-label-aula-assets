# Uso del banco

[METODOLOGIA] Instala el ZIP runtime fijado por `assets/bank.json` desde una skill 1.1.0. El repositorio completo contiene galería y documentación, y no es un directorio runtime válido.

```sh
python3 engine/bank.py sync --pin assets/bank.json --dest ../aula-bank-1.1.0
python3 engine/runtime.py build --kind immersive-class --edition EDITION --input input.json --out ../pieza-nueva --bank ../aula-bank-1.1.0
```

Sustituye EDITION por la edición de la skill. Alternativa offline: `bank.py install ARCHIVO.zip --sha256 HASH --dest NUEVO`, con el hash exacto del pin. Cache alterada, piezas ausentes, edición incompatible y SVG inseguro bloquean. El build embebe únicamente piezas utilizadas y las fuentes requeridas; la pieza no consulta la red.

Consulta `catalog.json` por significado, tags y usos. Cada entrada tiene ID, límites, parámetros y ejemplo de `sceneParams` o `assetRefs`; la galería ofrece búsqueda por intención. 256 iconos combinan metáforas y acciones distintas; 160 composiciones combinan20familiassemánticas con8relacionesgeométricas. Recolores, idiomas y previews no aumentan los conteos.

Código y geometría originales se mantienen en `05_verificacion/scripts/build-aula-assets.py` de Frames; cada repositorio conserva su perfil. MIT para iconos y escenas propios, OFL para fuentes, sin permiso implícito sobre marcas. Ejemplos RENDERED_DRAFT.
