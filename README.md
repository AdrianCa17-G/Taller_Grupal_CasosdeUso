#  Taller Grupal: Ejercicios de Casos de Uso

##  Fecha

16 de abril de 2026

##  Integrantes

* Anthony Godoy
* Adrian Guaman
* Byron Vargas
---

## 1️. Sistema de Biblioteca

###  Contexto

Sistema para gestionar préstamos de libros.

###  Actores

* Usuario
* Bibliotecario

###  Casos de uso

* Registrar usuario
* Buscar libro
* Consultar disponibilidad
* Prestar libro
* Devolver libro

###  Relaciones

* **<<include>>**: Prestar libro → Consultar disponibilidad

###  Diagrama

![](https://github.com/AdrianCa17-G/Taller_Grupal_CasosdeUso/blob/main/Casos%20de%20Uso%20UML/uml_biblioteca.png)

---

## 2. Sistema de Tienda Online

###  Contexto

Permite a los usuarios comprar productos en línea.

###  Actores

* Cliente
* Sistema de pagos

###  Casos de uso

* Ver productos
* Agregar al carrito
* Realizar compra
* Pagar
* Aplicar descuento

###  Relaciones

* **<<include>>**: Realizar compra → Pagar
* **<<extend>>**: Aplicar descuento → Realizar compra

###  Diagrama

![](https://github.com/AdrianCa17-G/Taller_Grupal_CasosdeUso/blob/main/Casos%20de%20Uso%20UML/uml_tienda_online.png)

---

## 3. Sistema de Chat

###  Contexto

Aplicación de mensajería tipo WhatsApp.

###  Actores

* Usuario
* Sistema de notificaciones

###  Casos de uso

* Iniciar sesión
* Enviar mensaje
* Recibir mensaje
* Ver notificaciones

###  Relaciones

* **<<include>>**: Enviar mensaje → Iniciar sesión
* **<<extend>>**: Ver notificaciones → Recibir mensaje

###  Diagrama

![](https://github.com/AdrianCa17-G/Taller_Grupal_CasosdeUso/blob/main/Casos%20de%20Uso%20UML/diagrama_uml_chat.png)

---

## 4. Sistema de Reservas de Hotel

###  Contexto

Permite reservar habitaciones.

###  Actores

* Cliente
* Recepcionista

###  Casos de uso

* Buscar habitación
* Consultar disponibilidad
* Reservar habitación
* Cancelar reserva
* Confirmar reserva
* Realizar pago

###  Relaciones

* **<<include>>**: Reservar habitación → Consultar disponibilidad
* **<<include>>**: Reservar habitación → Realizar pago

###  Diagrama

![](https://github.com/AdrianCa17-G/Taller_Grupal_CasosdeUso/blob/main/Casos%20de%20Uso%20UML/diagrama_uml_hotel.png)

---

## 5. Sistema Académico

###  Contexto

Gestión de estudiantes y docentes.

###  Actores

* Docente
* Estudiante

###  Casos de uso

* Registrar notas
* Ver calificaciones
* Consultar materias

###  Relaciones

* **<<include>>**: Registrar notas → Consultar materias

###  Diagrama

![](https://github.com/AdrianCa17-G/Taller_Grupal_CasosdeUso/blob/main/Casos%20de%20Uso%20UML/diagrama_uml_academico.jpg)

---

## 6. Sistema de Cajero Automático

###  Contexto

Permite realizar operaciones bancarias.

###  Actores

* Usuario
* Sistema bancario

###  Casos de uso

* Validar PIN
* Consultar saldo
* Retirar dinero

###  Relaciones

* **<<include>>**: Retirar dinero → Validar PIN
* **<<include>>**: Consultar saldo → Validar PIN

###  Diagrama

![](https://github.com/AdrianCa17-G/Taller_Grupal_CasosdeUso/blob/main/Casos%20de%20Uso%20UML/diagrama_uml_cajero.jpg)

---

## 7. Sistema de Delivery

###  Contexto

Aplicación para pedir comida.

###  Actores

* Cliente
* Repartidor
* Restaurante

###  Casos de uso

* Realizar pedido
* Preparar pedido
* Entregar pedido
* Pagar pedido

###  Relaciones

* **<<include>>**: Realizar pedido → Pagar pedido

###  Diagrama

![](https://github.com/AdrianCa17-G/Taller_Grupal_CasosdeUso/blob/main/Casos%20de%20Uso%20UML/diagrama_uml_delivery.jpg)

---

## 8. Sistema de Gestión de Eventos

###  Contexto

Permite crear y reservar eventos.

###  Actores

* Organizador
* Usuario

###  Casos de uso

* Crear evento
* Publicar evento
* Comprar ticket

###  Relaciones

* **<<include>>**: Comprar ticket → Validar disponibilidad

###  Diagrama

![Eventos](eventos.png)

---

## 9. Sistema de Gimnasio

###  Contexto

Control de usuarios y rutinas.

###  Actores

* Usuario
* Entrenador

###  Casos de uso

* Inscribirse
* Registrar asistencia
* Asignar rutina

###  Relaciones

* **<<include>>**: Registrar asistencia → Validar membresía

###  Diagrama

![Gimnasio](gimnasio.png)

---

## 10. Sistema de Turismo

###  Contexto

Aplicación para reservar tours.

###  Actores

* Cliente
* Agencia

###  Casos de uso

* Buscar destinos
* Reservar tour
* Pagar
* Confirmar reserva

###  Relaciones

* **<<include>>**: Reservar tour → Pagar
* **<<extend>>**: Confirmar reserva → Reservar tour

###  Diagrama

![Turismo](turismo.png)

---
