 Activation functions are mathematical operations applied to neurons in a neural network to introduce non-linearity. They help the network learn complex patterns and make better predictions. Below are some commonly used activation functions:

---

## 1. Sigmoid
- *Formula:* f(x) = 1 / (1 + e^(-x))
- *Range:* (0, 1)
- *Pros:* Good for probabilities.
- *Cons:* Causes vanishing gradients for very large or small values.

---

## 2. Tanh (Hyperbolic Tangent)
- *Formula:* f(x) = (e^x - e^(-x)) / (e^x + e^(-x))
- *Range:* (-1, 1)
- *Pros:* Zero-centered, which helps optimization.
- *Cons:* Still suffers from vanishing gradients.

---

## 3. ReLU (Rectified Linear Unit)
- *Formula:* f(x) = max(0, x)
- *Range:* [0, ∞)
- *Pros:* Fast and widely used, reduces vanishing gradient problem.
- *Cons:* Can cause "dying ReLU" (neurons stuck at 0).

---

## 4. Leaky ReLU
- *Formula:*  
-
f(x) = x if x > 0
f(x) = α * x if x ≤ 0 (α is a small constant, e.g., 0.01
- *Range:* (-∞, ∞)  
- *Usage:* Fixes the “dying ReLU” problem by allowing small negative values.  
- *Limitation:* Requires tuning of the parameter α.

---
