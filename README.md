# 🤗 Hugging Face Learning Notebooks

A collection of hands-on tutorial notebooks exploring different areas of
machine learning using Hugging Face libraries, Gradio, and Diffusers.

---

## 📚 Notebooks

### 1. 🔊 Audio Models in Hugging Face
**File:** `Audio Models in Hugging Face.ipynb`

Explores audio processing and models using Hugging Face Transformers.

**Topics covered:**
- Loading pretrained audio models from Hugging Face Hub
- Speech recognition (ASR) with Wav2Vec2 / Whisper
- Audio classification tasks
- Text-to-speech (TTS) models
- Processing audio with the `datasets` library

---

### 2. 🎨 Diffusers Library
**File:** `Diffusers library.ipynb`

Introduction to the Hugging Face `diffusers` library for image generation.

**Topics covered:**
- What diffusion models are and how they work
- Loading and running Stable Diffusion pipelines
- Text-to-image generation
- Tweaking inference parameters (steps, guidance scale, seed)
- Saving and displaying generated images

---

### 3. 🖥️ Gradio + Hugging Face
**File:** `gradio-hugging face.ipynb`

Building interactive web demos with Gradio and deploying to Hugging Face Spaces.

**Topics covered:**
- Creating Gradio interfaces (`gr.Interface`, `gr.Blocks`)
- Connecting Gradio to Hugging Face models
- Input/output components (image, text, audio, sliders)
- Deploying apps to Hugging Face Spaces
- Sharing demos with a public link

---

### 4. 📝 Text Generation
**File:** `text generation.ipynb`

Exploring large language models and text generation pipelines.

**Topics covered:**
- Loading GPT-2 and other text generation models
- Using the `pipeline` API for quick inference
- Controlling generation (temperature, top-k, top-p, max length)
- Prompt engineering basics
- Comparing outputs from different models

---

### 5. 🎬 Video Models
**File:** `video models.ipynb`

Working with video understanding and generation models on Hugging Face.

**Topics covered:**
- Video classification models
- Loading and preprocessing video data
- Temporal understanding with transformers
- Running inference on video inputs
- Visualizing video model outputs

---

## 🛠️ Setup

### Run on Google Colab (recommended)
Click any notebook → click the **"Open in Colab"** badge or button.
No local setup needed.

### Run locally

```bash
# Clone the repo
git clone https://github.com/RoseMary007/hugging-face.git
cd hugging-face

# Install dependencies
pip install transformers diffusers gradio datasets torch torchvision
pip install accelerate torchaudio opencv-python

# Launch Jupyter
jupyter notebook
```

---

## 📦 Main Libraries Used

| Library | Purpose |
|---|---|
| `transformers` | Pretrained models for NLP, audio, vision |
| `diffusers` | Diffusion models for image generation |
| `gradio` | Building interactive ML demos |
| `datasets` | Loading and processing datasets |
| `torch` | Deep learning framework |
| `torchaudio` | Audio processing |
| `torchvision` | Image processing |
| `accelerate` | Optimized model training and inference |

---

## 🚀 Related Project

This learning series led to building a full **Text-to-Digit Diffusion Model**
trained on MNIST from scratch — live demo on Hugging Face Spaces:

👉 **[diffusion-model Space](https://huggingface.co/spaces/RoseMary007/diffusion-model)**

---

## 👩‍💻 Author

**RoseMary007**
- GitHub: [@RoseMary007](https://github.com/RoseMary007)
- Hugging Face: [@RoseMary007](https://huggingface.co/RoseMary007)

---

## 📄 License

This project is open source and available under the
[MIT License](LICENSE).
