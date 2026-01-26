\# Device Libs Android 📱



Librería de lógica centralizada para la gestión de dispositivos Century Cloud. Esta librería actúa como un wrapper profesional de los SDKs binarios del fabricante, permitiendo un control de versiones preciso y desacoplado.



\## 🚀 Instalación rápida



\### 1. Agregar JitPack a settings.gradle

```groovy

dependencyResolutionManagement {

&nbsp;   repositories {

&nbsp;       google()

&nbsp;       mavenCentral()

&nbsp;       maven { url "\[https://jitpack.io](https://jitpack.io)" }

&nbsp;   }

}

```



\### 2. Agregar la dependencia en build.gradle. 



Para mantener la compatibilidad con hardware antiguo, utilizamos las fechas de los SDKs del fabricante como identificadores de versión.







```groovy

dependencies {

&nbsp;   implementation 'com.github.CENTURYCLOUD:device-libs-android:deviceApi:2023.12.08'

}

```



\### 📌 Control de Versiones (Basado en SDK)

Para mantener la compatibilidad con hardware antiguo, utilizamos las fechas de los SDKs del fabricante como identificadores de versión. En el ejemplo anterior usamos la librería de diciembre del 2023(2023.12.08).



\### 📜 Changelog (Historial de Cambios)

\[2023.12.08] - 2026-01-26

\- SDK Integrado: DeviceAPI\_ver20231208\_release.aar.

\- Compatibilidad: Software Legacy.

\- Cambios: Primera versión estable migrada al repositorio de Century Cloud.



