
# KazakhVC_Resutls_SVC

This repository contains experiment results and inference outputs for **Kazakh Voice Conversion (VC)** using the [so-vits-svc-fork](https://github.com/voicepaw/so-vits-svc-fork) project.

---

## 📂 Folder Structure

```
KazakhVC_Resutls_SVC/
├── Apps(named)/         # Audio outputs (inference results: converted wav files, etc.)
      ├──model files/    # (300pt 500pt 2000pt so on depending on epoch stages)
          ├──config.json
          ├──D_epochNumber.pt
          ├──G_epochNumber.pt
      ├──Dataset/        # For some apps uploaded datasets used to train models       
├── README.md            # This file
```

---

## ✅ Hugging Face Model Link

All trained `.pt` model checkpoint files will be uploaded to Hugging Face.

👉 **Hugging Face Model Repository Link:**  
[LINK](https://huggingface.co/woop1e/KazakhVC_models)

---

## ✅ About so-vits-svc-fork

- **Project:** [so-vits-svc-fork](https://github.com/voicepaw/so-vits-svc-fork)  
- **Description:**  
A real-time voice conversion toolkit that allows transforming the voice of a source speaker to sound like a target speaker.

---

## ✅ Example Output Files

The `/Speaker` folder will contain:

- Inference output `.wav` files


## ✅ License

IDK what have to be here XD

---

## ✅ Author

**woop1e**
