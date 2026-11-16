# MUSEOGRAFICA — IA Museográfica

Experiencias museográficas integrales generadas con IA, dentro de MUDELAR, el Museo de las Realidades.

Escribe un tema — por ejemplo, un museo de Queen — y se genera un museo completo: galerías virtuales, exposiciones con fichas museográficas, imágenes, video y audio, guiado por Canon Iko.

## Qué hay en este repo

- `index.html` — MVP de la IA Museográfica (página estática, se abre en el navegador)
- `README.md` — este archivo

## Motor / código base

MuseOS (`xew33o-source/museOS`) es el código base y motor de MUDELAR: app en React + TypeScript, servidor y migraciones de base de datos. Este repo es el producto independiente IA Museográfica, versionado aparte desde el inicio.

## Cómo probarlo

Abre `index.html` en el navegador y pide un museo, por ejemplo Queen, Frida Kahlo o la llegada a la Luna.

Queen, Frida y la Luna vienen con datos reales curados. Cualquier otro tema se arma con la plantilla didáctica de MuseOS y se marca como borrador.

## Estado

MVP rudimentario. Sin API pública todavía: MuseOS no expone una API pública, así que el motor de generación corre dentro de la página. La audioguía usa la síntesis de voz del dispositivo.
