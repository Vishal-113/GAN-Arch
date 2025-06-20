
## 🎓 Student Information
- **Name**: Chinni VeearvenkatasivanagarajuGovind
- **Student ID**: 700771324
- **Course**: Neural Network & Deep Learning


1. GAN-Arch
# Generative Adversarial Networks (GANs) - Adversarial Process

## Overview
Generative Adversarial Networks (GANs) operate through an adversarial process involving two neural networks: the **generator** and the **discriminator**. Their competition drives improvements in both models.

## Goals of Each Component
### 1. Generator (G)
- Takes random noise as input and generates synthetic data (e.g., images).
- Aims to produce data that is indistinguishable from real data.
- Improves by learning to fool the discriminator.

### 2. Discriminator (D)
- Acts as a binary classifier, distinguishing between real and generated data.
- Trains to correctly classify real data as real and fake data as fake.
- Improves by learning to detect the generator’s flaws.

## Adversarial Training Process
- The **discriminator** is trained on both real and fake data, adjusting its parameters to improve classification accuracy.
- The **generator** is trained to minimize the discriminator’s ability to distinguish fake data from real data.
- The training alternates between updating the discriminator and generator:
  1. The discriminator trains while the generator remains fixed.
  2. The generator trains while the discriminator remains fixed.
- As training progresses, the generator produces increasingly realistic data, making it harder for the discriminator to differentiate.
- 
## Optimization Process
- The generator tries to **maximize** the probability that the discriminator classifies its output as real.
- The discriminator tries to **minimize** classification errors by correctly distinguishing real from fake data.
- This adversarial process leads to a **MinMax optimization**, where the generator and discriminator continuously refine their abilities until the generator produces highly realistic data.
2.# AI Harm: Representational Harm

## Overview
Representational harm occurs when AI systems reinforce stereotypes or misrepresent certain groups, leading to unfair portrayals and societal biases.

## Hypothetical Application: AI-Powered Hiring Assistant
An AI-powered hiring assistant may:
- **Underrepresent certain groups** by favoring resumes that match biased historical hiring patterns.
- **Reinforce stereotypes** by associating certain job roles with specific demographics.

For example, if past successful software engineers were predominantly male, the AI might rank female candidates lower, even if equally qualified.

## Harm Mitigation Strategies
1. **Bias Auditing and Diverse Training Data**
   - Regularly audit the AI model for biases.
   - Train the model on diverse datasets with balanced demographic representation.

2. **Human Oversight and Fairness Constraints**
   - Implement human review processes to ensure fair AI-generated rankings.
   - Apply fairness constraints to prevent discriminatory patterns.



