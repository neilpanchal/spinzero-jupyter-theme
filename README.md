### Spinzero - Jupyter Notebook Theme
Personal theme that I use for Jupyter notebooks. It uses a chromatic palette similar to the popular solarized theme with excellent contrast against white background. Classic latex font - "Computer Modern" is used for body text to give it a professional/academic look. No official jupyter logo. Includes dataframe table formatting, matplotlib style, and a number of aesthetic updates to ensure clean, sophisticated and purposeful presentation. If you find errors or ways to improve, please submit and issue or a pull-request.

### Installation instructions
Create a new directory `".jupyter/custom"`[1] in your home folder if it doesn't exist.
Copy the contents of this repository to the `.jupyter/custom"` folder such that `custom.css` file is located at `.jupyter/custom/custom.css`. If this method doesn't work, see [2].

[1] Custom directory can be found by launching Jupyter notebook and using the following commands:
```
import jupyter_core
jupyter_core.paths.jupyter_config_dir() + '\\custom'
```
For more information, see this Stackoverflow post: ![Link](https://stackoverflow.com/questions/32156248/how-do-i-set-custom-css-for-my-ipython-ihaskell-jupyter-notebook)

[2] Launch jupyter notebook with a python kernel and type the following commands:
```
from distutils.sysconfig import get_python_lib
print(get_python_lib())
```
Try placing the custom.css such that it is located at:
`/Users/Username/miniconda3/lib/python3.7/site-packages/notebook/static/custom/custom.css`

For more information, see this Github issue: ![Link](https://github.com/jupyter/jupyter/issues/295)

### Color Palette
```
	      Hex			RGB
YELLOW      = #BA9600			[181,137,0  ]
ORANGE      = #BA5400			[186,84	,0  ]
RED         = #D43132			[176,47	,48 ]
MAGENTA     = #D14187			[209,65	,135]
VIOLET      = #793AC7			[144,89	,212]
BLUE        = #007AD0			[15 ,134,217]
CYAN        = #009489			[0  ,163,151]
GREEN       = #688A0A			[104,138,10 ]
GREEN       = #A05200			[156,98	,48 ]

BACKGROUND  = #F8F8F8			[248,248,248]
DARK GRAY   = #383838			[56 ,56 ,56 ]
MID GRAY    = #828282			[130,130,130]
LIGHT GRAY  = #D8D8D8			[216,216,216]

```

### Screenshot

![Notebook Design Screenshot](https://github.com/neilpanchal/spinzero-jupyter-theme/raw/master/screenshot_v2.0.png "Notebook Design")
