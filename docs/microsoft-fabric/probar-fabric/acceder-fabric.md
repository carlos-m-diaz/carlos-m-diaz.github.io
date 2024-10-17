---
layout: default
title: Accediendo a MS Fabric
parent: Probando MS Fabric
nav_order: 1
---

# Cómo acceder a Fabric?
Hace tiempo que vengo pidiendo algún usuario o capacidad de prueba de Fabric a mi consultora sin conseguirlo, así que, ya que tengo mas dudas que certezas, decidí obtener un nuevo período de pruebas para realizar una POC punta a punta del ciclo de vida del desarrollo de machine learning.
Para obtener 60 días de período de pruebas podemos realizar los pasos descritos en una [publicación del blog de fabric](https://blog.fabric.microsoft.com/en-us/blog/accessing-microsoft-fabric-for-developers-startups-and-enterprises/), está bien explicado y fácil de seguir. Sin embargo aquí les presento mi versión.

## Crear cuenta de Office 365
Esto nos permitirá generar un correo empresarial que será necesario para acceder a Fabric.

{: .highlight }
> - Para esto será necesario utilizar una tarjeta de crédito válida.
> - El trial de la cuenta de Office 365 dura 30 días.
> - Puedes desactivar la facturacción automática y seguir usando fabric sin problemas.

Entra a la siguiente [página](https://www.microsoft.com/es-ar/microsoft-365/enterprise/office365-plans-and-pricing) y seleccióna una licencia de **Office 365 E5** y hacer click sobre **Prueba Gratis**.

![licecia Office 365 E5](/docs/microsoft-fabric/probar-fabric/acceder-fabric/images/1.png)

En la casilla de correo electrónico escribir cualquier email propio, yo utilicé un gmail y pasó. Con esto se accede al path de crear una nueva cuenta empresarial.

![Introducir correo propio](/docs/microsoft-fabric/probar-fabric/acceder-fabric/images/2.png)

Seleccionar configurar cuenta, llenar los datos personales, click en siguiente.
Realizar la comprobación de seguridad, en mi caso solicité recibir un mensaje de texto a mi número telefónico.
Ajusta el nombre del dominio a tu gusto y genera una contraseña interesante para llenar los campos necesarios.
Completa los datos de pago con una tarjeta de crêdito válida.

![Conpletar datos de pago](/docs/microsoft-fabric/probar-fabric/acceder-fabric/images/3.png)

Si seguiste los pasos, habrás creado una cuenta de pruebas de Office 365

![Cuenta creada](/docs/microsoft-fabric/probar-fabric/acceder-fabric/images/4.png)

## Desactivar facturación mensual

Una vez creada la cuenta de Office 365 podemos desactivar la facturación mensual para evitar cargos a la tarjeta de credito. Para hacerlo siguie estos pasos:

- Entra con la cuenta recien creada al [portal de administración de office 365](https://admin.microsoft.com/)
- Navega al menu **Facturación** --> **Sus productos**
- Ubica Office 365 E5 en la lista (debería ser el único item) y haz click en los 3 puntos
- Selecciona **Editar Facturación Periódica** --> **Desactivado** --> **Guardar** --> **Si**

![Facturacion](/docs/microsoft-fabric/probar-fabric/acceder-fabric/images/5.png)

## Entremos a Fabric

Podemos acceder a fabric con la cuenta que recien creamos entrando a [https://app.fabric.microsoft.com](https://app.fabric.microsoft.com)

![Fabric inicio](/docs/microsoft-fabric/probar-fabric/acceder-fabric/images/6.png)

## Activa el trial de Fabric
Presiona el icono del account manager en la esquina superior derecha, selecciona iniciar prueba y acepta las condiciones.

![Inciar Prueba](/docs/microsoft-fabric/probar-fabric/acceder-fabric/images/7.png)

![Aceptar las condiciones](/docs/microsoft-fabric/probar-fabric/acceder-fabric/images/8.png)

Listo!!! Tenemos un entorno de Fabric para probar!!!


