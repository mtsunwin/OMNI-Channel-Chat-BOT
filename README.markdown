# OMNI CHANNEL BOT

# About:
BOT's will help you connect 'omni channel' with platform Rocket.Chat
- [x] Facebook
- [x] Viber
- [x] Skype
- [x] Zalo
- [x] Telegram

# Setup .ENV : 
You must register "Webhook" and get parameter config of the platforms Facebook Messenger, viber, zalo, ... and fill in this file .env

Include arguments:

  Facebook:
  
      FACEBOOK_CLIENT_ID = [your client id]
      FACEBOOK_CLIENT_SECRET = [your client secret]
      FACEBOOK_CALLBACK_URL = [your url call back]
      FACEBOOK_PAGE_ACCESS_TOKEN = [acces token of page]
      
  SKYPE:
  
      SKYPE_GRANT_TYPE = <client_credentials>
      SKYPE_CLIENT_ID = [Microsoft azure Application ID]
      SKYPE_CLIENT_SECRET = [Microsoft azure Application Password - You must goto setting of app chosen Setting, find "Microsoft App ID" and click at "Manage"]
      SKYPE_SCOPE = [This url to call API AZURE]
      
  Telegram
  
    TELEGRAM_TOKEN_BOT = [Token of the Bot your register with Telegram]
    

  ZALO:
  
      ZALO_APP_ID = []
      ZALO_REDIRECT_URI = [YOU MUST REGISTER URL THIS WITH ZALO]
      ZALO_SECRETKEY = []
      ZALO_TOKEN = [ACCESS TOKEN OF ACCOUNT TO USE API ZALO]
      
  VIBER
  
      VIBER_TOKEN = []

  ROCKET CHAT
  
     ROCKET_USERNAME = [User name of BOT],
     ROCKET_USERID = [USER id of BOT],
     ROCKET_TOKEN = [TOKEN of BOT]
     ROCKET_URL_API_ROCKET = [URL Call API of your Rocket.Chat]

  MONGO DB
  
    MONGODB_URL = [You can use DB other and fill parameter connect to db at this]
    MONGODB_DB_NAME = [Your DB name]
    MONGODB_COLLECTION = [Your collection of DN]  
    
    
  URL_WEBHOOK
  
    URL_WEBHOOK_VIBER = [URL WEBHOOK you wanna register with platform Rocket]
    URL_WEBHOOK_SKYPE = [URL WEBHOOK you wanna register with platform Rocket]
    URL_WEBHOOK_FACEBOOK = [URL WEBHOOK you wanna register with platform Rocket]
    URL_WEBHOOK_ZALO = [URL WEBHOOK you wanna register with platform Rocket]
    URL_WEBHOOK_TELEGRAM = [URL WEBHOOK you wanna register with platform Rocket]
   
# RUN PROJECT: 

  NODEJS
  
      1. Setup .env
      
      2. npm install
      
      3. npm start
      
  DOCKER
  
      1. You must update environment in docker-compose.yml
      2. docker-compose up
