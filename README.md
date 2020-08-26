![Hireable](https://img.shields.io/badge/Hireable-yes-success) ![](https://img.shields.io/badge/-Microverse%20projects-blueviolet)

# The Master Seach Telegram Bot

> In this project, I built a Telegram Bot that can search on Wikipedia or get you 3 random Wikipedia articles. It also send you random funny Gifs every time you write something else in the chat or you use the /start and /stop commands. The main goal is to make a massive use of external API`s by put into practice the main concepts of Object Oriented Programming, classes, modules, objects and access their attributes.

## You can see a short demo of the game in the GIF below.
![image](.github/captured.gif)

## The files structure of the project
![screenshot](.github/folder-structure.png)

## Available commands for the master-search-bot

1. `/start` receive a greetings message, all available commands and a funny random Gif
2. `/stop` receive a farewell message, a nice joke and a funny random Gif
3. `/search wiki <your query>` receive a loading message and 3 Wikipedia articles related to your search query
2. `/search wiki random` receive 3 random Wikipedia articles
3. Writed anything else in the chat and you will be informed about the available commands and receive a random funny Gif

## Video Explanation

Here is the [video explanation](https://www.loom.com/share/de84556995414869b6f6e127f291ac27) of this project.

## Built With
* Ruby
* [Telegram API](https://core.telegram.org/api)
* [Wikipedia API](https://www.mediawiki.org/wiki/API:Main_page/en)
* [Tenor Gif API](https://tenor.com/gifapi/documentation)
* RSpec
* Rubocop

## Ruby gems dependencies
* 'colorize'
* 'dotenv'
* 'httparty'
* 'telegram-bot-ruby

## Prerequisities

To get this project up and running locally, you must have ruby installed on your computer.

## Getting Started

**To get this project set up on your local machine, follow these simple steps:**

**Step 1**<br>
Navigate through the local folder where you want to clone the repository and run<br>
`git clone git@github.com:cristianCeamatu/microverse-ruby-telegram-bot.git`. It will clone the repo to your local folder.<br>
or with https<br>
`git clone https://github.com/cristianCeamatu/microverse-ruby-telegram-bot.git`.<br>
**Step 2**<br>
Run `cd microverse-ruby-telegram-bot`<br>
**Step 3**<br>
Run `bundle install` to install the gems from the `Gemfile`.<br>
**Step 4**<br>
Download the [Telegram app](https://desktop.telegram.org/), create an account and talk to the [Botfather](https://t.me/botfather). Follow the instructions and create a bot, you will then receive an API Token that looks like this: `1347431199:AAH4hPt6PDiJB4swk23Lb4oOzwocjKpba0S4` and the link to your bot.<br>
**Step5**<br>
Visit [Tenor API page](https://tenor.com/gifapi/documentation) and follow the quickstart steps to get a Tenor API Key.<br>
**Step 6**<br>
Run `mv .env_sample .env` on your terminal to create the `.env` file. Then add your tokens in the required fields `TELEGRAM_BOT_TOKEN=` and `TENOR_API_TOKEN` inside the file.<br>
**Step7**<br>
Run `ruby bin/bot.rb` to start the bot.<br>
**Step 8**<br>
Open the link to the bot that you received from the Botfather.<br>
**Step 9**<br>
You can start using the commands defined above.<br>

## Repository Contents

The code for the project is divided into the following directories: **./bin**, **./lib**, and **./spec**.

The **./bin** folder contains the executable **bot.rb** file.

The **./lib** folder contains subsidiary files that set up all of the classes and methods used in bin/main.rb

- **search.rb**, where the Search class is defined.
- **utils.rb**, where the Utils module is defined.

The **./spec** folder contains all the relative spec tests

- **search_spec.rb**, where the tests for the Search class are defined.
- **utils_spec.rb**, where the tests for the Utils methods are defined.
- **spec_helper.rb**, initial file generated by the RSpec.

In addition to the above, the repo also contains .rubocop.yml for linting.

## Tests

1. Open Terminal

2. Install RSpec on your system by running:

    `gem install rspec`

3. Run the tests with the command:

    `rspec`

## Authors

👤 **Cristian Viorel Ceamatu**

- Github: [@cristianCeamatu](https://github.com/cristianCeamatu)
- Twitter: [@CeamatuV](https://twitter.com/CeamatuV)
- Linkedin: [Ceamatu Cristian](https://www.linkedin.com/in/ceamatu-cristian/)

## 🤝 Contributing

Our favourite contributions are those that help us improve the project, whether with a contribution, an issue, or a feature request!

Feel free to check the [issues page](https://github.com/cristianCeamatu/microverse-ruby-telegram-bot/issues) to either create an issue or help us out by fixing an existing one.

## Show your support

If you've read this far....give us a ⭐️!

## 📝 License

This project is licensed by Microverse and the Odin Project
