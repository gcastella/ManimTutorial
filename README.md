## Mathematical animations with manim

### Installation

1. Install pycairo on windows with the following command:
    ```sh
    python -m pip install https://download.lfd.uci.edu/pythonlibs/gjr6o2id/pycairo-1.19.1-cp38-cp38-win_amd64.whl
    ```
    You can choose the wheel you need [here](https://www.lfd.uci.edu/~gohlke/pythonlibs/#pycairo).

2. [Install FFmpeg](https://www.wikihow.com/Install-FFmpeg-on-Windows).

3. Install a LaTeX distribution. [MiKTeX](https://miktex.org/download) is recommended.

4. [Install SoX](https://sourceforge.net/projects/sox/files/sox/).

5. Install manim with:
    ```
    python -m pip install manimlib
    ```
   
Verify the installation by running one of the examples:
```sh
python3 manim example_scenes.py SquareToCircle -pl
```