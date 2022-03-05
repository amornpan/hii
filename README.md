# hii
Hydro-Informatics Institute (Public organization) (hii)

mkdir hii     
python3 -m venv hii
source hii/bin/activate
pip3 freeze
/Users/Anthony/hii/hii/bin/python3 -m pip install --upgrade pip
pip3 install Pillow
pip3 install kivy

goto: https://github.com/kivymd/KivyMD
git clone https://github.com/kivymd/KivyMD.git --depth 1
cd KivyMD
pip3 install .
cd demos
cd kitchen_sink/
python3 main.py 
