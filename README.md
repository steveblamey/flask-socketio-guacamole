# flask-socketio-guacamole

A flask-socketio based web service to embed a remote terminal/desktop in your web browser with help from guacd.

## Usage

- You need a guacamole server (guacd), follow the steps given by the official documentation: 
https://guacamole.apache.org/doc/gug/installing-guacamole.html or run with docker "guacamole/guacd".

- Get this app running:

```
$ git clone https://github.com/steveblamey/flask-socketio-guacamole.git

$ python -m venv env

$ source env/bin/activate

(env) pip install -r requirements.txt
```
 
- Set the guacd host and port in config.py (defaults to 127.0.0.1:4832)

- `(env) python app.py` and access http://localhost:5000 in your browser

## Notes

flask-socketio-guacamole is licensed under the MIT License.
Thanks to [pyguacamole](https://github.com/mohabusama/pyguacamole) and 
[guacamole-client/guacamole-common-js](https://github.com/apache/guacamole-client/tree/master/guacamole-common-js).
