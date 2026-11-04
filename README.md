# Despliegue, Hardening y Gestión de Accesos (IAM) en Windows Server y Active Directory.

## Resumen Ejecutivo
Proyecto práctico de diseño, implementación y hardening de una infraestructura de dominio empresarial basada en **Windows Server 2022** y **Active Directory (AD DS)**. El objetivo principal es aplicar políticas de control de acceso, gestión de identidades (IAM) bajo el principio de menor privilegio y endurecimiento de seguridad mediante Directivas de Grupo (GPO).

---

## Arquitectura del Laboratorio
- **Sistema Operativo:** Windows Server 2022 Datacenter
- **Dominio:** `labciber.local`
- **Hostname:** `DC-LIMA-01`
- **Dirección IP:** `192.168.1.10/24`

---

## Hitos y Evidencias de Implementación

### 1. Configuración de Red y Promoción de Controlador de Dominio
- Asignación de dirección IP estática y resolución DNS local.
- Instalación de Servicios de Dominio de Active Directory (AD DS).
*(Espacio para evidencia visual 1)*

### 2. Estructura de Unidades Organizacionales (OUs) y Gestión de Identidades (IAM)
- Diseño jerárquico de Unidades Organizacionales (`Gerencia`, `TI`, `Operaciones`).
- Creación de usuarios y asignación de roles bajo el principio de menor privilegio.
*(Espacio para evidencia visual 2)*

### 3. Hardening y Directivas de Seguridad (GPOs)
- Implementación de políticas de complejidad y rotación de contraseñas.
- Configuración de umbral de bloqueo de cuenta ante intentos de fuerza bruta.
- Restricción de acceso a herramientas administrativas del sistema para usuarios no privilegiados.
*(Espacio para evidencia visual 3)*

### 4. Pruebas de Auditoría y Verificación
- Verificación del bloqueo de cuenta tras intentos fallidos de autenticación.
- Comprobación de aplicación de GPOs (`gpresult /r`).
*(Espacio para evidencia visual 4)*

---

## Habilidades y Competencias Validadas
- Administración de Active Directory (AD DS) y Servicios de Red (DNS).
- Gestión de Identidades y Accesos (IAM).
- Endurecimiento de Sistemas Operativos (Hardening).
- Configuración y auditoría de Directivas de Grupo (GPO).
