# Hey There!
welcome to web cheese tool.This tool madede for ethical hacking and information gathering 

# Web-cheese
Take webcam shots from target just sending a malicious link

![image alt]"(https://github.com/user-attachments/assets/59bf040f-5d1f-4d4e-a28d-641901ac3f55)"

# How it works?
<p>The tool generates a malicious HTTPS page using Serveo or Ngrok Port Forwarding methods, and a javascript code to cam requests using MediaDevices.getUserMedia. </p>

<p>The MediaDevices.getUserMedia() method prompts the user for permission to use a media input which produces a MediaStream with tracks containing the requested types of media. That stream can include, for example, a video track (produced by either a hardware or virtual video source such as a camera, video recording device, screen sharing service, and so forth), an audio track (similarly, produced by a physical or virtual audio source like a microphone, A/D converter, or the like), and possibly other track types. </p>

[See more about MediaDEvices.getUserMedia() here](https://developer.mozilla.org/en-US/docs/Web/API/MediaDevices/getUserMedia)
<p> To convince the target to grant permissions to access the cam, the page uses a javascript code made by https://github.com/Penzopm that turns the favicon into a cam stream.

</p>

## installation (kali Linux/Termux):

```

git clone https://github.com/Penzopm/Web-cheese.git
cd Web-cheese
bash webcheese.sh
```