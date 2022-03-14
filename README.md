<div align="center" id = "top">
  <img src="aurishem.png"  alt="aurishem logo"/>
  <h3>Safe and Easy way to build and install packages directly from <a href="https://aur.archlinux.org">Arch User Repository</a></h3> 
</div>

## Contents
- [Features](#Features)
- [Screenshots](#Screenshots)
- [Installation](#Installation)
- [Contributing](#Contributing)
- [Authors](#Authors)
- [License](#License)


## Features

- Uses policy-kit instead of `sudo` for installing dependencies and package
- Install directly from [aur.archlinux.org](https://aur.archlinux.org)
- One click install **only** after scrolling through PKGBUILD 
- Delete build files after install
- Excellent logging system and view live install using `tail -f` if required
- Get notified at each step


## Screenshots

| Install button on PKGBUILD page                                                                                       | Informative Notifications                                                                                                |
|-----------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------|
| ![Install Button](https://raw.githubusercontent.com/CoolFool/aurishem-extension/main/static/install_button.png)       | ![Informative Notifications](https://raw.githubusercontent.com/CoolFool/aurishem-extension/main/static/notification.png) |                                                                                                               |                                                                                                               |
| **Policy Kit Prompt**                                                                                                 | **Live Log using** `tail -f`                                                                                             |
| ![Policy Kit Prompt](https://raw.githubusercontent.com/CoolFool/aurishem-extension/main/static/policy-kit-prompt.png) | ![Live Log](https://raw.githubusercontent.com/CoolFool/aurishem-extension/main/static/live-log.png)                      |

<p align="right">(<a href="#top">back to top</a>)</p>

## Installation
- There are two parts to installing aurishem
  ### 1) Install the aurishem backend
  - #### From Arch User Repository using aur helpers
       - The arch user repository package can be found on [https://aur.archlinux.org/packages/aurishem](https://aur.archlinux.org/packages/aurishem)
       - If you have **yay** or **paru** as aur helpers run ```yay -S aurishem``` **OR**  ```paru -S aurishem``` respectively
       - If using any other aur helper lookup the command for installing packages and install according
  - #### Building the package manually
       - ```git clone https://aur.archlinux.org/aurishem.git```
       - ```cd aurishem```
       - ```makepkg -si```
  ### 2) Install browser extension
  - #### Mozilla Firefox
    [![Firefox Addon](https://raw.githubusercontent.com/CoolFool/aurishem-extension/main/static/get-the-addon.png)](https://addons.mozilla.org/en-US/firefox/addon/aurishem/)
  - #### Microsoft Edge
    - **Coming Soon**
  - #### Chrome/Chromium
    - **Publishing to Chrome Webstore requires creating an account,for the time being follow the steps provided below:**
      - Download [aurishem-extension](https://github.com/CoolFool/aurishem-extension) repo locally
      - Visit `chrome://extensions` in Google Chrome/Chromium
      - Click on **Load Unpacked**
      - Select the **aurishem** directory from the locally downloaded copy of [aurishem-extension](https://github.com/CoolFool/aurishem-extension)
<p align="right">(<a href="#top">back to top</a>)</p>

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>


## Authors

- [@coolfool](https://www.github.com/coolfool)

<p align="right">(<a href="#top">back to top</a>)</p>

## License

[MIT](https://choosealicense.com/licenses/mit/)

<p align="right">(<a href="#top">back to top</a>)</p>
