# Generative AI Practicals

A hands-on laboratory repository for studying and implementing the fundamental concepts, architectures, and applications of **Generative Artificial Intelligence (GenAI)**.

The practicals are organized from foundational Generative AI concepts to advanced topics such as Transformers, RAG, GANs, Diffusion Models, Neural Style Transfer, and open-source model fine-tuning and deployment.

---

## 🎯 Course Objective

> **To study the concepts, architectures, techniques, and applications of Generative Artificial Intelligence through practical implementation.**

---

## 🧪 List of Experiments

| No. | Experiment                                                                                                                 | Skill Level | CO  | Marks |
| --: | -------------------------------------------------------------------------------------------------------------------------- | ----------- | --- | ----: |
|   1 | To study the concept of Generative Artificial Intelligence and compare Generative Models with Discriminative Models.       | S1          | CO1 |     2 |
|   2 | To implement probabilistic modeling techniques and generate synthetic data samples.                                        | S2          | CO1 |     2 |
|   3 | To study the architecture of transformer-based language models and generate text using pretrained models.                  | S2          | CO3 |     2 |
|   4 | To design effective prompts and implement Retrieval Augmented Generation to reduce hallucination in large language models. | S3          | CO2 |     3 |
|   5 | To study the architecture and training process of Generative Adversarial Networks.                                         | S3          | CO3 |     3 |
|   6 | To generate images using diffusion-based generative models such as Stable Diffusion.                                       | S4          | CO3 |     3 |
|   7 | To generate artistic content using neural style transfer and GAN-based models.                                             | S3          | CO4 |     3 |
|   8 | To train, fine-tune, and deploy open-source generative AI models.                                                          | S3          | CO4 |     3 |

---

# 📚 Experiment Details

## 01 — Generative AI vs Discriminative Models

### Aim

To study the concept of Generative Artificial Intelligence and compare Generative Models with Discriminative Models.

### Topics

* Introduction to Generative AI
* Generative Models
* Discriminative Models
* MNIST Dataset
* Classification
* Image Reconstruction
* Generative vs Discriminative comparison

### Expected Learning

Students understand the fundamental difference between:

```text
Discriminative → Decide / Classify
Generative     → Create / Generate
```

---

## 02 — Probabilistic Modeling and Synthetic Data

### Aim

To implement probabilistic modeling techniques and generate synthetic data samples.

### Topics

* Probability distributions
* Gaussian distribution
* Sampling
* Probability Density Functions
* Synthetic data generation
* Data visualization

### Expected Learning

Students understand how probability distributions can be used to model data and generate synthetic samples.

---

## 03 — Transformer-Based Language Models

### Aim

To study the architecture of transformer-based language models and generate text using pretrained models.

### Topics

* Transformer architecture
* Attention mechanism
* Self-attention
* Tokens
* Embeddings
* Pretrained language models
* Text generation

### Expected Learning

Students understand the basic architecture of Transformers and perform text generation using a pretrained model.

---

## 04 — Prompt Engineering and RAG

### Aim

To design effective prompts and implement Retrieval Augmented Generation to reduce hallucination in large language models.

### Topics

* Prompt Engineering
* Large Language Models
* Embeddings
* Vector databases
* Document retrieval
* RAG pipeline
* Hallucination
* Context-grounded generation

### RAG Pipeline

```text
Documents
    ↓
Chunking
    ↓
Embeddings
    ↓
Vector Database
    ↓
Retriever
    ↓
Relevant Context
    ↓
LLM
    ↓
Answer
```

---

## 05 — Generative Adversarial Networks

### Aim

To study the architecture and training process of Generative Adversarial Networks.

### Topics

* GAN architecture
* Generator
* Discriminator
* Adversarial training
* Real vs Fake data
* Synthetic image generation

### GAN Architecture

```text
Random Noise
     ↓
 Generator
     ↓
Fake Image
     ↓
Discriminator
     ↓
Real / Fake
```

---

## 06 — Diffusion-Based Generative Models

### Aim

To generate images using diffusion-based generative models such as Stable Diffusion.

### Topics

* Diffusion models
* Forward diffusion
* Noise addition
* Reverse diffusion
* Denoising
* Text-to-image generation
* Stable Diffusion

### Basic Concept

```text
Image
 ↓
Add Noise
 ↓
Noisy Image
 ↓
Denoising Process
 ↓
Generated Image
```

---

## 07 — Neural Style Transfer and GAN-Based Art

### Aim

To generate artistic content using neural style transfer and GAN-based models.

### Topics

* Neural Style Transfer
* Content image
* Style image
* Feature extraction
* Artistic image generation
* GAN-based creative generation

### Basic Concept

```text
Content Image + Style Image
             ↓
      Neural Network
             ↓
      Artistic Image
```

---

## 08 — Open-Source Generative AI Models

### Aim

To train, fine-tune, and deploy open-source generative AI models.

### Topics

* Open-source models
* Hugging Face
* Model loading
* Fine-tuning
* LoRA / PEFT
* Model inference
* Deployment
* Local LLMs

### Workflow

```text
Open-source Model
       ↓
    Dataset
       ↓
    Fine-tuning
       ↓
     Testing
       ↓
    Inference
       ↓
   Deployment
```

---

# 🛠️ Technologies

The laboratory may use:

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* TensorFlow / PyTorch
* Hugging Face Transformers
* Hugging Face Diffusers
* LangChain
* FAISS / Chroma
* Streamlit
* Jupyter Notebook
* VS Code
* Git & GitHub

---

# 📂 Repository Structure

```text
generative-ai-practicals/
│
├── README.md
├── requirements.txt
│
├── 01-Generative-vs-Discriminative/
├── 02-Probabilistic-Modeling/
├── 03-Transformer-Text-Generation/
├── 04-Prompt-Engineering-RAG/
├── 05-Generative-Adversarial-Network/
├── 06-Diffusion-Models/
├── 07-Neural-Style-Transfer-GAN/
└── 08-Open-Source-GenAI/
```

Each practical contains:

```text
Practical/
├── README.md
└── source_code
```

---

# 🎓 Learning Path

```text
Fundamentals
     ↓
Probabilistic Models
     ↓
Transformers
     ↓
Prompt Engineering + RAG
     ↓
GANs
     ↓
Diffusion Models
     ↓
Creative GenAI
     ↓
Fine-tuning + Deployment
```

---

# 📈 Course Outcomes

After completing the practicals, students will be able to:

1. Explain fundamental Generative AI concepts.
2. Differentiate Generative and Discriminative Models.
3. Generate synthetic data using probabilistic techniques.
4. Understand Transformer-based language models.
5. Generate text using pretrained models.
6. Design effective prompts.
7. Implement RAG-based applications.
8. Understand GAN architecture and training.
9. Generate images using diffusion models.
10. Create artistic content using GenAI techniques.
11. Fine-tune open-source generative models.
12. Deploy basic Generative AI applications.

---

# 🚀 Getting Started

Clone the repository:

```bash
git clone https://github.com/<your-username>/generative-ai-practicals.git
```

Navigate to the repository:

```bash
cd generative-ai-practicals
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate on Windows:

```bash
venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

# 👨‍🎓 For Students

For every experiment:

1. Read the Aim.
2. Understand the concept.
3. Understand the architecture.
4. Run the implementation.
5. Observe the output.
6. Modify parameters and experiment.
7. Record observations.
8. Write the conclusion.

The objective is not only to execute the code but to **understand how Generative AI models work**.

---

# 📜 Academic Information

**Course:** Generative Artificial Intelligence Laboratory

**Repository:** `generative-ai-practicals`

**Experiments:** 8

**Purpose:** Academic / Educational

---

## ⭐ Core Idea

> **Learn the concept → Understand the architecture → Implement the model → Observe the output → Experiment → Understand Generative AI**
