# Motion Detection Game (Super Mario)

This is an awesome project using opencv to detect motions to trigger key-press signals.
The demo video was using the classic Super Mario to showcase the program.
(you could play it here: https://supermario-game.com/)

Original project link：https://github.com/BadagalaAdarsh/Super_Mario

## What I modified

On line 30 in ```main.py```, make the image flip, it's easier for me to control my motion on mirror image.
```Python
image = cv2.flip(image, 1)
```

In ```controls.py``` switch the keys ```a``` and ```d```, so that it would follow the change with the flipped mirror image.


## Download this repo

On your machine, open the terminal in your target directory and use following command to clone.
```buildoutcfg
git clone https://github.com/linbeta/Super_Mario.git
```

Make sure your Python interpreter and venv is set up correctly.

[!image](how_to/select_interpreter.png)

[!image](how_to/venv_setting.png)


## Install the dependencies

run the command below:
```buildoutcfg
pip install -r requirements.txt
```

And that's it! Have Fun

## Notice

It would be a little annoying if you place the text cursor on the wrong place. 😂
It's better if you click on any place before you run this program.

## My Demo Video

[image](how_to/mario_demo ‐ Made with Clipchamp.gif)

