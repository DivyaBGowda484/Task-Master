# Task-Master

## How To Run
1. Install `virtualenv`:
    
        $ pip install virtualenv

2. Open a terminal in the project root directory and run:

        $ virtualenv env

3. Then run the command:

        $ .\env\Scripts\activate

4. Then install the dependencies:

        $ (env) pip install -r requirements.txt

5. Finally start the web server:

        $ (env) python app.py

This server will start on port 5000 by default. You can change this in `app.py` by changing the following line to this:

```python
if __name__ == "__main__":
    app.run(debug=True, port=<desired port>)
```

## Live Demo
The app is also deployed on Replit for easy access and testing (Note: The app runs on Replit's free tier, so it may go to sleep after inactivity.)

https://66411309-994e-4d8e-863b-79cac7778c9f-00-1kr49nevipr92.pike.replit.dev/
