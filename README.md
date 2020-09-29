# Google Drive Download Folder Python

## Setup:
1. Create `client_secrets.json` following [this tutorial](https://learndataanalysis.org/google-drive-api-in-python-getting-started-lesson-1/)
   
2. Setup virtual environment
(Linux only)
```sh
python3.8 -m venv env
source env/bin/activate
```

2. Install `requirements.txt`
```sh
pip install -U pip
pip install -r requirements.txt
```

3. Run script

```sh
python main.py 'SOURCE_FOLDER_NAME' 'TARGET_FOLDER_PATH[OPTIONAL, DEFAULT=./]'
```