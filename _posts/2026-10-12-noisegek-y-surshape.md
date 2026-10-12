---
title: "## NOISEGEK y SURSHAPE"
date: 2026-10-12
tipo: bitácora
published: true
---
Llevaba años juntando aparatos para hacer ruido (mixers, el TEYUN Q-12, el MONOLOGUE) y usando software de otros. Estos meses hice mis propias herramientas. Son tres programas sobre un mismo motor.

**NOISEGEK**: plugin de efecto (VST3, CLAP y JSFX para REAPER), Windows. Toma una señal y la procesa: módulos de distorsión, generadores de ruido (blanco, rosa, browniano, dust, LFSR), filtro, compuerta secuenciada, carriles de modulación, realimentación, seguidor de envolvente y apertura estéreo.

**NOISEGEK GEN**: la versión instrumento. Sin entrada de audio; responde a notas MIDI, con envolvente ADSR por voz y modo afinado o sin afinar. El motor de ruido pasa de procesar a generar.

**SURSHAPE:** diseño sonoro offline, al estilo del Composers Desktop Project. No es en tiempo real: arrastras un audio, encadenas procesos en una grilla y renderizas a un archivo nuevo. Nada se sobrescribe, y cada render guarda de dónde salió y con qué parámetros.

Los tres corren sobre un mismo motor en Rust y son software libre (GPL); el código está a pedido.

Muestra: [youtu.be/VLltabBvkRo](https://youtu.be/VLltabBvkRo)