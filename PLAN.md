# Hechos estilizados del mundo de la IA

Panel de expertos Bourbaki, "El mercado laboral antes y después de OpenAI" · 3er Congreso Nacional de Ciencia de Datos · Fri Nov 20, 2026, 10:00–11:00. Panelists: Carlos Haro (Santander), Carlos Ruiz (Bourbaki), León Palafox (GBM).

## 1. How it is used
A panel, not a talk: each fact is one ~2-minute turn. If the moderator asks something else, jump to the fact that answers it. Kaldor framing: stylized facts are broad regularities stated before the theory that explains them (Kaldor 1961 listed six for growth; this deck lists six for AI).

## 2. The six facts
| # | Slide | Fact | Evidence |
|---|---|---|---|
| 01 | `h1` | La adopción es ancha y poco profunda | OpenAI users and subscribers; Menlo ≈3% pay |
| 02 | `h2` | Se abarata la tarea, no el puesto | Stanford "Canaries": adjustment via employment, not pay |
| 03 | `h3` | El ajuste cae en el primer escalón | Stanford "Canaries": −13% relative employment, ages 22–25 |
| 04 | `h4` | El valor se mueve de producir a juzgar | Author's own observation (labelled on slide) |
| 05 | `h5` | Construir parece descentralizarse; lo serio se centraliza | Ramp Glass, company-reported |
| 06 | `h6` | La calidad de la entrada pone el techo | OCR error by input quality; GlotOCR Bench |

Close (`cierre`): **el promedio engaña**; lo interesante está en la estratificación.

## 3. Sources
- Kaldor, N. (1961), "Capital Accumulation and Economic Growth", in Lutz & Hague (eds.), *The Theory of Capital*.
- OpenAI via press: 900M weekly users and 50M+ consumer subscribers (Feb 27, 2026); 1B weekly users (Aug 6, 2026). https://www.usecarly.com/blog/chatgpt-statistics/ · https://superlines.io/articles/chatgpt-statistics
- Menlo Ventures, *2025: The State of Consumer AI* (Jun 2025): ~1.8B users, ~3% pay; US survey of 5,031 adults, global extrapolated. https://menlovc.com/perspective/2025-the-state-of-consumer-ai/
- Brynjolfsson, Chandar & Chen (Aug 2025), "Canaries in the Coal Mine? Six Facts about the Recent Employment Effects of Artificial Intelligence", Stanford Digital Economy Lab, ADP payroll data. https://siepr.stanford.edu/publications/working-paper/canaries-coal-mine-six-facts-about-recent-employment-effects-artificial
- Ramp Glass (launched externally Oct 13, 2026): 323 employees, 6,500+ edits, 350+ skills; Glyman quote on shared workflows. Company-reported. https://www.implicator.ai/ramp-glass-ai-workspace-token-spending/ · https://analyticsindiamag.com/ai-news/ramps-ai-coworker-turns-employee-workflows-into-reusable-skills/
- OCR: printed text <1% CER, degraded scans 5–20% CER, https://codesota.com/browse/computer-vision/ocr-capabilities ; GlotOCR Bench (Kargaran et al., 2026): all models decline on degraded images, https://www.alphaxiv.org/abs/2604.12978
- Control pyramid (code and deterministic rules, then verification, then prose) and "every correction becomes a deterministic check": Lauren Tan (@poteto), SpaceX AI, talk on shipping with agents (2026). Her PR and revert numbers are self-reported and not on slides.
- Illustrative: the analyst job's task split (h2), the skill file (h5), the receipt (h6).
