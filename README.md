Puppet manifests for a new Raspberry pi.

1. Install [Raspbian](http://www.raspberrypi.org/downloads/) (tested with version June 2014).
2. If running headless, `ssh pi@the-ip` (pw: `raspberry`) and `sudo raspi-config` then reboot when prompted.
3. `sudo gem install puppet --no-ri --no-rdoc`
4. `git clone` this repository to `~/puppet`.
5. `sudo puppet apply ~/puppet/manifests/site.pp`.
