# STATY.AI


**STATY.AI offers a user-friendly interface for downloading and running open access Large Language Models (LLMs) locally on your PC.**  

   

**Getting started**

   

**1. Python Installation**    
> [!TIP]
> Make sure to check the checkbox labeled "Add Python ... to PATH" during the installation process.  
  This ensures you can easily run Python commands from your terminal later.  
  T
  
   Install Python 3.11.8 from: https://www.python.org/downloads/release/python-3118/  
   Windows: Select `Windows installer (64-bit)`  
   macOS: Select `macOS 64-bit universal2 installer`
   > [!TIP]
   > The Python installation files are at the bottom of the page in the section 'Files'

**2. VSC Installation**   
       Install Visual Studio Code by pressing the big blue button from: https://code.visualstudio.com/

**3. Ollama Installation**  
   Install Ollama from: https://ollama.com/

**4. Get 'STATY.AI' ready**   
  Download 'STATY.AI' to a folder on your PC. Open VSCode. Go to the `File` menu, select `Open Folder`, and then navigate to the project folder you just created.
  ` „Do you trust the Author of this Folder” – click “yes”`

**5. create a virtual environment**   
   Locate the `Terminal` panel in VScode (usually at the bottom of the window). If it's not visible, go to the View menu and select Terminal. Type the following command in the terminal to create a virtual environment:

   Windows: `py -3 -m venv .venv`

   macOS:`python3 -m venv .venv source `
   > [!TIP]
   > Don't foget the dot before the second venv `.venv`

**6. Activate the virtual environment**   
  Type the following command in the terminal:

  Windows:`.venv\Scripts\activate`

  macOS:`source .venv/bin/activate` 

**7. Install all application components**   
   Type the following command in the terminal: `pip install -r requirements.txt`

**8. Run STATY.AI**   
   Type the following command in the terminal: `streamlit run staty_ai.py`

> [!TIP]
> Windows: In case of a policy challenge type the following command in the terminal:   
`Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser`








