<div id="top"></div>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://www.semasoftware.com/">
    <img src="https://cdn.discordapp.com/icons/972616580078907442/3660c78f24a43ee25aa2e1a313d18424.webp?size=160" alt="Logo" width="80" height="80" >
  </a>

  <h3 align="center">Developer Rubric Discord Bot</h3>

  <p align="center">
    <!-- <a href="">View Demo</a>
    . -->
    <a href="https://github.com/Semalab/developer-skills-matrix-discord-bot/issues/new?assignees=nhcarrigan&labels=%F0%9F%9A%A6+status%3A+awaiting+triage&template=bug_report.yml&title=%5BBUG%5D+-+">Report Bug</a>
    ·
    <a href="https://github.com/Semalab/developer-skills-matrix-discord-bot/issues/new?assignees=nhcarrigan&labels=%F0%9F%9A%A6+status%3A+awaiting+triage&template=feature_request.yml&title=%5BFEAT%5D+-+">Request Feature</a>
  </p>
</div>

## About The Project

<!-- [![Developer Rubric Discord Bot][product-screenshot]](https://example.com) -->

This is a Discord bot that allows you to assess your skills with our [developer rubric](https://github.com/Semalab/developer-skills-matrix) directly on Discord.

Here's what developer rubric is:

- A self-assessment tool you can use to measure your current place in your development journey.
- It provides the Markdown rubric, JSON rubric, and the CSV rubric

<p align="right">(<a href="#top">back to top</a>)</p>

### Installation

_How to run the discord bot locally._

1. Setting up the Discord bot:

- Login to the Discord Developer portal and create a new Application.
- Add a bot to the Application after selecting "Bot" from the left-side panel.
- Copy the bot's token.
- Go to the OAuth2 tab > URL Generator and select both bot and applications.commands scopes, along with the - Administrator permission. Copy the URL generated and invite the bot to your server.
- Copy the guild id of the server you invited the bot into

2. Clone the repo
   ```sh
   git clone https://github.com/YOUR_USERNAME_HERE/developer-skills-matrix-discord-bot.git
   ```
3. Install NPM packages
   ```sh
   npm i
   ```
4. Enter your BOT_TOKEN and GUILD_ID in `.env`
   ```js
   BOT_TOKEN = "";
   GUILD_ID = "";
   ```
5. Run this command to start the bot locally
   ```sh
   npm run start:dev
   ```
   <p align="right">(<a href="#top">back to top</a>)</p>

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the project [here](https://github.com/Semalab/developer-skills-matrix-discord-bot/fork)
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- LICENSE -->

## License

Distributed under the GNU Affero General Public License v3.0. See `LICENSE.md` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>
