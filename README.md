# FFBoost

**Menos delay. Más control sobre tu equipo.**
FFBoost es un optimizador de Windows hecho para jugar Free Fire competitivo (emulador o juego nativo). Cada ajuste se puede medir, se puede deshacer y no manda datos a ningún lado.

## Tres niveles

| Nivel | Para qué |
|---|---|
| **Recomendado** | Lo esencial. Seguro para cualquier PC y sin tocar nada delicado. |
| **Para competitivo** | Todo lo anterior, más servicios, privacidad y tus apps (Discord, Steam, navegadores) para torneos. |
| **Máximo** | Todo lo anterior, más ajustes profundos de procesador, memoria, red y gráficos, con un perfil automático por partida (Modo Sesión). |

Los niveles son acumulativos. Lo que no se puede deshacer (quitar OneDrive o Edge, por ejemplo) nunca entra en un nivel y siempre pide confirmación.

## Todo es reversible

Antes de aplicar se crea un punto de restauración y se guarda el estado previo de cada valor. **Revertir todo** devuelve la PC a como estaba. Sin telemetría: la app solo usa la red para el ping y el DNS que vos medís.

FFBoost no incluye macros ni anti-retroceso ni nada que automatice la puntería (Garena los prohíbe).

## Requisitos

- Windows 10 (1809 o superior) o Windows 11, 64 bits.
- Permisos de administrador para aplicar los ajustes.
- WebView2 Runtime (el instalador lo revisa y lo descarga si falta).

## Instalación

1. Bajá `FFBoost-Setup-1.1.0.exe` desde [Releases](../../releases/latest).
2. Ejecutalo y seguí el asistente.

### Aviso de SmartScreen

El instalador todavía **no está firmado digitalmente**, así que Windows puede mostrar "Windows protegió su PC". Es normal:

1. Tocá **Más información**.
2. Tocá **Ejecutar de todas formas**.

## Verificá la descarga (SHA-256)

El SHA-256 de cada versión está en las notas del Release. En PowerShell:

```powershell
Get-FileHash .\FFBoost-Setup-1.1.0.exe -Algorithm SHA256
```

Tiene que coincidir letra por letra con el de las notas. Si no coincide, no lo ejecutes.

## Qué mide y qué no

FFBoost muestra RAM disponible, cantidad de ajustes activos y la estabilidad de tu mouse, y dice "no concluyente" cuando un cambio no se puede afirmar. No promete menos procesos ni cifras de mejora: medilo en tu PC.

---
Hecho por **Quorzant**.
