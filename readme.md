# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Navigate to the code repo by going to the github page and clicking the Copy > Selecting HTTPS, then clicking the Copy button to the right of the https git URL.

Next, open your terminal program, and choose what directory you want the code to live in. Such as a subdirectory off you home directory called `repos` or `code`. To setup any of those type `mkdir repos` from the current prompt you're at.  

After that, run `git clone ` and paste in the URL you copied i.e. `git clone https://github.com/ObelusFamily/Anythink-Market-0eoo3.git`. This will setup a new directiory under your repos/code directory. 

NOTE: running the `git clone` command above may prompt you to download the XCode developer tools (if running on a Mac). If so, go ahead download and install that.

Finally, navigate to the new directory and run the `docker-compose up` command. This will download all the pre-requisite containers and get them mounted. If you are having issues with Docker, make sure you have Docker Desktop installed and it's currently running.
