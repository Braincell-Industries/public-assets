# How to get your Riot cookies

If you wish to log in without sending your password, either because you log in using Google/Facebook/Apple, or you simply  don't want to risk it, you can login with your cookies instead, as that's all the bot needs to fetch your daily shop.  

That being said, your cookies can still be used to log into your account just like your password, both in-game and on the website, and in some ways they are less secure because they bypass [2FA](https://www.riotgames.com/en/news/multi-factor-authentication-has-arrived).  

Overall, be careful what you do with them.

## How to get your Riot cookies

This guide uses Chrome, but should work on any browser that has some form of devtools (except Firefox, because it doesn't show your whole cookies if they are too long).

First, go to [account.riotgames.com](https://account.riotgames.com/) and make sure you are logged in.

Then:

1. Open a new tab and press `F12` (or `Ctrl+Shift+I`/`⌥⌘I`) to open the devtools, and head to the `Network` tab on the top right.
2. With the Network tab open, open the following link on that tab: `https://auth.riotgames.com/`
3. A new network request should appear called `auth.riotgames.com` in the Network tab, click on it.

<img src="https://raw.githubusercontent.com/Braincell-Industries/public-assets/main/Guides/Assets/requests.png " alt="valorant demo" width="700"/>

<br></br>

4. In the new window that appeared, scroll all the way down to the paragraph called `Request Headers` and look for the `cookie` header.

<img src="https://raw.githubusercontent.com/Braincell-Industries/public-assets/main/Guides/Assets/cookie.png" alt="valorant demo" width="1000"/>

<br></br>

Those are your cookies, you can use them with the `/cookies` command.