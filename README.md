# MAPSDT

[![Downloads](https://pepy.tech/badge/MAPSDT)](https://pepy.tech/project/MAPSDT)
[![OS](https://img.shields.io/badge/OS-windows-red)](https://windows.com)
[![Python version](https://img.shields.io/badge/python-3.7.0-brightgreen.svg)](https://www.python.org) 
 
**Team Leader** : [Chan-gyu](https://github.com/wjk1011)  **Team Member** : [Yu-ha](https://github.com/jiyuha)


**Installation**

The easiest way to install MAPSDT framework is to download it from [PyPI](https://pypi.org/project/MAPSDT).
```
pip install MAPSDT==0.1.5
```

**Usage**
```python
MAPSDT(df,
       tree=None,
       split_portion=0.3,
       max_depth=5,
       Genetic_Progrmmaing=False,
       init_size=50,
       max_generations=50,
       save=True
       )
```

**Outcomes**

![image](https://user-images.githubusercontent.com/70674000/141953129-3ed83e44-561f-4508-8c58-b97f9600eb45.png)


**Model save and restoration**

You can save your trained models. This makes your model ready for transfer learning.

```python
MAPSDT(save=True)
```
