# LMS-manager

This script helps you log in to your LMS account and enter the currently running session, all in a second.
</br>
## Install packages
First, make sure Python is installed on your system; Open the terminal and run:
```
python --version
```
You should get a message like `"Python 3.8.5."` otherwise, download it from [here.](https://www.python.org/downloads/) </br>

Before anything, it is good to check that you are working with the most recent version of pip:
```
pip install --upgrade pip
```
With pip installed, the installation is straightforward, run:
```
pip install -r req.txt
```

Finally, download `chromedriver` from [here](https://chromedriver.storage.googleapis.com/98.0.4758.80/chromedriver_win32.zip). After extraction, copy `chromedriver.exe` to the `C:\` drive. </br></br>
**Note:** Get latest [chromedriver](https://chromedriver.chromium.org/downloads) version matching your [Google Chrome](https://www.google.com/chrome/) version.
</br>
## Get started
Create file `config.py` and put the following properties in it:
```
USERNAME = 'YOUR_USER_NAME'
PASSWORD = 'YOUR_PASSWORD'
```
So, the project structure will be:
```
|-- meeting.py
|-- main.py
|-- config.py
|-- req.txt
```

Now run:
```
python main.py
```

**Note:** Make sure you run this script when a meeting begins.
Otherwise, you have to enter the session yourself or run `main.py` again. </br>
**Note:** Once you install packages, you can double-click on `main.py` to run the script next time.
