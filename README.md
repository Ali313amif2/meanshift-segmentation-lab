# Mean Shift Color Image Segmentation Lab

An interactive, client-side web laboratory for **5D Mean Shift color image segmentation** $(x, y, R, G, B)$. Built to visually compare up to 5 independent parameter configurations simultaneously in a single row without requiring any local installation.

### Live Demo
**[Launch Interactive Simulator](https://ali313amif2.github.io/meanshift-segmentation-lab/)**

---

### Key Features
- **5 Simultaneous True-Color Outputs:** Independently tune spatial bandwidth ($h_s$), range bandwidth ($h_r$), convergence threshold ($th$), max iterations, and kernel type (Gaussian / Uniform) side by side.
- **Controlled Single-Variable Experiments:** One-click presets to isolate the effect of $h_s$, $h_r$, $th$, iteration count, and kernel type.
- **Visual & Quantitative Comparison:** Split-screen curtain slider, RGB color difference map, PSNR (dB), MAE, smoothing ratio, and cluster count metrics.
- **100% Client-Side Privacy:** All 5D Mean Shift calculations run locally in the browser via Web Workers; uploaded images are never sent to any server.
- **Presentation & Export Ready:** Focus presentation mode plus individual PNG and 6-panel comparison sheet downloads.

### Tech Stack
- HTML5 Canvas, JavaScript (Web Workers + Disjoint Set Union mode merging), CSS3.

---

### معرفی کوتاه (فارسی)
شبیه‌ساز تعاملی بخش‌بندی تصویر رنگی با الگوریتم **Mean Shift** در فضای ۵ بعدی مکانی-رنگی. با این ابزار می‌توانید تصویر دلخواه خود را بارگذاری کرده و تأثیر پارامترهای $h_s$، $h_r$، $th$ و نوع کرنل را به‌صورت هم‌زمان در ۵ خروجی مجزا با یکدیگر مقایسه و تحلیل کنید.
