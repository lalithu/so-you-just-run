---
layout: post
title: "Visualizing Waves"
date: 2024-05-30 00:00:01 +0530
author: Lalith Uriti
categories: Science
---

# Defining a Wave

```python
def traveling_wave_fn(x, t, direction=1, amp=1, wave_len=(2 _ np.pi), w=1):
k = (2 _ np.pi) / wave_len

    wave_ = amp * np.sin((k * x) - (direction * (w * t)))

    return wave_
```

{% include wavea.html %}

# Two Identical Waves Travelling in Opposite Directions

{% include waveab.html %}

# Resultant Standing Wave

{% include waves.html %}
