# Hello World Python App

A simple Python Flask application that displays "Hello World" on port 80.

## Installation

```bash
pip install -r requirements.txt
```

## Running the App

```bash
python app.py
```

The app will be accessible at `http://localhost/`

## Note

Running on port 80 requires root/admin privileges. On most systems, you can use:
```bash
sudo python app.py
```

Or alternatively, run on a different port (e.g., 5000) for development:
```python
app.run(host='0.0.0.0', port=5000)
```
