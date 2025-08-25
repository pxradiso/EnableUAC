# ⚡ EnableUAC

[![Made with ❤️ by pxradise](https://img.shields.io/badge/made%20with-%E2%9D%A4-red?style=for-the-badge)](https://github.com/pxradise)  
[![Platform: Windows 10/11](https://img.shields.io/badge/platform-Windows%2010%2F11-blue?logo=windows&logoColor=white&style=for-the-badge)](#)  
[![License: MIT](https://img.shields.io/badge/license-MIT-brightgreen?style=for-the-badge)](#)
![Demo EnableUAC](https://github.com/pxradiso/EnableUAC/raw/main/demo.gif)
---

## 🖥️ What is EnableUAC?  
**EnableUAC** is a lightweight script that restores and enables **User Account Control (UAC)** on Windows.  
Ideal if UAC has been **disabled, corrupted, or misconfigured**.
---

## ⚙️ How it works  
- **Administrator privileges are required** to run the script.  
- The script automatically restores UAC to its **default configuration**.  
- By default, UAC is set to **Option 4 — Always Notify**, the **highest security level**, prompting whenever apps attempt system changes.  
- After enabling UAC, you'll be prompted to **restart your PC**:  
  - Press **`Y`** → Restart immediately  
  - Press **`N`** → Exit without restarting  

---

## 🧩 Supported Versions  
- Windows 10 😉  
- Windows 11 🪟  

---

## ✅ Why EnableUAC?  
Having UAC active helps you:  
- Block unauthorized system changes  
- Reduce malware risks  
- Preserve system integrity during installations  

---

## 🛠️ Requirements  
- Windows 10 or 11  
- Administrator rights  

---

## 🚀 Usage

### Option 1: Clone the repository  
1. **Navigate** to the GitHub repository and click the **“Code”** button to copy the clone URL.  
2. Open your terminal (e.g., Git Bash or PowerShell) and go to the desired directory:

    ```bash
    cd path/to/your/desired-folder
    ```

3. Run:

    ```bash
    git clone https://github.com/pxradise/EnableUAC.git
    ```

    This creates a new `EnableUAC` folder with the full project history. ([git-scm.com](https://git-scm.com/docs/git-clone?utm_source=chatgpt.com))

4. Inside that folder, if the project is compressed (e.g., ZIP), **extract** it.

5. **Right-click** the `.exe` file and select **Run as administrator**, or from File Explorer use **"Run as administrator" via context menu or ribbon**.

---

### Option 2: Download from Releases  
1. Go to the **Releases** page of the GitHub repository.  
2. Expand the **Assets** section under the desired release.  
3. Download the **EXE** or **ZIP** file.  
4. If ZIP, **extract** it.  
5. **Run the `.exe` as Administrator** to launch the script.
