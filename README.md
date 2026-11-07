# Resorte de torsión en espiral (v1.4)

Simulador de un **resorte espiral de torsión**: calcula el par frente al giro, con contacto entre espiras y fricción.

> **Estado:** hipótesis de ingeniería / modelo de juguete. No es un resultado experimental ni un dispositivo.

## Cómo usarlo
Abre `index.html` en el navegador (o por GitHub Pages). Mueve los controles y observa los resultados en vivo. No necesita instalación.

## Qué modela
- Elástica de la barra (viga flexible), contacto por penalización.
- Fricción de Coulomb con retorno de mapeo; modelo de adhesión por umbral de enlace; modo de deslizamiento plano.

## Límites (importante)
- La fricción es de juguete: el par cambia ≤ 4 % hasta μ = 0.5 a −6 rad, con convergencia **parcial** tras el contacto.
- Sin datos reales de fricción/adhesión (a escala MEMS/NEMS dominan efectos que no se modelan).
- Falta convergencia estricta (conjunto activo) y tope exterior de tamaño finito. Conviene consultarlo con un experto en MEMS/NEMS.

## Documentación
Informe asociado: `informe-resorte-espiral.docx` (si está en esta carpeta).

## Autoría
Mathias Zárate Amenero, Lima, Perú. Desarrollado junto con Claude (Anthropic): el código y los informes se elaboraron con asistencia de IA y los supuestos físicos están declarados arriba.
