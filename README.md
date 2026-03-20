# VAADI-OCR Resources

This repository contains the resources and code used for generating the VAADI-OCR dataset.

---

## 🔤 Fonts Used in This Work

The dataset is generated using the following Kashmiri/Arabic script fonts:

- **Noto Nastaliq Urdu** (`NotoNastaliqUrdu-Medium.ttf`)
- **Gulmarg Nastaleeq** (`Gulmarg Nataleeq_2013.ttf`)
- **Naskh Arabic** (`NaskhArabic.ttf`)
- **Narqalam** (`Narqalam.ttf`)

These fonts provide stylistic diversity for robust OCR evaluation.

---

## ⚙️ Noise Augmentation Code

The dataset uses a synthetic noise pipeline to simulate real-world document degradation.

### Applied Effects

- Gaussian Blur  
- Yellow Tint (aging effect)  
- Bleed-through Simulation  
- Salt & Pepper Noise  
- Gaussian Noise  
- Contrast Adjustment  
- Vignette Effect  

