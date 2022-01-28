from flask import Flask

app = Flask(__name__)

@app.route('/')
def index():
    return 'HELLO WORLD'

app.run()
 Running on http://127.0.0.1:5000/
