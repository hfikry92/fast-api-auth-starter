# A starter project for FastAPI including JWT-AUTH


1. Make sure you create a virtual environment
   
    ```sh
    $ python3 -m venv myenv && source myenv/bin/activate
    ```

2. Install requirements
    ```sh
    (myenv)$ pip install -r requirements.txt
    ```
   
3. Create a .env file and add the following:
   ```sh
   secret=DUMMY_VALUE_HERE____REPLACE_IT
   algorithm=HS256
   ```
   
4. run app and check http://localhost:8081/docs#/
    ```sh
    (myenv)$ python main.py
    ```
   
