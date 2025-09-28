---
title: core
---



> Fill in a module description here


::: {#cell-2 .cell 0='d' 1='e' 2='f' 3='a' 4='u' 5='l' 6='t' 7='_' 8='e' 9='x' 10='p' 11=' ' 12='c' 13='o' 14='r' 15='e'}
``` {.python .cell-code}
!pip install nbdev
```

::: {.cell-output .cell-output-stdout}
```
Requirement already satisfied: nbdev in /opt/anaconda3/lib/python3.13/site-packages (2.4.5)
Requirement already satisfied: packaging in /opt/anaconda3/lib/python3.13/site-packages (from nbdev) (24.2)
Requirement already satisfied: fastcore>=1.8.0 in /opt/anaconda3/lib/python3.13/site-packages (from nbdev) (1.8.11)
Requirement already satisfied: execnb>=0.1.12 in /opt/anaconda3/lib/python3.13/site-packages (from nbdev) (0.1.14)
Requirement already satisfied: astunparse in /opt/anaconda3/lib/python3.13/site-packages (from nbdev) (1.6.3)
Requirement already satisfied: ghapi>=1.0.3 in /opt/anaconda3/lib/python3.13/site-packages (from nbdev) (1.0.8)
Requirement already satisfied: watchdog in /opt/anaconda3/lib/python3.13/site-packages (from nbdev) (4.0.2)
Requirement already satisfied: asttokens in /opt/anaconda3/lib/python3.13/site-packages (from nbdev) (3.0.0)
Requirement already satisfied: setuptools in /opt/anaconda3/lib/python3.13/site-packages (from nbdev) (72.1.0)
Requirement already satisfied: build in /opt/anaconda3/lib/python3.13/site-packages (from nbdev) (1.3.0)
Requirement already satisfied: PyYAML in /opt/anaconda3/lib/python3.13/site-packages (from nbdev) (6.0.2)
Requirement already satisfied: ipython in /opt/anaconda3/lib/python3.13/site-packages (from execnb>=0.1.12->nbdev) (8.30.0)
Requirement already satisfied: wheel<1.0,>=0.23.0 in /opt/anaconda3/lib/python3.13/site-packages (from astunparse->nbdev) (0.45.1)
Requirement already satisfied: six<2.0,>=1.6.1 in /opt/anaconda3/lib/python3.13/site-packages (from astunparse->nbdev) (1.17.0)
Requirement already satisfied: pyproject_hooks in /opt/anaconda3/lib/python3.13/site-packages (from build->nbdev) (1.2.0)
Requirement already satisfied: decorator in /opt/anaconda3/lib/python3.13/site-packages (from ipython->execnb>=0.1.12->nbdev) (5.1.1)
Requirement already satisfied: jedi>=0.16 in /opt/anaconda3/lib/python3.13/site-packages (from ipython->execnb>=0.1.12->nbdev) (0.19.2)
Requirement already satisfied: matplotlib-inline in /opt/anaconda3/lib/python3.13/site-packages (from ipython->execnb>=0.1.12->nbdev) (0.1.6)
Requirement already satisfied: prompt-toolkit<3.1.0,>=3.0.41 in /opt/anaconda3/lib/python3.13/site-packages (from ipython->execnb>=0.1.12->nbdev) (3.0.43)
Requirement already satisfied: pygments>=2.4.0 in /opt/anaconda3/lib/python3.13/site-packages (from ipython->execnb>=0.1.12->nbdev) (2.19.1)
Requirement already satisfied: stack-data in /opt/anaconda3/lib/python3.13/site-packages (from ipython->execnb>=0.1.12->nbdev) (0.2.0)
Requirement already satisfied: traitlets>=5.13.0 in /opt/anaconda3/lib/python3.13/site-packages (from ipython->execnb>=0.1.12->nbdev) (5.14.3)
Requirement already satisfied: pexpect>4.3 in /opt/anaconda3/lib/python3.13/site-packages (from ipython->execnb>=0.1.12->nbdev) (4.8.0)
Requirement already satisfied: wcwidth in /opt/anaconda3/lib/python3.13/site-packages (from prompt-toolkit<3.1.0,>=3.0.41->ipython->execnb>=0.1.12->nbdev) (0.2.5)
Requirement already satisfied: parso<0.9.0,>=0.8.4 in /opt/anaconda3/lib/python3.13/site-packages (from jedi>=0.16->ipython->execnb>=0.1.12->nbdev) (0.8.4)
Requirement already satisfied: ptyprocess>=0.5 in /opt/anaconda3/lib/python3.13/site-packages (from pexpect>4.3->ipython->execnb>=0.1.12->nbdev) (0.7.0)
Requirement already satisfied: executing in /opt/anaconda3/lib/python3.13/site-packages (from stack-data->ipython->execnb>=0.1.12->nbdev) (0.8.3)
Requirement already satisfied: pure-eval in /opt/anaconda3/lib/python3.13/site-packages (from stack-data->ipython->execnb>=0.1.12->nbdev) (0.2.2)
```
:::
:::


::: {#cell-3 .cell 0='h' 1='i' 2='d' 3='e'}
``` {.python .cell-code}
from nbdev.showdoc import *
```

::: {.cell-output .cell-output-error}

::: {.ansi-escaped-output}
```{=html}
<pre><span class="ansi-red-fg">---------------------------------------------------------------------------</span>
<span class="ansi-red-fg">ModuleNotFoundError</span>                       Traceback (most recent call last)
<span class="ansi-cyan-fg">Cell</span><span class="ansi-cyan-fg"> </span><span class="ansi-green-fg">In[5]</span><span class="ansi-green-fg">, line 2</span>
<span class="ansi-green-fg">      1</span> <span style="font-style:italic;color:rgb(95,135,135)">#| hide</span>
<span class="ansi-green-fg">----&gt; </span><span class="ansi-green-fg">2</span> <span style="font-weight:bold;color:rgb(0,135,0)">from</span><span style="color:rgb(188,188,188)"> </span><span class="ansi-blue-fg ansi-bold">nbdev</span><span class="ansi-blue-fg ansi-bold">.</span><span class="ansi-blue-fg ansi-bold">showdoc</span><span style="color:rgb(188,188,188)"> </span><span style="font-weight:bold;color:rgb(0,135,0)">import</span> *

<span class="ansi-red-fg">ModuleNotFoundError</span>: No module named 'nbdev'</pre>
```
:::

:::
:::


::: {#cell-4 .cell 0='e' 1='x' 2='p' 3='o' 4='r' 5='t'}
``` {.python .cell-code}
def foo(): pass
```
:::


::: {#cell-5 .cell 0='h' 1='i' 2='d' 3='e'}
``` {.python .cell-code}
import nbdev; nbdev.nbdev_export()
```
:::


