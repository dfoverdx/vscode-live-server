# FAQs

- [FAQs](#faqs)
    - [How to configure the settings in my project?](#how-to-configure-the-settings-in-my-project)
    - [How to use Live Server Web Extension?](#how-to-use-live-server-web-extension)
    - [How to setup Live Server for Dynamic Pages (like PHP)?](#how-to-setup-live-server-for-dynamic-pages-like-php)
    - [How to access the server from Mobile?](#how-to-access-the-server-from-mobile)
----------

## How to configure the settings in my project?

Create a `.vscode` folder in the root of project. Inside of `.vscode` folder create a json file named `settings.json`.
Inside of the `settings.json`, type following key-value pairs. By the way you'll get intelli-sense.

```json
{
    "liveServer.settings.port": 4500,
    "liveServer.settings.root": "/src",
    "liveServer.settings.CustomBrowser" : "chrome",
    "liveServer.settings.AdvanceCustomBrowserCmdLine": "chrome --incognito --remote-debugging-port=9222",
    "liveServer.settings.NoBrowser" : false,
    "liveServer.settings.ignoreFiles" : [
            ".vscode/**",
            "**/*.scss",
            "**/*.sass"
    ]

}
```
_Note: Use either `CustomBrowser` or `AdvanceCustomBrowserCmdLine` setting._

----------

## How to use Live Server Web Extension?

*  Please [check here](https://github.com/ritwickdey/live-server-web-extension) 

----------

## How to setup Live Server for Dynamic Pages (like PHP)?

*  Please [check here](https://github.com/ritwickdey/live-server-web-extension) 

----------



## How to access the server from Mobile?

 First, make a sure that your PC & Mobile are connected through same network. 

In Windows, ensure that the Windows Firewall is allowing Visial Studio Code public access via `Control Panel\All Control Panel Items\Windows Defender Firewall\Allowed apps