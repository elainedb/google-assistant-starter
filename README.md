# Google Assistant Starter

## 1) Download or clone Facts about Google
 https://github.com/actions-on-google/apiai-facts-about-google-nodejs

## 2) Install Homebrew
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

## 3) Install node
```
brew install node
```

## 4) Setup Firebase Cloud Functions
```
npm install -g firebase-tools
```
```
firebase login
```

## 5) Create a Firebase project
```
https://console.firebase.google.com/
```

## 6) On your working directory (Facts about Google)
```
firebase init
```
- Check `◯ Functions: Configure and deploy Cloud Functions`
- Pick the project you created on step 5


## 7) Install the node modules
```
cd functions/
npm install
```

## 8) Deploy the function to Firebase Cloud Functions
```
firebase deploy --only functions
```

## 9) Create an API.AI project
```
https://console.api.ai
```

## 10) Restore the zip file downloaded from github earlier (FactsAboutGoogle.zip)
- Settings
- Export and Import
- Restore

## 11) Setup the fulfillment function
Put the link you got from step 8) on the fulfillment section on api.ai

## 12) Test it on API.AI!

## 13) Enable the Actions on Google Integration
- Integrations
- Actions on Google
- Follow the instructions