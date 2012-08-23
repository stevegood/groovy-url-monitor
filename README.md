# groovy-url-monitor

A URL monitoring script that can send an SMS when things go pear shaped.

## Setup

- Install [Groovy 2.0.1](http://groovy.codehaus.org) or higher
    - Make sure groovy/bin is in your PATH
- Get a Twilio account (required only if you want the script to send SMS)
    - [Register for a Twilio account](http://twilio.com)
- Configure the script
    - In a text editor, open `monitorURL` and make sure to edit the options block at the top of the file to match your needs
- *nix systems
    - Make the script executable `chmod a+x monitorURL`
- Windows
    - I'm working on it, but you might be able to just run `groovy monitorURL` (untested)