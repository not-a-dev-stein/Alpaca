<p align="center"><img src="https://jeffser.com/images/alpaca/logo.svg"></p>

# Alpaca

<a href='https://flathub.org/apps/com.jeffser.Alpaca'><img width='240' alt='Download on Flathub' src='https://flathub.org/api/badge?locale=en'/></a>

Alpaca is an [Ollama](https://github.com/ollama/ollama) client where you can manage and chat with multiple models, Alpaca provides an easy and begginer friendly way of interacting with local AI, everything is open source and powered by Ollama.

---

> [!WARNING]
> This project is not affiliated at all with Ollama, I'm not responsible for any damages to your device or software caused by running code given by any AI models.

## Features!
- Talk to multiple models in the same conversation
- Pull and delete models from the app
- Image recognition
- Code highlighting
- Multiple conversations
- Notifications
- Import / Export chats
- Delete messages

## Future features!
- Document recognition (Probably only Markdown because it's really easy for AI to read)
- YouTube recognition (Ask questions about a YouTube video using the transcript)
- Edit messages
- Snap Package (maybe)

## Screenies
Login to Ollama instance             |  Chatting with models        |  Managing models
:-------------------------:|:-------------------------:|:-------------------------:
![Screenshot from 2024-05-12 19-58-28](https://jeffser.com/images/alpaca/screenie1.png)  |  ![Screenshot from 2024-05-12 20-01-08](https://jeffser.com/images/alpaca/screenie2.png)  |  ![Screenshot from 2024-05-12 20-01-31](https://jeffser.com/images/alpaca/screenie3.png)

## Preview
1. Clone repo using Gnome Builder
2. Press the `run` button

## Instalation
1. Go to the `releases` page
2. Download the latest flatpak package
3. Open it

## Ollama session tips

### Migrate Ollama session to Alpaca's integrated session
For now Alpaca doesn't offer a way to do this from the GUI but it's really simple, when you are using Ollama it creates a folder in the home directory called `.ollama`, you just need to move that folder to `~/.var/app/com.jeffser.Alpaca/data/`

### Change the port of the integrated Ollama instance
Go to `~/.var/app/com.jeffser.Alpaca/config/server.json` and change the `"local_port"` value, by default it is `11435`.

### Backup all the chats
The chat data is located in `~/.var/app/com.jeffser.Alpaca/config/chats.json` you can copy that file wherever you want to.

### Force showing the welcome dialog
To do that you just need to delete the file `~/.var/app/com.jeffser.Alpaca/config/server.json`, this won't affect your saved chats or models.

---

## Thanks
- [not-a-dev-stein](https://github.com/not-a-dev-stein) for their help with requesting a new icon, bug reports and the translation to Brazilian Portuguese
- [TylerLaBree](https://github.com/TylerLaBree) for their requests and ideas
- [Alexkdeveloper](https://github.com/alexkdeveloper) for their help translating the app to Russian
- [Imbev](https://github.com/imbev) for their reports and suggestions
- [Nokse](https://github.com/Nokse22) for their contributions to the UI
- [Louis Chauvet-Villaret](https://github.com/loulou64490) for their suggestions and help translating the app to French

## About forks
If you want to fork this... I mean, I think it would be better if you start from scratch, my code isn't well documented at all, but if you really want to, please give me some credit, that's all I ask for... And maybe a donation (joke)
