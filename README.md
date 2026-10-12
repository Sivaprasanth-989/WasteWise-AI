# ♻️ WasteWise AI — Intelligent Waste Classification

**An AI-powered waste classification demo designed to help users identify common waste categories and encourage responsible waste disposal.**


\


> **Project type:** Academic team project — deployment, evaluation, documentation, and demonstration of an existing waste-classification application.

## 🌐 Live Demo

**Application:** [Open WasteWise AI](https://wastewise-ai-jw9keq4hkkmaj8dpisuwhb.streamlit.app/)

The application interface is deployed on Streamlit Community Cloud. Image-classification predictions still require end-to-end validation.

## 📌 Project Overview

WasteWise AI presents an image-based approach to waste classification. Users can upload a waste image and explore how a deep-learning model categorizes common waste materials.

The project is intended to demonstrate how computer vision can support waste awareness and recycling education.

## ✨ Key Features

- 🖼️ **Image input:** Upload a supported waste image.
- 🧠 **AI-based classification:** Uses a pretrained waste-classification model.
- ♻️ **Six waste categories:** Cardboard, glass, metal, paper, plastic, and trash.
- 📊 **Prediction results:** Designed to display the predicted category and associated confidence.
- 🌱 **Environmental awareness:** Encourages users to think about waste separation and responsible disposal.
- 🌐 **Web-based interface:** Built with Streamlit for browser access.

*Prediction availability and accuracy depend on successful model initialization and inference. These features should be tested against the deployed application before being considered fully verified.*

## 🛠️ Technology Stack

| Technology                | Purpose                                         |
| ------------------------- | ----------------------------------------------- |
| Python                    | Application programming                         |
| Streamlit                 | Interactive web interface                       |
| TensorFlow / Keras        | Deep-learning model execution                   |
| MobileNetV2               | Model architecture used by the existing project |
| Pillow                    | Image processing                                |
| NumPy                     | Numerical operations                            |
| Streamlit Community Cloud | Web application hosting                         |
| Git and GitHub            | Source-code hosting and version control         |

## 🧩 How It Works

1. The user opens the web application.
2. The user uploads an image of a waste item.
3. The application preprocesses the image for the model.
4. The trained model produces a category prediction.
5. The interface displays the result when inference succeeds.

## 🗂️ Repository Structure

```text
WasteWise-AI/
├── app.py
├── waste_model_v2.h5
├── class_indices_v2.json
├── requirements.txt
├── runtime.txt
├── Dockerfile
├── Waste Classification Using CNN (1).ipynb
└── README.md
```

- `app.py` — Streamlit application.
- `waste_model_v2.h5` — Existing trained model file.
- `class_indices_v2.json` — Class-index mapping.
- `requirements.txt` — Python dependencies.
- `runtime.txt` — Runtime configuration file.
- `Dockerfile` — Container configuration included in the original project.
- `Waste Classification Using CNN (1).ipynb` — Existing model-training notebook.

## 🚀 Running Locally

### Prerequisites

- Python 3.11 is recommended for compatibility with the existing dependency versions.
- Git
- Sufficient memory and disk space for TensorFlow and the trained model.

### Setup

```bash
git clone https://github.com/Sivaprasanth-989/WasteWise-AI.git
cd WasteWise-AI
python -m venv .venv
```

Activate the environment.

**Windows PowerShell:**

```powershell
.\.venv\Scripts\Activate.ps1
```

Install the dependencies and launch the application:

```bash
python -m pip install -r requirements.txt
python -m streamlit run app.py
```

Open the local URL displayed in the terminal.

*Note: Local setup may require dependency adjustments if the pinned packages are incompatible with your Python environment. The commands above have not been independently tested in a fresh environment.*

## 👥 Project Team

| Name                  | Role        | Suggested contribution                                                         |
| --------------------- | ----------- | ------------------------------------------------------------------------------ |
| **Sivaprasanth T**    | Team Leader | Project coordination, repository management, deployment setup, and integration |
| **Rupesh V P**        | Team Member | Application testing, test-image preparation, and result validation             |
| **Sivakrishnan S**    | Team Member | Technical documentation, code review, and project explanation                  |
| **Devadharshini S R** | Team Member | Research, project report, presentation, and environmental-awareness content    |

*The contribution breakdown above is a proposed allocation. Update it to reflect each member's actual work.*

## 📈 Current Project Status

- [x] Existing project files published to GitHub.
- [x] Streamlit application deployed.
- [x] Application interface loads in the browser.
- [x] Verify image classification end to end.
- [x] Validate predictions across all six categories.
- [x] Document measured performance using reproducible tests.
- [x] Confirm permission to redistribute the original code and trained model.

## 🙏 Acknowledgments

This project is based on the existing **WasteAI — Smart Waste Classifier** project by [Shweta Tiwari](https://github.com/Shwetatiwari05/WasteAI).

- Original repository: [Shwetatiwari05/WasteAI](https://github.com/Shwetatiwari05/WasteAI)
- Original hosted demo: [Waste Classifier AI](https://huggingface.co/spaces/ShwetaTiwari05/waste-classifier-ai)

The existing application, trained model, and related implementation originate from the original project. Our team's work focuses on deployment, evaluation, documentation, and academic demonstration. Please consult the original creator regarding permission to redistribute or modify the project and model.

## 📄 License

No license has been confirmed for the original project. Permission to redistribute the original code and model should be established before selecting or adding a license to this repository.

## 🌍 Our Goal

To explore how accessible AI applications can support environmental awareness, waste segregation, and responsible recycling practices.

**Built and documented by the WasteWise AI project team.**
