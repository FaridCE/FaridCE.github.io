---
layout: page
title: "Manuscripts"
author: "A. F. Cantun"
---

Welcome to my library. You can view or download my latest work below.

### Pre-prints

* **Regularization of cosmological correlators.**
<br>

<button onclick="togglePreview()" id="previewBtn" style="background-color: #2ea44f; color: white; border: none; padding: 8px 16px; border-radius: 6px; cursor: pointer; font-weight: bold; margin: 10px 0;">
  Show Preview
</button>

<div id="pdfContainer" style="height: 0; opacity: 0; overflow: hidden; transition: opacity 0.3s ease;">
  <iframe id="pdfFrame" src="" width="100%" height="600px" style="border: 1px solid #ccc;"></iframe>
</div>

<script>
function togglePreview() {
  var container = document.getElementById("pdfContainer");
  var frame = document.getElementById("pdfFrame");
  var btn = document.getElementById("previewBtn");
  
  // The specific PDF path with the "Fit Horizontal" parameter
  var pdfPath = "{{ '/assets/manuscripts/RCC.pdf#view=FitH' | relative_url }}";

  if (container.style.height === "0px" || container.style.height === "") {
    // Show it
    frame.src = pdfPath; // Load PDF only when clicked to ensure correct zoom
    container.style.height = "610px";
    container.style.opacity = "1";
    btn.innerHTML = "Hide Preview";
    btn.style.backgroundColor = "#d73a49";
  } else {
    // Hide it
    container.style.height = "0px";
    container.style.opacity = "0";
    btn.innerHTML = "Show Preview";
    btn.style.backgroundColor = "#2ea44f";
    frame.src = ""; // Unload to save memory
  }
}
</script>

---
