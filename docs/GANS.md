# An Overview of GANs
Modern generative and reasoning models mainly evolve around three landmark deep learning architectures: GANs, Diffusion Models, and Transformers.

## A closer look at GANs 🤖🎨
Generative Adversarial Networks (GANs), introduced by Goodfellow et al. in 2014, consist of **two neural networks**:

GAN = Generator + Discriminator

- **Generator (G):** Creates synthetic data from random noise in a **latent space**.
- **Discriminator (D):** Distinguishes real data from synthetic data.

### How GANs Work 🔄

1. **Noise → Data:**  
   G takes random noise and transforms it into synthetic data.

2. **Evaluation:**  
   D receives both real and synthetic data and tries to identify which is which.

3. **Adversarial Feedback:**  
   D’s feedback helps G improve. The process continues until **equilibrium** is reached.

4. **Equilibrium:**  
   When D can no longer tell real from fake, assigning **0.5 probability** to both, the synthetic data is indistinguishable from real data.

### Applications 🌟

- **Automotive:** Simulate real-world scenarios for autonomous vehicle testing.  
- **Entertainment:** Generate digital characters & realistic environments for films & games.  
- **Art:** Create entirely new, AI-generated artworks.  

GANs continue to evolve, offering **better quality, control, and performance** every year.
