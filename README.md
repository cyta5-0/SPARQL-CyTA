# Proyecto SPARQL en CyTA

Este repositorio contiene el desarrollo de la integración de consultas SPARQL en CyTA, utilizando PHP y MySQL para gestionar datos RDF de los artículos científicos publicados en la plataforma.

## Objetivo

El propósito del proyecto es permitir la consulta estructurada de los metadatos de los artículos de CyTA mediante SPARQL, aprovechando la base de datos MySQL existente y generando representaciones RDF de los contenidos.

## Componentes principales

1. **visual_rdf.php** ([Ver en CyTA](https://cyta.com.ar/cybercyta/visual_rdf.php))  
   - Visualiza los datos RDF generados.
   - Permite verificar la correcta estructuración de los metadatos.

2. **RDF_MYSQL_NOVO.php** ([Ver en CyTA](https://cyta.com.ar/cybercyta/RDF_MYSQL_NOVO.php)))  
   - Genera los datos RDF a partir de la base de datos MySQL.
   - Facilita la conversión de los metadatos de los artículos en un formato compatible con la web semántica.

3. **sparql.php** ([Ver en CyTA](https://cyta.com.ar/cybercyta/sparql.php))  
   - Permite realizar consultas SPARQL sobre los datos RDF generados.
   - Se ampliará para incluir nuevas consultas con la información recientemente incorporada.
  
4. **[articulos.rdf](https://www.cyta.com.ar/cybercyta/buscar.php)**  
   - Archivo PHP, permite realizar las búsqueds en SPARQL mdediante un query y generar un endpoint.   

5. **articulos.rdf** ([Descargar RDF](https://cyta.com.ar/cybercyta/articulos.rdf))  
   - Archivo RDF generado, con los metadatos estructurados de los artículos.
   
## Tareas pendientes

- Generar nuevas consultas SPARQL basadas en los metadatos actualizados.
- Optimizar la integración con PHP y MySQL para mejorar la eficiencia del sistema.

## Instalación y uso

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/tu-repositorio.git
   ```
2. Configurar un entorno con PHP y MySQL.
3. Subir los archivos al servidor y verificar el correcto funcionamiento de las consultas RDF y SPARQL.

## Contribución

Este es un proyecto abierto. Se aceptan sugerencias y mejoras a través de pull requests o issues en GitHub.

---

### Contacto
Para más información, visita [CyTA](https://www.cyta.com.ar/) o escribe a cyta@cyta.ar.

