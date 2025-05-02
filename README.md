# llamaphone
Download as zip and unextract to use.

Lamma is a fake phone for talking to fake people.
This should run on any webbrowser.![Screenshot from 2025-05-01 23-17-57](https://github.com/user-attachments/assets/6c878a46-1fdc-4ac9-a200-851ab59536eb)


This project requires LLamaCPP: https://github.com/ggml-org/llama.cpp/releases
Download the zip for your platform and we need llama-server or llama-server.exe.
Get a GGUF model from https://huggingface.co/   Gemma models seem to keep character well.
Run llama-server like this on windows

    llama-server.exe -m modelname.jjuf

  and like this on linux/macos

      ./llama-server -m modelname.gguf

minimize it and open llamaphone.html

Once you're up and running, feel free to delete the (silly) built in chatacters. Hit the + and add a contact, describe your character and attach a 128x128 photo. I've included a handful off AI generated faces in faces.zip.

You can use the included charmaker.html to mass generate characters, but you have to add the images manually.
