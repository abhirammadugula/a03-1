# A03 Personal Website Example

> A personal multipage website example that includes a working contact form.

## Links

- [Website](https://resumesite563.herokuapp.com/)
- [Source Code](https://github.com/profcase/a03)

## Technology Stack

Server-side platform

- Node.js

Node.js modules

- Express web framework
- Morgan HTTP request logger
- Body-Parser to automatically parse HTTP request bodies
- NodeMailer for emailing contact form information
- nodemailer-mailgun-transport plugin for Mailgun
- nconf to keep authorization information in a config.json file (not committed to repo)
- Nodemon live monitoring utility for automatic updates (installed globally)

Mailing Service

- MailGuns service (10,000 free emails) - to send me an email when someone completes the web form

Client-side

- BootStrap framework for responsiveness & styling

## Prerequisities

- Git Distributed Version Control System
- Node (lastest LTS version recommended)
- Node Package Manager (npm)

## Development Tools

- Windows Explorer Context Menu: Add ['Open command window here as administrator'](https://github.com/profcase/open-command-window-here-as-admin)
- Visual Studio (VS) Code
- VS Code Extension: markdownlint (to format Markdown files)
- VS Code Extension: Auto-Open Markdown Preview (to preview Markdown files)

## Used Once At the Beginning

I used a template generator to get started with HTML5 boilerplate

- [Initializr](http://www.initializr.com/)

## Get Started

1. Fork the repo into your own cloud account.
2. Clone your repo down to your local machine.
3. Open a command window in your a03 folder or from VS Code menu, chose View / Integrated Terminal
4. Install the dependencies listed in package.json with npm install.
5. Run nodemon to start the server.  (Hit CTRL-C to stop.)

  ```Powershell
  > npm install
  > nodemon app.js
  ```

Open browser `http://localhost:8081`.

## Set up free email notifications with Mailgun

1. Sign up for an account at <https://www.mailgun.com>.
1. Log in.
1. Go to your dashboard at<https://app.mailgun.com/app/dashboard>.
1. Scroll down to get your "Domain Name".  
1. On the right, click the eye to view your private API key.
1. Create a new config.json from the config.json.example.
1. Set your domain name and private api key as found above.
1. Add your private config.json to the .gitignore file.

## Create Icons

1. Create icon at <https://iconsflow.com>.
2. Create set of icons with <https://www.favicon-generator.org/>.

## Progressive Web App

To improve performance and accessibility on mobile devices, it's progressive.

- manifest.json to provide information about the app and how it should appear
- service-worker.js for fetching and caching (they run even when the user is offline)

## Set up Free Hosting with Heroku

1. Create a free account with Heroku hosting service.
2. Create an appname for your site.
3. Go to Deploy and install Heroku CLI (command line interface).
4. Go to Settings to see your Heroku URI (hosted website link).

## Making Changes

1. Git Add & commit your changes to your local repository (on your machine).
2. Git push to origin master branch - your source code repository (e.g. on GitHub or BitBucket).

## Deploy with Heroku CLI

1. Open command window as administrator in your local repo folder on your machine. 
2. Run heroku login and enter your email address and heroku password.
3. Run git push heroku master
4. If errors, use heroku logs to view the log files. 

```Powershell
heroku login
git push heroku master
heroku logs
```

Open a browser to your Heroku URL to view.

## References

Express in Action: Writing, building, and testing Node.js applications
by Evan M, <https://www.manning.com/books/express-in-action>