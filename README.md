# 🏷️ AI Label

> Check whether a file shows **signs of being AI-generated** (C2PA content credentials, known generator markers) and generate the **AI-content transparency disclosure** the EU AI Act (art. 50) requires. Runs 100% in your browser — nothing is uploaded.

<sub>[🇪🇸 Español abajo](#-español)</sub>

---

## What it does
- 🔍 **Verify**: reads a file's metadata locally and flags markers of AI generation — provenance standards (**C2PA / Content Credentials, SynthID**) and known tools (Midjourney, DALL·E, Stable Diffusion, ChatGPT, Firefly, ElevenLabs…).
- 🏷️ **Label**: generates a plain-language **disclosure** (per AI Act art. 50) + a **machine-readable JSON label** you can attach to your content.

## Honest limitations
- Detection is **heuristic** (it scans metadata for markers), **not** a cryptographic verification. Full C2PA verification needs the official [`c2pa` SDK](https://github.com/contentauth).
- **Absence of markers does NOT prove content isn't AI** — metadata can be stripped. Treat results as orientation, not proof.

## Use
Open `index.html`. Drop a file to verify, or fill the form to generate a label. All local.

## License
[MIT](LICENSE) © 2026 DataFlow Elegance

---

## 🇪🇸 Español
**AI Label** comprueba si un archivo tiene **señales de haber sido generado por IA** (credenciales C2PA, marcadores de generadores conocidos) y genera la **declaración de transparencia** que exige el AI Act (art. 50). **100% en tu navegador**, no se sube nada.

- 🔍 **Verificar**: lee los metadatos en local y marca señales de IA (C2PA/SynthID, Midjourney, DALL·E, ChatGPT, ElevenLabs…).
- 🏷️ **Etiquetar**: genera una **declaración** en lenguaje claro (art. 50) + una **etiqueta JSON legible por máquina** para adjuntar a tu contenido.

**Límites honestos:** la detección es **heurística** (busca marcadores en metadatos), no verificación criptográfica — para eso está el [SDK c2pa](https://github.com/contentauth). Y **que no haya marcadores NO prueba que no sea IA** (los metadatos se borran fácil).

**Uso:** abre `index.html`. Todo local.

---

<div align="center">
Hecho con ❤️ por <a href="https://github.com/romebkkk">DataFlow Elegance</a> · <a href="https://dataflowelegance.es">dataflowelegance.es</a>
</div>
