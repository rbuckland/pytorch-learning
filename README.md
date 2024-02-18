# pytorch-learning

## Setup of this repo

1. setup poetry and add libraries 
 * `virtualenvs.in-project = true` is on, as that creates a `.venv` which is industry standard.
   (VScode searches for it, and the developer of the python extensions polled the twitterverse :-D 51% <project>/.venv (other forms the reset))


```
poetry init
poetry add torch matplotlib pandas numpy ipykernel
```
