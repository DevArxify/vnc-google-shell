# Google Shell VNC
Step-by-step guide on how to connect remotely to a [Google Cloud](https://console.cloud.google.com) server.
# Instructions
First, we'll install the Google Remote Desktop client by using the following command:<br>
`$ wget https://dl.google.com/linux/direct/chrome-remote-desktop_current_amd64.deb`

## Second step

Then, we'll clone this repository to get the remote desktop environment required file.<br>
`$ git clone https://github.com/DevArxify/vnc-google-shell.git`<br><br>

## Third step

Next, we have to unpackage and install the Remote Desktop client.<br>
`$ sudo dpkg -i chrome-remote-desktop_current_amd64.deb`<br><br>
`$ sudo apt-get install -f`<br><br>

## Fourth step

Now, let's enter to the folder that we cloned previously.<br>
`$ cd vnc-google-shell`<br><br>

## Fifth step

Next, we have to run the necessary script to setup a desktop environment on the server.<br>
`$ python vnc.py`<br><br>

## Sixth step

Then, log into the [Google Remote Desktop](https://remotedesktop.google.com/headless) headless install with your [Google account](https://myaccount.google.com). <br><br>

# Last step

And last but not least, copy the Debian Linux command and paste it on the machine.<br><br>

Now, you can connect to it using the [Remote Desktop](https://remotedesktop.google.com/) website and selecting the `xfce session` while booting up.

# FAQ
### When I run the "Debian Linux" command, it outputs an error
A: Try repeating the first and third steps.<br><br>

### It outputs an error when I try the fifth step
A: run `$ sudo apt-get install python -y`

# Credits
©️ Arxify Innovations, 2022<br>
This piece of software is licensed under the [MIT license](https://github.com/ArxifyByte/vnc-google-shell/tree/main/LICENSE)
