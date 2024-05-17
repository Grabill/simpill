# simpill
## How to start
Clone the repo with the following command:
```
git clone --recurse-submodules https://github.com/Grabill/simpill.git
```
## Available npm commands
### `npm run git`
Update 2 submodules.
### `npm run sync`
Run `npm install` on all `package.json` files. Should be run after updating submodules.
### `npm run start`
Start both backend and frontend.

## Run python backend (within the backend folder)
```
cd suggestion
```
Create a virtual environment
```
python -m venv venv
```
Activate the virtual environment
```
source venv/bin/activate
```
Install the required packages
```
pip install -r requirements.txt
```
Run the script
```
python suggestion.py
```
