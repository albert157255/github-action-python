# TEST

# git 
    ```bash
    git add -A
    git commit -m '20251213-001-modify -README'
    git push

    git tag -a tag-20251213-001-modify-README -m "20251213-001-modify -README"
    git push origin tag-20251213-001-modify-README
    ```

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
    ```
  - (Required) Install the required libraries
    ```bash
    pip install -r requirements.txt
    ```
# github vailable Images
:::success
github vailable Images. 
:::

|**Image**   	         | **YAML Label**   	          | **Included Software**  |                                                                **Score**                                                          	|
|:----------------------:|:------------------------------:|:----------------------:|:--------------------------------------------------------------------------------------------------------------------------------:	|
|**Ubuntu 24.04**   	 | ubuntu-latest or ubuntu-24.04  | ubuntu-24.04 	       | <input type="checkbox" enable/> :+1: <input   type="checkbox" enable/> :heavy_minus_sign: <input   type="checkbox" enable/> :-1:  	|
|**Ubuntu 22.04**   	 | ubuntu-22.04	                  | ubuntu-22.04  	       | <input type="checkbox" enable/> :+1: <input   type="checkbox" enable/> :heavy_minus_sign: <input   type="checkbox" enable/> :-1:  	|
|**Windows Server 2025** | windows-latest or windows-2025 | windows-2025	       | <input type="checkbox" enable/> :+1: <input   type="checkbox" enable/> :heavy_minus_sign: <input   type="checkbox" enable/> :-1:  	|
|**Windows Server 2022** | windows-2022  	              | windows-2022     	   | <input type="checkbox" enable/> :+1: <input   type="checkbox" enable/> :heavy_minus_sign: <input   type="checkbox" enable/> :-1:  	|
  
