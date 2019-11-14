# api-datos-gob-mx
sdk for api.datos.gob.mx
[api datos gob](https://datos.gob.mx/blog/catalogo-apidatosgobmx?category=api-cdn&tag=nula)

# api documentation

## endpoint(qs) -> Promise

The next properties map between name and path documented:

```js
const nameToPathMap = {
    catalog: 'api-catalog',
  datasets: 'datasets',
  concesionesMineras: 'bases-de-datos-de-concesiones-mineras',
  calidadAire: 'calidadAire',
  condicionesAtmosfericas: 'condiciones-atmosfericas',
  calidadAgua: 'datos-de-calidad-del-agua-de-5000-sitios-de-monitoreo',
  calidadAguaUsoHumano: 'monitoreo-de-calidad-de-agua-de-uso-y-consumo-humano',
  fondenDesastres: 'fonden.desastres',
  fondenemergencias: 'fonden.emergencias',
  fondenreconstruccion: 'fonden.reconstruccion',
  inaiSolicitudes: 'inai.solicitudes',
  compranet: 'compranet',
  matriculaPorInstitucionYentidadFederativa: 'matricula-por-institucion-y-entidad-federativa',
  informacionSobreElInventarioTuristicoEnLasEntidadesFederativas: 'informacion-sobre-el-inventario-turistico-en-las-entidades-federativas',
  informacionSobreLaActividadHoteleraEnLosDestinosTuristicosDelPais: 'informacion-sobre-la-actividad-hotelera-en-los-destinos-turisticos-del-pais',
  precioGasolinaPublico: 'precio.gasolina.publico',
  profecoPrecios: 'profeco.precios',
  residuosSolidosUrbanosManejadosAdecuadamente: 'residuos-solidos-urbanos-manejados-adecuadamente',
  diccionario: 'diccionario',
  dgmEstadisticas: 'dgm.estadisticas',
  dataCore: 'data-core',
  gobmxFacts: 'gobmx.facts',
}
```