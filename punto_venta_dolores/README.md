[Manual_TDD_PuntoDeVenta ANCS.pdf](https://github.com/user-attachments/files/35040947/Manual_TDD_PuntoDeVenta.ANCS.pdf)

🔴 ROJO: escribe la prueba (debe FALLAR)

 <img width="436" height="70" alt="image" src="https://github.com/user-attachments/assets/093b277c-1bf3-4e15-a71c-6a884d09705c" />

Paso 1.3 · 🟢 Verde: implementar
$ flutter test

<img width="666" height="105" alt="image" src="https://github.com/user-attachments/assets/78a6a462-9609-4165-a7ad-143b5ffc463b" />


🟢 VERDE: el código mínimo para pasar
Los tres casos pasan. Nota cómo cada línea responde a un caso: padLeft hace que 5 centavos sea "05", y la expresión regular inserta las comas de miles.

<img width="666" height="105" alt="image" src="https://github.com/user-attachments/assets/78a6a462-9609-4165-a7ad-143b5ffc463b" />

 
Paso 1.4 · Segunda prueba: texto a centavos
🔴 ROJO: escribe la prueba (debe FALLAR)

<img width="816" height="470" alt="image" src="https://github.com/user-attachments/assets/2d3613e0-1585-4300-8f7e-b8a3ed665f0d" />
<img width="942" height="108" alt="image" src="https://github.com/user-attachments/assets/1792d59b-10f6-49a9-bf01-8c48cabf63f7" />


🟢 VERDE: el código mínimo para pasar

<img width="656" height="120" alt="image" src="https://github.com/user-attachments/assets/9d2704a1-de77-47b4-a8f4-8d4e3cdd1cd8" />
 

Ronda 2 · El Producto
Paso 2.1 · 🔴  Prueba ROJA

<img width="641" height="492" alt="image" src="https://github.com/user-attachments/assets/8d9778ed-abb7-488f-b4cb-a749b4a72dcb" />
<img width="468" height="180" alt="image" src="https://github.com/user-attachments/assets/2d1a7e68-731a-4f90-8b43-0b0638aea379" />
 
Paso 2.2 · 🟢 VERDE

<img width="658" height="120" alt="image" src="https://github.com/user-attachments/assets/fed6d5e0-fd2f-4892-bdbf-3c6feae32122" />


Ronda 3 · El Carrito (el corazón del negocio)
Ciclo 3.1 · Sumar cantidades
🔴 ROJO: escribe la prueba (debe FALLAR)

<img width="633" height="566" alt="image" src="https://github.com/user-attachments/assets/428e9687-f6f9-4d14-9f6c-357ffcb739f2" />
<img width="629" height="98" alt="image" src="https://github.com/user-attachments/assets/e926c6f7-dc5a-4798-930a-136c6a132342" />


🟢 VERDE: el código mínimo para pasar

<img width="857" height="186" alt="image" src="https://github.com/user-attachments/assets/f4566f94-e48e-4c26-9d73-1bbbc3fcb4b1" />

 
Ciclo 3.2 · No vender lo que no hay
🔴 ROJO: escribe la prueba (debe FALLAR)

<img width="785" height="749" alt="image" src="https://github.com/user-attachments/assets/5e53103e-c57d-4347-95f3-25a96cef1e93" />
<img width="785" height="87" alt="image" src="https://github.com/user-attachments/assets/75cb2ac4-446b-4a65-9f6e-63bc5fd24543" />

   
🟢 VERDE: el código mínimo para pasar

 <img width="907" height="170" alt="image" src="https://github.com/user-attachments/assets/cd237ede-0019-4dd7-8297-ec567484fdd4" />


🔴 ROJO: escribe la prueba (debe FALLAR)

<img width="996" height="835" alt="image" src="https://github.com/user-attachments/assets/b579a187-d1d6-47eb-8efa-138a47b9379f" />

🟢 VERDE: el código mínimo para pasar

<img width="909" height="90" alt="image" src="https://github.com/user-attachments/assets/049ebc04-2e8f-466d-bf8a-42f79307b3f4" />

 
Ciclo 3.4 · Cambio, pago corto y carrito vacío
🔴 ROJO: escribe la prueba (debe FALLAR)

<img width="558" height="105" alt="image" src="https://github.com/user-attachments/assets/b25a7e69-5feb-47cc-b23a-a50145cbda84" />


🟢 VERDE: el código mínimo para pasar
$ flutter test test/dominio_test.dart
<img width="906" height="114" alt="image" src="https://github.com/user-attachments/assets/ef937e83-c6de-4f13-af20-c44f01da9f9c" />


Ciclo 4.3 · Guardar y buscar
🔴 ROJO: escribe la prueba (debe FALLAR)

<img width="647" height="225" alt="image" src="https://github.com/user-attachments/assets/993f746c-d7b4-4ef5-8362-15d4eaa20850" />
<img width="663" height="173" alt="image" src="https://github.com/user-attachments/assets/80be936d-e2b3-4d2e-8706-bda7ba0c4412" />

 
🟢 VERDE: el código mínimo para pasar

<img width="1004" height="112" alt="image" src="https://github.com/user-attachments/assets/53336d3c-bb99-4a48-bf57-bc382864f798" />

 

Ronda 5 · Cobrar: la transacción
Ciclo 5.1 · Cobrar descuenta inventario
🔴 ROJO: escribe la prueba (debe FALLAR)

 <img width="863" height="313" alt="image" src="https://github.com/user-attachments/assets/64ec0b18-a58e-4f72-9c54-566483310abb" />
<img width="847" height="282" alt="image" src="https://github.com/user-attachments/assets/cdaa40e1-9e62-4e66-a45e-390fcdfba0a7" />

 
🟢 VERDE: el código mínimo para pasar

<img width="906" height="114" alt="image" src="https://github.com/user-attachments/assets/1d594a5d-dd3c-41b6-91b8-6fcfeb3e25e5" />

 
Ciclo 5.2 · La prueba que demuestra la transacción
🔴 ROJO: escribe la prueba (debe FALLAR)

 <img width="847" height="282" alt="image" src="https://github.com/user-attachments/assets/2708ce4b-c878-4490-8210-5e3a31aaeb24" />


🟢 VERDE: el código mínimo para pasar

<img width="906" height="114" alt="image" src="https://github.com/user-attachments/assets/8636fb7b-7bf8-4162-b8da-ad66c5910cf1" />


Ciclo 5.3 · Corte del día
🔴 ROJO: escribe la prueba (debe FALLAR)

  <img width="847" height="282" alt="image" src="https://github.com/user-attachments/assets/8edafa0f-2258-4b6a-820c-6a4f7f424a3f" />


🟢 VERDE: el código mínimo para pasar
$ flutter test
<img width="906" height="114" alt="image" src="https://github.com/user-attachments/assets/5a13ada6-68d4-4e79-a6bd-dda1ebb71de1" />

 
Ronda 6 · ViewModel y pantalla
¿Por qué un ViewModel?
Si metes la lógica dentro del Widget, solo puedes probarla abriendo la pantalla. El ViewModel es un "intermediario": guarda el estado (catálogo, carrito, mensajes), llama a los repositorios y avisa a la pantalla cuando algo cambia con notifyListeners(). Así la pantalla solo dibuja.

Cierre · Lo que lograste
Checklist de calidad (revisa antes de entregar)
•	Todo el dinero está en centavos enteros; ningún double en el dominio.
•	El dominio no importa Flutter ni sqflite.
•	Cada regla de negocio nació de una prueba roja.
•	Cobrar usa una transacción y se probó el caso de fallo.
•	Los errores técnicos se traducen a excepciones de negocio con mensaje claro.
•	La pantalla no contiene reglas de negocio.
•	flutter test termina completamente en verde.
Preguntas para discutir en clase
7.	¿Qué pasaría con el corte del día si guardáramos los precios como double? Se acumularían errores de precisión flotante debidos a la representación binaria de los números decimales en computación (por ejemplo, operaciones que terminan dando .99999999 en lugar de un número exacto). Esto descuadraría la contabilidad y el corte de caja final por centavos fantasma. Por esta razón crítica se manejan centavos.
8.	¿Por qué revalidamos las existencias dentro de la transacción si el carrito ya las validó? Para prevenir condiciones de carrera (race conditions) y problemas de concurrencia. Entre el momento en que el cliente o cajero armó su carrito en la memoria de la app y el instante exacto en que se ejecuta la transacción en la base de datos, otro cajero en otra terminal pudo haber vendido esos mismos productos. La transacción en BD asegura que el stock sea real justo al momento de cobrar.
9.	¿Qué ventaja tiene probar con una base en memoria en lugar de la base real? Velocidad y aislamiento. 
10.	Si mañana cambiamos SQLite por una API en internet, ¿qué capas tendríamos que modificar? Únicamente la capa de datos (los repositorios y fuentes de datos). Gracias a la separación de responsabilidades y Clean Architecture, las reglas de negocio en el dominio y la interfaz de usuario no dependen de cómo o dónde se guardan los datos, por lo que el cambio de SQLite a una API web sería transparente para el resto de la aplicación.
Retos finales por equipos
•	Pantalla de "Corte del día" con total, IVA, número de ventas y los 5 productos más vendidos.
•	Pantalla de alta de productos con validación (precio mayor a cero, código único).
•	Ticket de venta compartible como texto (usa el paquete share_plus).
•	Descuentos por porcentaje y por producto, con pruebas primero.
•	Adapta el sistema a otro negocio de Dolores: papelería, taquería o tiend
