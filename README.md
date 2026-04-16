# 📘 Taller Grupal: Ejercicios de Casos de Uso

---

## 1️⃣ Sistema de Biblioteca

### 📌 Contexto

Sistema para gestionar préstamos de libros.

### 👤 Actores

* Usuario
* Bibliotecario

### ⚙️ Casos de uso

* Registrar usuario
* Buscar libro
* Consultar disponibilidad
* Prestar libro
* Devolver libro

### 🔗 Relaciones

* **<<include>>**: Prestar libro → Consultar disponibilidad

### 🖼️ Diagrama

![Sistema Biblioteca](biblioteca.png)

---

## 2️⃣ Sistema de Tienda Online

### 📌 Contexto

Permite a los usuarios comprar productos en línea.

### 👤 Actores

* Cliente
* Sistema de pagos

### ⚙️ Casos de uso

* Ver productos
* Agregar al carrito
* Realizar compra
* Pagar
* Aplicar descuento

### 🔗 Relaciones

* **<<include>>**: Realizar compra → Pagar
* **<<extend>>**: Aplicar descuento → Realizar compra

### 🖼️ Diagrama

![Tienda Online](tienda.png)

---

## 3️⃣ Sistema de Chat

### 📌 Contexto

Aplicación de mensajería tipo WhatsApp.

### 👤 Actores

* Usuario
* Sistema de notificaciones

### ⚙️ Casos de uso

* Iniciar sesión
* Enviar mensaje
* Recibir mensaje
* Ver notificaciones

### 🔗 Relaciones

* **<<include>>**: Enviar mensaje → Iniciar sesión
* **<<extend>>**: Ver notificaciones → Recibir mensaje

### 🖼️ Diagrama

![Sistema Chat](chat.png)

---

## 4️⃣ Sistema de Reservas de Hotel

### 📌 Contexto

Permite reservar habitaciones.

### 👤 Actores

* Cliente
* Recepcionista

### ⚙️ Casos de uso

* Buscar habitación
* Consultar disponibilidad
* Reservar habitación
* Cancelar reserva
* Confirmar reserva
* Realizar pago

### 🔗 Relaciones

* **<<include>>**: Reservar habitación → Consultar disponibilidad
* **<<include>>**: Reservar habitación → Realizar pago

### 🖼️ Diagrama

![Sistema Hotel](hotel.png)

---

## 5️⃣ Sistema Académico

### 📌 Contexto

Gestión de estudiantes y docentes.

### 👤 Actores

* Docente
* Estudiante

### ⚙️ Casos de uso

* Registrar notas
* Ver calificaciones
* Consultar materias

### 🔗 Relaciones

* **<<include>>**: Registrar notas → Consultar materias

### 🖼️ Diagrama

![Sistema Académico](academico.png)

---

## 6️⃣ Sistema de Cajero Automático

### 📌 Contexto

Permite realizar operaciones bancarias.

### 👤 Actores

* Usuario
* Sistema bancario

### ⚙️ Casos de uso

* Validar PIN
* Consultar saldo
* Retirar dinero

### 🔗 Relaciones

* **<<include>>**: Retirar dinero → Validar PIN
* **<<include>>**: Consultar saldo → Validar PIN

### 🖼️ Diagrama

![Cajero Automático](cajero.png)

---

## 7️⃣ Sistema de Delivery

### 📌 Contexto

Aplicación para pedir comida.

### 👤 Actores

* Cliente
* Repartidor
* Restaurante

### ⚙️ Casos de uso

* Realizar pedido
* Preparar pedido
* Entregar pedido
* Pagar pedido

### 🔗 Relaciones

* **<<include>>**: Realizar pedido → Pagar pedido

### 🖼️ Diagrama

![Delivery](delivery.png)

---

## 8️⃣ Sistema de Gestión de Eventos

### 📌 Contexto

Permite crear y reservar eventos.

### 👤 Actores

* Organizador
* Usuario

### ⚙️ Casos de uso

* Crear evento
* Publicar evento
* Comprar ticket

### 🔗 Relaciones

* **<<include>>**: Comprar ticket → Validar disponibilidad

### 🖼️ Diagrama

![Eventos](eventos.png)

---

## 9️⃣ Sistema de Gimnasio

### 📌 Contexto

Control de usuarios y rutinas.

### 👤 Actores

* Usuario
* Entrenador

### ⚙️ Casos de uso

* Inscribirse
* Registrar asistencia
* Asignar rutina

### 🔗 Relaciones

* **<<include>>**: Registrar asistencia → Validar membresía

### 🖼️ Diagrama

![Gimnasio](gimnasio.png)

---

## 🔟 Sistema de Turismo

### 📌 Contexto

Aplicación para reservar tours.

### 👤 Actores

* Cliente
* Agencia

### ⚙️ Casos de uso

* Buscar destinos
* Reservar tour
* Pagar
* Confirmar reserva

### 🔗 Relaciones

* **<<include>>**: Reservar tour → Pagar
* **<<extend>>**: Confirmar reserva → Reservar tour

### 🖼️ Diagrama

![Turismo](turismo.png)

---

## ✅ Requisitos cumplidos

* ✔️ Identificación de actores
* ✔️ Definición de casos de uso
* ✔️ Uso de relaciones <<include>> y <<extend>>
* ✔️ Representación gráfica mediante diagramas UML
