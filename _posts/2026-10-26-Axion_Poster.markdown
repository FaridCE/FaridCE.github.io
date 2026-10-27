---
layout: post
title: "Axion Poster (Spanish)"
date: 2025-10-30 04:02:16 -0600
categories: inflation, cosmology
---

# El universo de los axiones: de la física de partículas a la cosmología

*Día de Puertas Abiertas — Instituto de Física, UNAM*

Con motivo del **Día de Puertas Abiertas del Instituto de Física de la UNAM (IFUNAM)**, presento este póster de divulgación sobre los **axiones**, partículas hipotéticas que podrían ayudarnos a comprender algunos de los problemas más interesantes de la física moderna.

## ¿Qué es un axión?

El axión fue propuesto originalmente como una solución al **problema de CP fuerte**, una pregunta que surge en la cromodinámica cuántica (QCD), la teoría que describe las interacciones entre quarks y gluones.

Esta teoría permite una violación de la simetría CP que produciría un momento dipolar eléctrico en el neutrón. Sin embargo, los experimentos muestran que dicho momento es extremadamente pequeño. ¿Por qué la naturaleza parece conservar esta simetría con tanta precisión?

El mecanismo de **Peccei–Quinn** ofrece una posible respuesta: introduce una nueva simetría cuya ruptura espontánea da origen a un campo, el axión, que evoluciona hacia una configuración donde se conserva CP.

## Un universo de axiones

Más allá del problema original de QCD, existen generalizaciones conocidas como **partículas similares al axión** (*Axion-Like Particles*, ALPs). Estos campos aparecen en diversos modelos teóricos y podrían desempeñar un papel importante en cosmología.

En particular, se han estudiado como posibles candidatos para explicar tres fenómenos:

- **Inflación y fluctuaciones del fondo cósmico de microondas (CMB):** los campos tipo axión podrían participar en la inflación primordial y generar fluctuaciones cuánticas que dejarían huellas observables en el CMB.
- **Materia oscura:** los axiones podrían constituir parte o la totalidad de la materia oscura que influye gravitacionalmente en la formación de galaxias.
- **Energía oscura:** campos tipo axión extremadamente ligeros podrían evolucionar lentamente y contribuir a la expansión acelerada del universo.

Aunque estas posibilidades siguen siendo objeto de investigación, muestran cómo una idea originada en la física de partículas puede abrir nuevas preguntas sobre la historia y composición del cosmos.

## El póster

En este póster presento una breve introducción al problema de CP fuerte, el mecanismo de Peccei–Quinn y algunas de las conexiones más interesantes entre los axiones y la cosmología.

La pregunta central es: **¿podría una nueva familia de partículas ayudarnos a comprender tanto las interacciones fundamentales como la evolución del universo?**

<br>

<button onclick="togglePreview('previewBtn1', 'pdfContainer1', 'pdfFrame1', '{{ '/assets/posters/Poster_DPA.pdf#view=FitH' | relative_url }}')"
  id="previewBtn1"
  style="background-color: #2D3E50; color: white; border: none; padding: 8px 16px; border-radius: 6px; cursor: pointer; font-weight: bold; margin: 10px 0;">
  Show Poster
</button>

<div id="pdfContainer1" style="height: 0; opacity: 0; overflow: hidden; transition: opacity 0.3s ease;">
  <iframe id="pdfFrame1" src="" width="100%" height="700px" style="border: 1px solid #ccc;"></iframe>
</div>

<script>
function togglePreview(btnId, containerId, frameId, pdfPath) {
  var container = document.getElementById(containerId);
  var frame = document.getElementById(frameId);
  var btn = document.getElementById(btnId);

  if (container.style.height === "0px" || container.style.height === "") {
    frame.src = pdfPath;
    container.style.height = "710px";
    container.style.opacity = "1";
    btn.innerHTML = "Hide Poster";
    btn.style.backgroundColor = "#d73a49";
  } else {
    container.style.height = "0px";
    container.style.opacity = "0";
    btn.innerHTML = "Show Poster";
    btn.style.backgroundColor = "#2D3E50";
    frame.src = "";
  }
}
</script>

---

**Para profundizar:** D. J. E. Marsh, *Axion Cosmology*, Physics Reports **643**, 1–79 (2016). [arXiv:1510.07633](https://arxiv.org/abs/1510.07633).