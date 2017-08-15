# ReStatGui
  
ReStat is a simple data collection tool for server status.
ReStatGui is a simple GUI for the [ReStat](https://github.com/Fullaxx/ReStat) collection tool.
It has a few independent pieces that collect important information
and includes a web interface to display the information in real time.
The goal is to collect and monitor system status and be as lightweight as possible.
It can be run on as many machines as you would like.

## Installation & Deployment

Place these files in your webroot and serve up with your favorite web server.
* [Darkhttpd](https://unix4lyfe.org/darkhttpd/) is one of my favorites
* Fly light with [lighttpd](https://www.lighttpd.net/)
* [Nginx](https://www.nginx.com/resources/wiki/) is good too

## Configuration

edit js/config.js and set restathost and restatport to your running restat_uhd socket

## File Tree
```
├── index.html
├── README.md
├── css
│   ├── bootstrap.css
│   ├── bootstrap.css.map
│   ├── bootstrap.min.css
│   ├── bootstrap.min.css.map
│   ├── bootstrap-theme.css
│   ├── bootstrap-theme.css.map
│   ├── bootstrap-theme.min.css
│   ├── bootstrap-theme.min.css.map
│   ├── sticky-footer.css
│   └── style.css
├── fonts
│   ├── glyphicons-halflings-regular.eot
│   ├── glyphicons-halflings-regular.svg
│   ├── glyphicons-halflings-regular.ttf
│   ├── glyphicons-halflings-regular.woff
│   └── glyphicons-halflings-regular.woff2
└── js
    ├── bootstrap.min.js
    ├── config.js
    ├── jquery.min.js
    └── restat.js
```
