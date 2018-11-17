# Chess AI Workshop
UCI AI Club Chess AI  

## Download

Use the "Clone or download" and click "Download ZIP".

Save the folder to your computer.

Open a Terminal (OSX/LINUX) or CMD (WINDOWS) and follow the below instructions.

## Prerequisites

We have provided a requirements.txt for you to setup your **python3 environment.**

Change directories to flappy bird folder
```
cd /path/to/chess/folder/
```

First off, create your virtual environment by entering the below command

### Mac OSX / Linux

If on OSX or Linux, enter the following into terminal
```
python3 -m venv chessenv

source chessenv/bin/activate

pip install -r requirements.txt
```

### Windows

If on windows, you may have to run the following in order to install the virtual environment tool

```
pip3 install virtualenv
```

Then, you have to run the following to make and activate the venv
```
virtualenv chessenv

chessenv\Scripts\activate.bat

pip install -r requirements.txt
```
### RUN (When code is completed)

Once you have got your venv activated, run the following command

```
cd PyChess
python chess.py
```
