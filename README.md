
# Job Application Form

It is a basic Job Application form created using **Python** and **Flask** which takes the user input and whenever user clicks on submit it stores the user information in **SQLite** database and sends an email to the employer regarding the information of the candidate.
- **Bootstrap** was used to add styling the form.
- With **Dockerfile** you can create a **Docker Image** of the app.
- To use this code you have to create an app on your google account and copy paste its password in variables.py file.
- Link to create app in google account [https://myaccount.google.com/apppasswords](https://myaccount.google.com/apppasswords)



## Run Locally

Install requirements

```bash
  pip install --no-cache-dir -r requirements.txt
```

Start the server

```bash
  python app.py
```

### Run with Docker

Build Docker Image
```bash
  docker build -t flask-form .
```

Run the docker image
```bash
  docker run -p 5000:5000 flask-form:latest
```


## Screenshots

![ss1](https://github.com/AkramExp/flask-form/blob/main/screenshots/ss1.png)

