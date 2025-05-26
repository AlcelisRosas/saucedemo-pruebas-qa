# Saucedemo-pruebas-qa
Pruebas funcionales manuales con casos y resultados para el sitio SauceDemo


# 🧪 SauceDemo – Pruebas QA Manual Jr

Este repositorio contiene el informe de pruebas funcionales manuales ejecutadas sobre el sitio de práctica [SauceDemo](https://www.saucedemo.com/) como parte del entrenamiento de pruebas QA Manual nivel junior.

---

## Información general


- **Tester:** Alcelis  Rosas  
- **Fecha de ejecución:** 20 de mayo de 2025  
- **Tipo de pruebas:** Funcionales Manuales  
- **Funcionalidad probada:** Login y compra de productos  
- **Entorno:** Navegador Chrome – Web  
- **Versión de la App:** Demo pública de SauceDemo  



## Historia de usuario

 Como usuario registrado, quiero poder iniciar sesión, agregar un producto al carrito y completar una compra para obtener mis artículos.



## Casos de prueba ejecutados

| ID      | Caso de prueba                    | Estado  |
|---------|----------------------------------|---------|
| TC001   | Login exitoso                    | Passed |
| TC002   | Agregar producto al carrito      | Passed |
| TC003   | Finalizar compra                 | Passed |
| TC004   | Login fallido                    | Passed |



## Incidentes encontrados

| ID       | Descripción                                                                 | Severidad | Estado  |
|----------|------------------------------------------------------------------------------|-----------|---------|
| BUG001   | El mensaje de error por login fallido es poco visible y no específico.      | Media     | Abierto |

---

## Métricas

- **Total de casos ejecutados:** 4  
- **Casos exitosos:** 4  
- **Casos fallidos:** 0  
- **Bugs encontrados:** 1  
- **Tiempo total de prueba:** 30 minutos

---

## Archivos incluidos

Informe: saucedemo-pruebas-qa.pdf` → Informe completo con resultados y observaciones → Capturas de pantalla de cada ejecución



## Conclusión

Las pruebas fueron satisfactorias en los 4 escenarios planteados, validando funcionalidades clave como login, navegación, carrito de compras y finalización de pedidos. Se detectó una mejora visual pendiente en el mensaje de error para credenciales inválidas.



