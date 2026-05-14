[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20174094.svg)](https://doi.org/10.5281/zenodo.20174094)

# Golden Ratio Deep Learning (Φ)    EN language
Implementation of the Golden Ratio (Φ ≈ 1.618) in deep neural networks. Comparative experiments between golden initialization and regularization versus Xavier's method, evaluating stability, convergence, and learning efficiency in PyTorch models.

This repository contains experiments conducted in Google Colab applying the **Golden Ratio (Φ ≈ 1.618)** to deep neural network architectures.  
The goal is to compare golden initialization, topological compression, and regularization with conventional methods (Xavier + Dropout 0.5), evaluating **stability and convergence**.

---

## 📌 Contents
- Implementation of **Golden Weight Initialization** (stochastic initialization based on Φ).
- Topological compression following the geometric progression Φ⁻¹.
- **Golden Dropout** (~38.2%) as an alternative to standard dropout.
- Learning rate scheduler with smooth decay based on Φ.
- Attention scaling in Transformers using Φ.
- Practical comparison with **Xavier initialization** and standard dropout (0.5).

---

## ⚙️ How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
2. Open the notebook in Google Colab.
3. Run the training using Φ initialization and compare it with Xavier.
4. Generated graphs and GIFs will be automatically saved to Google Drive.

## 📊 Main Results
- Average Loss:
  - Φ decreased from ~0.49 to ~0.15 over 10 epochs.
  - Xavier stabilized around ~0.60.
- Accuracy:
  - Φ reached peaks of ~95.26%.
  - Xavier reached ~92.53%.

Conclusion: The golden geometry accelerates convergence, stabilizes gradients, and improves generalization.

---

# Aprendizado profundo com proporção áurea (Φ)  PT language
Implementação da Proporção Áurea (Φ ≈ 1,618) em redes neurais profundas. Experimentos comparativos entre inicialização e regularização áureas versus Xavier, avaliando estabilidade, convergência e eficiência de aprendizado em modelos PyTorch.

Este repositório contém experimentos realizados no Google Colab aplicando a **Proporção Áurea (Φ ≈ 1,618)** em arquiteturas de redes neurais profundas.  
O objetivo é comparar inicialização, compressão topológica e regularização áureas com métodos convencionais (Xavier + Dropout 0.5), avaliando **estabilidade e convergência**.

---

## 📌 Conteúdo
- Implementação da **Golden Weight Initialization** (inicialização estocástica baseada em Φ).
- Compressão topológica seguindo progressão geométrica Φ⁻¹.
- **Golden Dropout** (~38,2%) como alternativa ao dropout padrão.
- Scheduler de aprendizado com decaimento suave baseado em Φ.
- Escalonamento de atenção em Transformers usando Φ.
- Comparação prática com inicialização **Xavier** e dropout padrão (0.5).

---

## ⚙️ Como usar
1. Clone este repositório:
   git clone https://github.com/<seu-usuario>/<nome-do-repo>.git
   
2. Abra o notebook no Google Colab.

3. Execute o treinamento com inicialização Φ e compare com Xavier.

4. Os gráficos e GIFs gerados serão salvos automaticamente no Google Drive.

## 📊 Resultados principais
- Perda média (Loss):
   - Φ reduziu de ~0.49 para ~0.15 em 10 épocas.
   - Xavier estabilizou em torno de ~0.60.
- Acurácia:
   - Φ atingiu picos de ~95.26%.
   - Xavier atingiu ~92.53%.

Conclusão: a geometria áurea acelera a convergência, estabiliza gradientes e melhora a generalização.
