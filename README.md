# Under maintance! There are some problems with image colors

# genshin-place-war by genshindb.net
Modified reddit-place-script to bring the Genshin Impact logo back to the canvas.

# About
Script use image from "image.jpg". it is mapped to an image from the Genshin Logo Template overlay. Brown color is representing transparent pixels.

# How To Use
1. Download archive from release folder and unzip it.
2. Login to your Reddit account and go to
   https://www.reddit.com/prefs/apps
   
   Scroll down to "Create Application" and fill field "name" with, for example, "genshin-place"
   
   Choose type "script"
   
   Fill "Redirect Url" with something, for example "https://someurl.com"
   
   Click "Create App"
   
3. Copy key from "secret"

   Copy your id from under "personal use script"
   
4. In unpacked folder find .env file and open it in text editor:

ENV_PLACE_USERNAME='["developer_username"]'       <- Replace developer_username with your reddit username
ENV_PLACE_PASSWORD='["developer_password"]'       <- Replace developer_password with your reddit password
ENV_PLACE_APP_CLIENT_ID='["app_client_id"]'       <- Replace app_client_id with id from under "personal use script"
ENV_PLACE_SECRET_KEY='["app_secret_key"]'         <- Replace app_secret_key with key from "secret"
ENV_DRAW_X_START="0"                              <- Don't change
ENV_DRAW_Y_START="0"                              <- Don't change
ENV_R_START='["0"]'                               <- Don't change
ENV_C_START='["0"]'                               <- Don't change

5. Save .env and launch main.exe

# Multiple accounts
You can add multiple accounts in .env by this template:

ENV_PLACE_USERNAME='["developer_username_1", "developer_username_2"]'

ENV_PLACE_PASSWORD='["developer_password_1", "developer_password_2"]'

ENV_PLACE_APP_CLIENT_ID='["app_client_id_1", "app_client_id_2"]'

ENV_PLACE_SECRET_KEY='["app_secret_key_1", "app_secret_key_2"]'

ENV_DRAW_X_START="0"

ENV_DRAW_Y_START="0"

ENV_R_START='["0", "0"]'

ENV_C_START='["0", "0"]'


# Troubleshooting
If main.exe closing after launch with KeyError: "access token" you probably put incorrect data in .env file.

# Like this?
You can support us by visiting and bookmarking our site with genshin guides: https://genshindb.net/
