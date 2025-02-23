# Prueba de API con Postman
---

### Importar la Colección
1. Abre Postman.
2. Ve a **File > Import**.
3. Carga el archivo `PARTNERS.postman_collection` incluido en el folder en este repositorio.

### Configurar el Entorno
1. Abre Postman.
2. Ve a la sección de **Environments** y haz clic en **Import**.
3. Carga el archivo `PARTNERS_VAR.postman_environment` incluido en el folder este repositorio.

## Run tests:
Usa el siguiente comando para ejecutar los test  (no grafico):

```bash
newman run PARTNERS.postman_collection.json -e PARTNERS_VAR.postman_environment.json
```

## Generate the report:
Ejecuta el siguente comando para ejecutar los test reporte no grafico:

```bash
newman run PARTNERS.postman_collection.json -e PARTNERS_VAR.postman_environment.json -r html --reporter-html-export report.html
```

Para un reporte mas grafico 
```bash
newman run PARTNERS.postman_collection.json -e PARTNERS_VAR.postman_environment.json -r htmlextra
```
### Documentacion de la API
https://documenter.getpostman.com/view/38910927/2sAYdcsCgP
---

# PARTNER

