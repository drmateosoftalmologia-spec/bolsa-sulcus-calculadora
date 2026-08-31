# Bolsa ⇄ Sulcus — Calculadora de ajuste de potencia de LIO

Herramienta intraoperatoria de apoyo para cirugía de cataratas: calcula la potencia final de una lente intraocular (LIO) reposicionada en el surco ciliar (sulcus) en lugar del saco capsular, incluyendo la equiparación de la constante A cuando la lente disponible pertenece a otra plataforma.

**Uso:** abrir `index.html` en cualquier navegador (celular, tablet o PC), o la versión publicada en GitHub Pages una vez habilitada: `https://<tu-usuario>.github.io/<nombre-del-repo>/`

## Qué calcula

1. **Equiparación de plataforma** — si la lente disponible para sulcus tiene una constante A distinta de la planificada, ajusta la potencia según la diferencia de constantes.
2. **Corrección posicional bolsa → sulcus** — aplica una tabla interpolada (ACD bolsa 5.20 mm / sulcus 4.70 mm) para obtener la potencia final, más una referencia cruzada con la "Regla de los Nueve".

## Fundamento científico

El desarrollo completo del algoritmo, su derivación matemática y las limitaciones están documentados en [`fundamento-cientifico.docx`](fundamento-cientifico.docx).

Referencia principal:
Suto C, Hori S, Fukuyama E, Akura J. Adjusting intraocular lens power for sulcus fixation. *J Cataract Refract Surg.* 2003;29(10):1913-7.

## Autoría

Desarrollada por el **Dr. Gerardo Mateos** (MP 33952), Córdoba, Argentina.

### Cómo citar

> Mateos G. Bolsa ⇄ Sulcus: calculadora de ajuste de potencia de LIO intraocular [Internet]. 2026. Disponible en: https://doi.org/10.5281/zenodo.22213101

## Licencia

Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0). Se permite compartir y adaptar dando crédito, sin uso comercial, y bajo la misma licencia. Ver [`LICENSE`](LICENSE).

## Advertencia clínica

Herramienta de apoyo a la decisión intraoperatoria. No reemplaza el criterio quirúrgico ni el cálculo vergencial individualizado en casos atípicos (longitud axial anómala, ausencia total de soporte capsular). Ver limitaciones en el documento de respaldo científico.
