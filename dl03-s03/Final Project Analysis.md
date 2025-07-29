 Intuition Behind the Function *tanh(x)*

- It has an S-shaped curve , symmetric around zero.
- The output range is between –1 and +1.
- When x = 0 , the output is also 0 ⇒ indicates equilibrium, helping the mean of activations stay near zero , which improves learning speed.
- Near zero, the function behaves almost linearly ; but for large positive or negative values, the output becomes saturated(approaches ±1).

---

 Derivative of *tanh(x)*
Formula: 
f'(x) = 1 - \tanh^2(x)

- The derivative reaches its maximum at x = 0 , meaning gradients are strongest at the center.
- As  x moves away from zero , the derivative diminishes toward zero ⇒ leading to the vanishing gradient effect.

---
 Graphical Analysis *(Optional but Powerful for Intuition)*

By plotting the function and its derivative, you’ll notice:

- The main function is smooth and S-shaped.
- The derivative peaks at the center and is near zero at the edges.

