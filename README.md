# java_course

Se requiere crear 3 componentes
- 3 bases de datos
- 1 kafka

## Caso de Uso 1
- Se debe crear un servicio con java spring boot que lea la BD1 y cada que exista un registro en una tabla X nuevo genere un evento en un topico de kafka

## Caso de Uso 2
- Se debe crear un enriquecedor que lea el topico y enriquesca con informacion de BD2

## Caso de Uso 3
- Se debe generar un consumer que lea los eventos enriquecidos e inserte en BD3

## Caso de Uso 4
- Generar un servico rest en spring boot que permita consultar los datos de BD3


- [ ] Todo esto debe poder levantarse con un docker compose
- [ ] Se deben generar las ramas test, develop y main para prod
