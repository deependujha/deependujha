### Hi there 👋

![](https://komarev.com/ghpvc/?username=deependujha&color=green)

Core-team member of <a href="https://github.com/Lightning-AI/litdata" target="_blank">LitData</a>

```diff
+ Deep Learning ❤️
+ Wanna be Rustacean
+ Cloud Computing (AWS primarily)
```

<p align="center">

<img width="53%"  src="https://github-readme-stats.vercel.app/api?username=deependujha&count_private=true&show_icons=true&include_all_commits=false&hide_border=true&hide_title=true" />

<br>
  
<img width="53%"  src="https://github-readme-streak-stats.herokuapp.com/?user=deependujha&hide_border=true" />
  

</p>


<!--
---------------
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

---

3. **Pytorch model summary**

```python
from torchinfo import summary

model = ConvNet()
batch_size = 16
summary(model, input_size=(batch_size, 1, 28, 28))
```

```
================================================================================================================
Layer (type:depth-idx)          Input Shape          Output Shape         Param #            Mult-Adds
================================================================================================================
SingleInputNet                  [7, 1, 28, 28]       [7, 10]              --                 --
├─Conv2d: 1-1                   [7, 1, 28, 28]       [7, 10, 24, 24]      260                1,048,320
├─Conv2d: 1-2                   [7, 10, 12, 12]      [7, 20, 8, 8]        5,020              2,248,960
├─Dropout2d: 1-3                [7, 20, 8, 8]        [7, 20, 8, 8]        --                 --
├─Linear: 1-4                   [7, 320]             [7, 50]              16,050             112,350
├─Linear: 1-5                   [7, 50]              [7, 10]              510                3,570
================================================================================================================
Total params: 21,840
Trainable params: 21,840
Non-trainable params: 0
Total mult-adds (M): 3.41
================================================================================================================
Input size (MB): 0.02
Forward/backward pass size (MB): 0.40
Params size (MB): 0.09
Estimated Total Size (MB): 0.51
================================================================================================================
```



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
