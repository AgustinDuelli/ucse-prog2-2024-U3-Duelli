## Ejemplo de la api
http://localhost:4001/tz?zone=America/Los_Angeles

### Zonas horarias
Lista de zonas horarias del mundo para probar
[Link](https://gist.github.com/diogocapela/12c6617fc87607d11fd62d2a4f42b02a)

## Ejemplo de la API (implementación en Docker)
Utilizando la configuración de network específica, se puede pasar como url el nombre de servicio de docker para acceder luego al puerto 4000 de la app1.
http://localhost:4001/checker?url=app1&zone=America/Los_Angeles

Resultado de pruebas:

- America, Los Angeles
![image](https://github.com/AgustinDuelli/ucse-prog2-2024-U3-Duelli/assets/130614935/fae1837a-0677-429c-81cd-2ba5f182b808)

- Africa, Accra

![image](https://github.com/AgustinDuelli/ucse-prog2-2024-U3-Duelli/assets/130614935/985fe471-9b55-449b-9c05-ae649f5d7771)

Asia, Famagusta

![image](https://github.com/AgustinDuelli/ucse-prog2-2024-U3-Duelli/assets/130614935/19b067bf-f16d-4048-9006-5a02413748eb)
