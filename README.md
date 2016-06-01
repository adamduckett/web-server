# Web Server
Spin a web server (with live reload) using Gulp to aid front-end builds.

## Getting Started
```
  $ git clone https://github.com/adamduckett/web-server.git your-project-folder
  $ cd your-project-folder
  $ rm -rf .git/
  $ git init
  $ npm install
  $ gulp
```

The above removes the `.git` folder before creating a new instance of Git, installing our Gulp dependencies (for spinning a local server) and finally running our default Gulp task.

If your build doesn't require Git simply omit the `git init` command :)