# Simple Python Keylogger with Pynput. Sending data to a server.
## This code DOES NOT promote or encourage any illegal activities! The content in this document is provided solely for educational purposes and to create awareness!

## This is a proof of concept and could be improved on in a lot of ways.

1. To run this code use `git clone https://github.com/davidbombal/python-keylogger.git`
2. Run the command `cd\python-keylogger`
3. Create Virtual Environment in Windows. Using command `<python_path>\py -m venv keylogger_env`
4. Run command `keylogger_env\Scripts\activate`
5. Run the command `pip install -r requirements.txt` to install all the packages required in your virtual environment.
6. Run `py keylogger.py` this will run the program.

## Create your own Pyinstaller bootloader (It is often times more likely to avoid Anti-Virus but not guaranteed)
### Build your own bootloader.

1. We want to create a new bootloader for Pyinstaller that uses the Microsoft C/C++ compiler. You can download the Community Edition
here `https://visualstudio.microsoft.com/thank-you-downloading-visual-studio/?sku=Community&channel=Release&version=VS2022&source=VSFeaturesPage&passive=true&tailored=cplus&cid=2031#cplusplus`
2. Run the downloaded `VisualStudioSetup.exe` file.
3. `git clone https://github.com/pyinstaller/pyinstaller.git`
4. Run `pip install wheel`
5. Change directory into the `\pyinstaller\bootloader` folder of the cloned repository.
6. Build the bootloader using command `./waf distclean all`
7. Run `py setup.py install`
