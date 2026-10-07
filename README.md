# Configuración en MacOS y Linux

Ejecute los siguientes comandos en el terminal:

```bash
python3 -m venv .venv
source .venv/bin/activate
source setup.sh
```

# Configuración en Windows

Ejecute los siguientes comandos en el terminal:

```bash
python3 -m venv .venv
.venv\Scripts\activate
setup
```

# Ejecución de pruebas

Para probar una actividad individual, ejecute desde la raíz del repositorio:

```bash
python -m pytest P001_hola_mundo/tests -q
```

Reemplace `P001_hola_mundo` por el nombre de la actividad que quiera probar.
Por ejemplo, para ejecutar las pruebas de MapReduce:

```bash
python -m pytest P100_mapreduce_word_count/tests -q
```

Ejecutar `pytest` sin indicar una actividad lanza las pruebas de todo el
repositorio; puede fallar por ejercicios todavía sin resolver y por módulos
con nombres repetidos entre actividades.
