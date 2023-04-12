## ****Part Two: Practice Tools****

1. Using ***curl***, make a ***GET*** request to the *icanhazdadjoke.com* API to find all jokes involving the word “pirate”

```bash
curl "www.icanhazdadjoke.com"
```
this is a GET request but returns nothing



```bash
curl -H "Accept: application/json" https://icanhazdadjoke.com/search?term=pirate
```

this returns a JSON object

```json
{"id":"Me2wAAl31wc","joke":"Velcro\u2026 What a rip-off.","status":200}
```





2. Use ***dig*** to find what the IP address is for *icanhazdadjoke.com*
```bash
dig icanhazdadjoke.com
```
this digs the website and finds IP address and more info

```bash
dig icanhazdadjoke.com +short
```
this returns JUST the IP address




3. Make a simple web page and serve it using ***python3 -m http.server***. Visit the page in a browser.

```bash
Serving HTTP on :: port 8000 (http://[::]:8000/) ...
```
this was initialized in a different directory


```python
Traceback (most recent call last):
  File "<frozen runpy>", line 198, in _run_module_as_main
  File "<frozen runpy>", line 88, in _run_code
  File "/opt/homebrew/Cellar/python@3.11/3.11.2_1/Frameworks/Python.framework/Versions/3.11/lib/python3.11/http/server.py", line 1309, in <module>
    test(
  File "/opt/homebrew/Cellar/python@3.11/3.11.2_1/Frameworks/Python.framework/Versions/3.11/lib/python3.11/http/server.py", line 1256, in test
    with ServerClass(addr, HandlerClass) as httpd:
         ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/opt/homebrew/Cellar/python@3.11/3.11.2_1/Frameworks/Python.framework/Versions/3.11/lib/python3.11/socketserver.py", line 456, in __init__
    self.server_bind()
  File "/opt/homebrew/Cellar/python@3.11/3.11.2_1/Frameworks/Python.framework/Versions/3.11/lib/python3.11/http/server.py", line 1303, in server_bind
    return super().server_bind()
           ^^^^^^^^^^^^^^^^^^^^^
  File "/opt/homebrew/Cellar/python@3.11/3.11.2_1/Frameworks/Python.framework/Versions/3.11/lib/python3.11/http/server.py", line 136, in server_bind
    socketserver.TCPServer.server_bind(self)
  File "/opt/homebrew/Cellar/python@3.11/3.11.2_1/Frameworks/Python.framework/Versions/3.11/lib/python3.11/socketserver.py", line 472, in server_bind
    self.socket.bind(self.server_address)
OSError: [Errno 48] Address already in use
```

Second one was initialized inside a lder with an html, css and js files
