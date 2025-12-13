# TEST

# git 
   ```bash
    git add -A
    git commit -m '20251213-001-modify -README'
    git push

    git tag -a tag-20251213-001-modify-README -m "20251213-001-modify -README"
    git push origin tag-20251213-001-modify-README
    

# Setup Project
  - (Recommended) Install Python 3.12.x (We use 3.12.8) from the official Python website and create virtual environment
    ```bash
    # On mac/linux
    python3.12 -m venv venv
    # or
    python3 -m venv venv
    # On Windows 
    python -m venv venv
    # or
    py -3.12 -m venv venv

    # On mac/linux
    source venv/bin/activate
    # On windows
    Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
    ./venv/Scripts/activate.bat

  - (Required) Install the required libraries
    ```bash
    pip install -r requirements.txt
   
  