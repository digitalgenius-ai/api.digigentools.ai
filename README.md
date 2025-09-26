# api.digigentools.ai
Web Api Project for Gen AI Tools

## How to Setup

1. **Create a Python virtual environment**  
    ```bash
    python -m venv myenv
    ```

2. **Activate the virtual environment**  
    - On Windows:
      ```bash
      myenv\Scripts\activate
      ```
      OR 
      ```bash
      myenv\Scripts\activate.ps1
      ```
      OR 
      ```bash
      myenv\Scripts\activate.bat
      ```
    - On macOS/Linux:
      ```bash
      source myenv/bin/activate
      ```

3. **Install dependencies**  
    ```bash
    pip install -r requirements.txt
    ```

4. **Run the FastAPI app**  
    ```bash
    uvicorn main:app --reload
    ```

5. **Open FastAPI Swagger docs**  
    Visit [http://localhost:8000/docs](http://localhost:8000/docs) in your browser.
