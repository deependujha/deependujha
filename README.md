<h1 align="center"> Hi there 👋 I'm Deep 🤠</div>
<br/>
<p align="center">
  <img src="./tom-cowboy.jpg" />
</p>

---

[![Deependu Jha profile views](https://u8views.com/api/v1/github/profiles/76887609/views/day-week-month-total-count.svg)](https://u8views.com/github/deependujha)

---

## Codes I use often but don't remember:

1. **`PyTorch device (MPS, CUDA, CPU)`**

```python
import torch

# Get cpu, gpu or mps device for training.
device = (
    "cuda"
    if torch.cuda.is_available()
    else "mps"
    if torch.backends.mps.is_available()
    else "cpu"
)
print(f"Using {device=}")
```

---

2. **`Matplotlib multiple plot`**

```python
import numpy as np
import matplotlib.pyplot as plt

x = np.arange(1,11)
y = 3*x+2
z = x**2+5

# --------------------------------------------

fig, axs = plt.subplots(nrows=2, ncols=2, figsize=(12, 4))
axs[0][0].plot(x, y)
axs[0][1].plot(x, z)
axs[1][0].plot(x, z)
axs[1][1].plot(x, y)

plt.show()
```

---

3. **`Argument Parser in python`**

```python
import os
from argparse import ArgumentParser

if __name__ == "__main__":
    # enable CLI commands
    parser = ArgumentParser()
    parser.add_argument('--data', type=str,
                        default=os.getcwd() + '/example_dataset')
    parser.add_argument('--max_steps', type=int, default=100)
    parser.add_argument('--lr', type=float, default=1e-3)
    parser.add_argument('--batch_size', type=int, default=2)
    args = parser.parse_args()
    
    print(f"{args=}")
    print(f"batch size: {args.batch_size}")
```


<!--
**deependujha/deependujha** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
