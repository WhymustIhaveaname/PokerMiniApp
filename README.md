# PokerMiniApp

Do you ever struggle to remember all the cards played while playing bridge or poker? Don't worry! Our new Telegram MiniApp is here to help you become the master of card games!

To keep track of played cards, find them in the card list and click on them. They will be marked as grey.
If you want to know how many cards remain in each suit, scroll to the top of the page!
The app is compatible with both games that include jokers and those without. Just go to the "settings" section and change the mode!
Enjoy your game and become a card game champion!

## File description

* `index.html`: the main page
* `style.css`: the css file
* `script.js`: the javascript

## How to boot your first Mini App

1. You should host a webpage. The easiest way is to host a page on GitHub. For that, you should

    a. create a new repository and add a new file `index.html`

    b. add the following content to `index.html` and save.

        <!DOCTYPE html>
        <html lang="en">
        <head>
            <meta charset="utf-8"/>
            <script src="https://telegram.org/js/telegram-web-app.js?1"></script>
        </head>
        <body>
            Hello World!
            <script>
                Telegram.WebApp.ready();
            </script>
        </body>
        </html>

    c. on GitHub, go to Settings --> Pages --> Build and deployment --> select Branch and then Save, to deploy it

3. Find [@BotFather](https://t.me/BotFather) on Telegram, create a new bot, select your bot --> Bot Settings --> Menu Button --> add the url of the `index.html` you hold. Then, you should be able to launch the Mini App using the Bot's menu button.
