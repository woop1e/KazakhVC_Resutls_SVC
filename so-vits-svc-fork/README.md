
# KazakhVC_Resutls_SVC

This repository contains experiment results and inference outputs for **Kazakh Voice Conversion (VC)** using the [so-vits-svc-fork](https://github.com/voicepaw/so-vits-svc-fork) project.

---

## 📂 Folder Structure

```
KazakhVC_Resutls_SVC/
├── my_wavs/             # Audio outputs (inference results: converted wav files, etc.)
├── checkpoints/         # (Optional) Checkpoints (model files, if needed)
├── README.md            # This file
```

---

## ✅ Hugging Face Model Link

All trained `.pt` model checkpoint files will be uploaded to Hugging Face.

👉 **Hugging Face Model Repository Link:**  
[PLACE_HUGGINGFACE_LINK_HERE](#)

*(Once you create the repository on Hugging Face, replace this line with the actual link.)*

---

## ✅ About so-vits-svc-fork

- **Project:** [so-vits-svc-fork](https://github.com/voicepaw/so-vits-svc-fork)  
- **Description:**  
A real-time voice conversion toolkit that allows transforming the voice of a source speaker to sound like a target speaker.

---

## ✅ Example Output Files

The `/my_wavs` folder will contain:

- Inference output `.wav` files
- Different experiments (f0 methods, speakers, noise levels, etc.)

You can organize the outputs as:

```
my_wavs/
├── speaker_A_to_B/
├── speaker_C_to_D/
├── different_f0_methods/
└── ...
```

---

## ✅ How to Create a Hugging Face Model Repository

If you want to store large `.pt` model files:

1. Go to: https://huggingface.co/
2. Sign in or create an account
3. Click your profile picture → **New Repository**
4. Choose:
   - **Repository name:** Example: `Kazakh-VC-Models`
   - **Type:** Model Repository
   - **Visibility:** Public (or Private)
5. After creation, you will get a link like:

```
https://huggingface.co/woop1e/Kazakh-VC-Models
```

6. Upload `.pt` model files manually (drag-and-drop), or via `git-lfs` if needed.

---

## ✅ Optional: Upload to Hugging Face via Git LFS (for large models)

If your model `.pt` files are large:

```bash
git lfs install
git clone https://huggingface.co/woop1e/Kazakh-VC-Models
cd Kazakh-VC-Models
cp /path/to/your_model/*.pt .
git add .
git commit -m "Add first Kazakh VC model"
git push
```

*(For this, make sure you have `git-lfs` installed: [Git LFS Installation](https://git-lfs.github.com/))*

---

## ✅ License

You can add a license file here (e.g., MIT, Apache 2.0) depending on your preference.

---

## ✅ Author

**woop1e**
