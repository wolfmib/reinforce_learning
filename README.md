# reinforce_learning
Repeat: pick web site useful example for practice

---


## convert jupyter notebook to pdf:
---
- mac-air:
    - install the mactex (download ~ 4.5G)
    - export path: , check ja_export_ooo.sh for the path location
    - jupyter nbconvert 01_Q_learning-Improve.ipynb --to pdf
    - the markdown-cell is not fully-support: 
        - have check the web-site, but didn't work anyway:
            1. [Suggest_convert_to_latex_than_to_PDF](https://github.com/jupyter/nbconvert/issues/552)
            1. [the latex to pdf command](https://askubuntu.com/questions/166679/how-can-i-convert-a-tex-file-to-a-pdf-via-the-command-line)

- mac-pro:
    - start to install first, (download link, Jean will prepare the gitlab link for you)





## Gitlab repo in the following device:
- mac-pro
- mac-air

## Vriatual Env setting:
---
- virtualenv --system-site-packages -p python3 ~/.ja_reinforecement_learning_lab
- source ja_init_game_simulation.sh
- python3 -m pip install --upgrade pip



## 01-Diving deeper into Reinforcement Learning with Q-Learning
---
[Link](https://www.freecodecamp.org/news/diving-deeper-into-reinforcement-learning-with-q-learning-c18d0db58efe/)


01_Q_learning-Improve.ipynb 01_Q_learning.ipynb 
- Fini la Q-Learning for FrozenLake:
    - Basic one: ___01_Q_learning.ipynb___
    - Advanced one: ___01_Q_learning-Improve.ipynb___


## 02-Deep-Q-Learning Doom

- Follow the [link](https://github.com/mwydmuch/ViZDoom/blob/master/doc/Building.md#macos_deps)
- source ja_init_virtual_env
- brew install cmake boost sdl2 wget
- brew cask install julia
- pip3 install vizdoom
- Success installed dans ma mac-book-air
- add sys.path.append in ipython.configure in mac-air:
    1. ipython profile create
    1. cd /Users/johnny_hung/.ipython/profile_default/
    1. vi ipython_config.py
        - 
----------
35 c.InteractiveShellApp.exec_lines = [
36             'import sys; sys.path.append("/Users/johnny_hung/.ja_reinforecement_learning_lab/lib/python3.6/site-packages")'
37             ]
-----------
- you are good to go with import vizdoom automatically when opening the jupyter notebook.  

  

 




 
