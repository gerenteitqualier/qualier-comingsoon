# Micrositio de Lanzamiento — Qualier Internacional
**Proyecto Horizonte · Mayo 2026**

---

## ¿Qué es este micrositio?

Una página web temporal publicada en **qualierinternacional.com** durante la semana previa al lanzamiento oficial del 25 de mayo. Su función es generar expectativa, confirmar la existencia del nuevo dominio corporativo y mostrar una cuenta regresiva al evento.

---

## Elementos clave

- **Cuenta regresiva en tiempo real** al 25 de mayo a las 9:00 AM, sincronizada automáticamente con la zona horaria del país desde donde se consulta (Venezuela, Colombia, Panamá, República Dominicana y más).
- **Identidad visual oficial** aplicada al 100%: logotipo principal de Qualier Internacional, paleta de colores corporativa, tipografías Raleway y Graphik.
- **Claim de campaña** visible: *"Medio siglo construyendo confianza. Una nueva marca para liderar el futuro."*
- **Responsive**: se adapta correctamente a teléfonos, tablets y computadoras de escritorio.
- Cuando el contador llega a cero, la página cambia automáticamente al mensaje de bienvenida oficial.

---

## Infraestructura y despliegue

| Elemento | Detalle |
|---|---|
| Plataforma de publicación | Vercel (servicio en la nube, costo $0) |
| Dominio | qualierinternacional.com |
| Repositorio de código | GitHub — cuenta corporativa Qualier |
| Tiempo de carga estimado | < 1 segundo |
| Disponibilidad garantizada | 99.99% (SLA de Vercel) |

El sitio es completamente estático: no tiene base de datos, no procesa datos de usuarios y no requiere servidor propio. Esto lo hace seguro, rápido y de mantenimiento cero.

---

## Seguridad del dominio de correo

El dominio `@qualierinternacional.com` cuenta con los tres estándares de autenticación de correo electrónico:

- **SPF** — autoriza únicamente a Google Workspace a enviar correos en nombre de Qualier.
- **DKIM** — firma digitalmente cada correo para garantizar su autenticidad.
- **DMARC** — instruye a los servidores receptores a rechazar o poner en cuarentena correos fraudulentos que suplanten el dominio.

Esto protege la reputación de la marca y reduce el riesgo de phishing hacia clientes y proveedores.

---

## Responsable técnico

César Fernando Blanco — Gerencia IT  
Coordinación con G. Ferraro y la Directiva.

---

*Documento interno · Confidencial · Proyecto Horizonte 2026*
