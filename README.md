# RPi_Camera_Browser_Stream
This is a Python Web Server that can stream the Pi Camera to multiple clients. The streams can be views in browser, or anything with mjpeg support. 

# How to Run
Clone the Repository

```git clone https://github.com/bubbajoe/RPi_Camera_Browser_Stream```

Change Directory to the cloned repository

```cd RPi_Camera_Browser_Stream```

Run Python 3.*.* to run the web server

```python3 rpi_stream.py```

# How to Test

Go to http://localhost:8080 , on the Pi's Browser.

Or,

Go to http://raspberrypi.local:8080 , on a computer on the same network. (if this doesn't work, find out your Pi's IP address and go to http://<Your_IP_Address>:8080).

# Not working?

1. Make sure you have your camera plugged in.

2. Make sure you have your camera is enabled in the Pi's config settings.

3. Make sure you aren't running any other programs that are using the camera.
