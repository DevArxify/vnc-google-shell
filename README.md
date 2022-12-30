# Google Shell VNC
Step-by-step guide on how to connect remotely to a [Google Cloud](https://console.cloud.google.com)
# Instructions
First, we'll install the Google Remote Desktop client by using the following command:<br>
`$ wget https://dl.google.com/linux/direct/chrome-remote-desktop_current_amd64.deb`

## Second step

Then, we'll clone this repository to get the remote desktop environment required file.<br>
`$ git clone https://github.com/ArxifyByte/vnc-google-shell.git`<br><br>

## Third step

Next, we have to unpackage and install the Remote Desktop client.<br>
`$ sudo dpkg -i chrome-remote-desktop_current_amd64.deb`<br>
`$ sudo apt-get install -f`<br><br>

## Fourth step

Now, let's enter to the folder that we cloned previously.<br>
`$ cd vnc-google-shell`<br><br>

## Fifth step

Next, we have to run the necessary script to setup a desktop environment on the server.<br>
`$ python vnc.py`<br><br>

Then, log into the [Google Remote Desktop](https://remotedesktop.google.com/headless) headless install with your [Google account](https://myaccount.google.com). <br><br>

And last but not least, copy the Debian Linux command and paste it on the machine.

# FAQ
### How can I copy any command from this repo?
