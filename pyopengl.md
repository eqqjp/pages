# PyOpenGL

PyOpenGL は、Python で OpenGLUT に相当する機能を利用するものです。

PyOpenGL を利用するには、C言語レベルで、OpenGLUT が利用できる環境を整える必要があります。

その上で、以下のように、PyOpenGL をインストールします。

	pip install PyOpenGL

※ Windows 11 の WSL と WSLg 上で Ubuntu 20.04 が動作している環境では、前述のように pip ではなく、必要に応じて以下のようにインストールします。

    sudo apt install build-essential xorg-dev
    sudo apt install libopengl-dev freeglut3-dev
    sudo apt install python3-opengl

python で以下のプログラムを実行してみます。

    python3 pyopengl.py

このプログラムは、新たにウィンドウを作成し、ティーポットを三次元表示します。  
![teapot](img/pyopengl-teapot0.png)

左ボタンのマウス操作により、回転させることができます。  
![teapot rotation](img/pyopengl-teapot1.png)
![teapot rotation](img/pyopengl-teapot2.png)

中央ボタンのマウス操作により、ズームさせることができます。  
![teapot zoom](img/pyopengl-teapot3.png)
![teapot zoom](img/pyopengl-teapot4.png)

右ボタンのマウス操作により、移動させることができます。  
![teapot move](img/pyopengl-teapot5.png)
![teapot move](img/pyopengl-teapot6.png)
