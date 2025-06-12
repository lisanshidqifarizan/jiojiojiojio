
# How to use
## Windows
- Make a environtment: `python3 -m venv venv`
- Activate venv: `venv\Scripts\activate`
- Install dependencies: `pip3 install -r requirements.txt`
- Extract model in folder `models/model_NUMBER.7z.001` and so on.
- Run the programs `cartoonGAN.py` file.
## Linux & macOS
- Make a environtment: `python3 -m venv venv`
- Activate venv: `source venv/bin/activate`
- Install dependencies: `pip install -r requirements.txt`
- Extract model:
	- Install p7zip-full (kalau belum ada):
		`sudo apt install p7zip-full` # For Linux (Debian/Ubuntu)
		`brew install p7zip` # FormacOS
- Extract: `7z x model_0.7z.001 -o./models`
- Run the programs: `python3 cartoonGAN.py --model_number 0`