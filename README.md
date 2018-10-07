# A03 Personal Website Example

A simple website using server-side:

- Node.js platform
- Express web framework
- Morgan HTTP request logger
- Body-Parser to automatically parse HTTP request bodies
- NodeMailer for emailing contact form information
- Nodemon for live updates
- nconf to keep authorization information in a config.json file (not committed to repo)
- MailGun (10,000 free emails)

and client-side:

- BootStrap framework for responsiveness & styling
- Initializr from <http://www.initializr.com/>

## Development Tools

- Windows Explorer Context Menu: Add 'Open command window here as administrator'
 <http://www.sevenforums.com/tutorials/47415-open-command-window-here-administrator.html>
- Visual Studio Code

## Get Started

1. Open a command window in your c:\44563\a03 folder or from VS Code menu, chose View / Integrated Terminal

1. Install nodemon globally with npm install -g nodemon

1. Install the dependencies listed in package.json with npm install.

1. Run nodemon to start the server.  (Hit CTRL-C to stop.)

  ```Powershell
  > npm install -g nodemon
  > npm install
  > nodemon
  ```

Open browser `http://localhost:8081`.

## Set up Mailgun

1. Sign up for an account at <https://www.mailgun.com>.

1. Log in.

1. Go to your dashboard at<https://app.mailgun.com/app/dashboard>.

1. Scroll down to get your "Domain Name".  

1. On the right, click the eye to view your private API key.

1. Create a new config.json from the config.json.example.

1. Set your domain name and private api key as found above.

1. Add your private config.json to the .gitignore file.

## References

Express in Action: Writing, building, and testing Node.js applications
by Evan M, <https://www.manning.com/books/express-in-action>

## Code

<https://bitbucket.org/professorcase/a03>

## Demo

