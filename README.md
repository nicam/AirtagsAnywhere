## ❌ WARNING

I don't have a Mac anymore, for now I can't maintain this project.
If I get a Mac and Airtags one day, I will do a complete rewrite with a Android/Windows/Linux/ChromeOS client.

Feel free to open a PR if you have some fixes/improvements.

## Interface

<details>
  <summary>💻 Click to view desktop interface</summary>

  ![Alt Text](/readme_files/desktop.png "Desktop view")
</details>
<details>
  <summary>📱 Click to view mobile interface</summary>

  ![Alt Text](/readme_files/phone.png "Phone view")
</details>

## ❓ Why

With this project, you can see the airtags location on a simple web-app from any device.
The idea of this project is to learn how Airtags location are stored and how to use them, it has been made for educational purposes.

## 🚀 Quick start

### You'll need

- A bit of time
- Any device running MacOS that needs to be always on (to get airtags location and host the server)

### Getting Started On MacOS (Server)

- Install NodeJS using [nvm](https://github.com/nvm-sh/nvm)
- Clone the repository in a convenient location
- run `nvm use`
- run `npm setup`
- run `npm start` (The first time it will ask you for permissions to access `~/Library/Caches/com.apple.findmy.fmipcore/`)
- open `localhost:3890` on your browser and check if it's working

### Getting Started On Your Non-Apple Device (Client)

- Type the IP of your Mac on your address bar, followed by :3890, login, and that's it !


If you want to access it from the external network, do a wireguard server (or open the port 3890, but I do not recommend it)


## ⌨️ Credits

- AirtagAlex (for the idea of using the Items.data file) : https://github.com/icepick3000/AirtagAlex
