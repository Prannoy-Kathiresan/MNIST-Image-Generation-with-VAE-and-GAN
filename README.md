# 🧠 Generative Modeling on MNIST: VAE vs GAN

This project compares two generative models — **Variational Autoencoders (VAE)** and **Generative Adversarial Networks (GAN)** — for learning and generating handwritten digits from the **MNIST dataset**.

> 📁 Includes: `MNIST_VAE.ipynb` and `MNIST_GAN.ipynb`

---

## 🎯 Project Overview

- Trained and evaluated **VAE** and **GAN** architectures using PyTorch
- Explored **latent space representations** and **sample generation**
- Compared reconstruction quality, sample realism, and training dynamics
- Generated handwritten digit images from noise/latent vectors

---

## 🔍 Key Differences

| Feature            | VAE                         | GAN                         |
|--------------------|------------------------------|------------------------------|
| Architecture       | Encoder–Decoder              | Generator–Discriminator     |
| Training Objective | ELBO (reconstruction + KL)   | Minimax (adversarial loss)  |
| Output Style       | Blurry but smooth            | Sharp but possibly unstable |
| Latent Sampling    | Probabilistic                | Deterministic (from noise)  |

---

## 🧪 Files

- `MNIST_VAE.ipynb` — Trains and visualizes a Variational Autoencoder
- `MNIST_GAN.ipynb` — Implements a basic GAN with Generator + Discriminator

---

## 🖼 Sample Outputs

> You can add generated image grids or t-SNE visualizations here!

---

## ⚙️ How to Run

1. Install dependencies:
```bash
pip install torch torchvision matplotlib
```

2. Open either notebook in Jupyter or Colab:
```bash
jupyter notebook MNIST_VAE.ipynb
jupyter notebook MNIST_GAN.ipynb
```

3. Run all cells to train and generate samples.

---

## 📚 References

- Kingma & Welling (2014) — *Auto-Encoding Variational Bayes*  
- Goodfellow et al. (2014) — *Generative Adversarial Nets*  
- PyTorch & torchvision official tutorials

---

## 📬 Contact

Connect on [LinkedIn](https://www.linkedin.com/in/prannoy-kathiresan) for questions or collaboration!
