---
description: Describes the gravity function.
---

# Gravity

The gravity constant, $g$, varies between game modes.

## Cube

In the cube mode, there are two forms of gravity:

* Standard
* Inverted (Upside-Down)

The _Inverted_ mode works identically to the standard mode, simply substituting the acceleration constant for its additive inverse, $-g$. The standard acceleration is $-72b/s^2$, which can be then computed by block with respect to time with the following formula:

$$
h_{\mathrm{b}}(t) = h_0 - \int_{0}^{t} \int_{0}^{\tau} 79 \; \mathrm{d}\phi \mathrm{d}\tau = h_0 - \frac{79t^2}{2} = h_0 - 39.5t^2
$$

Which is obtained by integrating the acceleration twice, as the acceleration is the second derivative. Here, $h_0$ represents the initial height in blocks. One can compute change in generic height using the following conversion metric:

$$
1\cdot \mathrm{b}^1 = 30\cdot \Delta^1
$$

Thus, the height in terms of the $\Delta$ unit is

$$
h_\Delta(t) = h_0 - 1185t^2
$$



Where $h_0$ is in terms of the Delta unit.

Similarly, the height in pixels is

$$
h_{\mathrm{p}}(t)=h_0 - 5332.5t^2
$$

With $h_0$ in pixels.

## Ship

In the ship mode, there are two modes of gravity:

* Normal
* Inverse

The inverse simply inverts the acceleratory constant with $-g$ instead of $g$.

The standard acceleration in the ship mode is $-25b/s^2$, which is considerably slower than the cube. The formulae are given:

$$
h_{\mathrm{b}}(t) = h_0 = 12.5t^2
$$

$$
h_{\Delta}(t) = h_0 - 375t^2
$$

$$
h_{\mathrm{p}}(t) = h_0 - 1687.5t^2
$$

