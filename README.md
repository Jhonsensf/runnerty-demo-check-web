## Runnerty Demo - Check a website

This a [Runnerty](https://github.com/runnerty/runnerty) demo for checking if a website is online.

It checks if http://www.google.com is online every 5 minutes. Everytime the chain is executed it checks if the web is online, if it is not, the procces retry it again in 30 seconds, if the web stills offine the process fails and show an error with throught the @runnerty/notifier-console.

The chain is set to fail intentionally. If you want to change this yo only have to change the `"check_contains": "gooogle"` property for a correct text

> Note that it's possible to use any of the existing notifiers to get feed if the chain fails. Have a look at the documentation [here](http://docs.runnerty.io/plugins/)



## Usage
Clone the repo
```
https://github.com/Jhonsensf/runnerty-demo-check-web
```

Go to the directory  
```
cd runnerty-demo-check-web
npm install
```

Run Runnerty
```
runnerty
```

Force Run
```
run -f CHECK_MY_WEB_CHAIN
```