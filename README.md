# GitHub Actions 入門與進階
- 講師
- Peng Xiao
- Senior Cloud DevOps Engineer 麥兜搞IT
## 1. GitHub Actions建構塊和元件
  ### 1. GitHub Actions是什麼？

  ### 2. GitHub Actions Components

  ### 3. 影片播放器設置

  ### 4. 創建我們第一個Github Actions

  ### 5. GitHub Action Runners

  ### 6. Jobs的串列與平行

  ### 7. 一起做一個練習

  ### 8. 使用Actions

  ### 9. GitHub Actions Context
    - **github vailable Images**
    :::success
    github vailable Images. 
    :::

    |**Image**   	         | **YAML Label**   	          | **Included Software**  |                                                                **Score**                                                          	|
    |:----------------------:|:------------------------------:|:----------------------:|:--------------------------------------------------------------------------------------------------------------------------------:	|
    |**Ubuntu 24.04**   	 | ubuntu-latest or ubuntu-24.04  | ubuntu-24.04 	       | <input type="checkbox" enable/> :+1: <input   type="checkbox" enable/> :heavy_minus_sign: <input   type="checkbox" enable/> :-1:  	|
    |**Ubuntu 22.04**   	 | ubuntu-22.04	                  | ubuntu-22.04  	       | <input type="checkbox" enable/> :+1: <input   type="checkbox" enable/> :heavy_minus_sign: <input   type="checkbox" enable/> :-1:  	|
    |**Windows Server 2025** | windows-latest or windows-2025 | windows-2025	       | <input type="checkbox" enable/> :+1: <input   type="checkbox" enable/> :heavy_minus_sign: <input   type="checkbox" enable/> :-1:  	|
    |**Windows Server 2022** | windows-2022  	              | windows-2022     	   | <input type="checkbox" enable/> :+1: <input   type="checkbox" enable/> :heavy_minus_sign: <input   type="checkbox" enable/> :-1:  	|
      
    - **github context**
    https://docs.github.com/en/actions/reference/workflows-and-actions/contexts#context-availability

## 2. 如何建構和編排簡單和複雜的workflow
  ### 10. What is Event?

  ### 11. 多个Events Trigger

  ### 12. Event Filters和Activity Types

  ### 13. Pull Request Events

  ### 14. Schedule Events
    資源:
      - https://crontab.guru/

  ### 15. Cancel and skip Workflows

## 3. 如何將workflow連接到事件並配置事件詳細信息
  ### 16. 示範專案準備
    資源:
    - python-sha256-(16. 示範專案準備).zip

  ### 17. 準備GitHub Workflow

  ### 18. Upload Job Artifacts
    資源:
    - https://github.com/marketplace/actions/upload-a-build-artifact


  ### 19. Upload Job Artifacts補充

  ### 20. Download Artifacts in Workflow
    資源:
    - https://github.com/marketplace/actions/download-a-build-artifact

## 4. 如何有條件地運行workflow或steps
  ### 21. GitHub Action Default Environment Variables
   資源:
   - https://docs.github.com/en/actions/how-tos/write-workflows/choose-what-workflows-do/use-variables#default-environment-variables

  ### 22. 在Workflow中定義和使用Environment Variables

  ### 23. Repository Secrets

  ### 24. Repository Variables

  ### 25. 什麼是Environment？

  ### 26. 一個Project Demo
    資源:
    - https://www.youtube.com/watch?v=L6LcW22CB6A&list=PLfQqWeOCIH4CGhmL--Te6idRngw5TrJVS
    - https://github.com/oh-my-docker/net-box

## 5. 如何管理環境變數和密碼
  ### 27. 本章介紹

  ### 28. 示範專案準備
   資源:
   - python-pytest-github-action-(28. 示範專案準備).zip

  ### 29. Job的依賴關係
    資源:
    - https://www.youtube.com/playlist?list=PLfQqWeOCIH4CGhmL--Te6idRngw5TrJVS

  ### 30. Job狀態檢查

  ### 31. Step狀態檢查(1)

  ### 32. Step狀態檢查(2)

  ### 33. Matrix的使用(1)

  ### 34. Matrix的使用(2)

  ### 35. Matrix的使用(3)

## 6. 如何處理workflow結果、輸出和輸入
  ### 36. 本章介紹

  ### 37. 本章專案準備
    資源:
    - fastapi-mongodb-demo-(37. 本章專案準備).zip

  ### 38. 在runner直接使用Docker指令

  ### 39. 使用Service Container

  ### 40. 直接在container裡運行job

## 7. 如何建立和分享actions
  ### 41. 本章介紹

  ### 42. 環境準備
    資源:
    - fastapi-mongodb-demo-(42. 環境準備).zip

  ### 43. 建立一個本地composite actions

  ### 44. 建立一個可以分享的action

  ### 45. 把action發佈到marketplace

  ### 46. Docker container actions

  ### 47. Create JavaScript Actions
    資源:
    - javascript-actions-master-(47. Create JavaScript Actions).zip
    - https://docs.github.com/en/actions/tutorials/create-actions/create-a-javascript-action
# Project GIT 
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
