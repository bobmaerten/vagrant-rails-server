## DESCRIPTION

Builds a Ruby on Rails server upon a Vagrant VM.
I use these few files to rapidly get a Rails app up and running without pollute
my host config.

It provides rbenv installed for the system and the vagrant user, bundler gem
ready, postgresql backend and Nginx as a webserver.

You can specify a rails app to be configured as the default nginx site in order
to test right upon VM start through a vagrant port redirection.

## REQUIREMENTS

* [VirtualBox](http://www.virtualbox.org/)
* [vagrant](http://www.vagrantup.com/) gem (tested with 1.0.6)
* [librarian](https://github.com/applicationsonline/librarian) gem

## BASIC USAGE

1. Fetch the necessary provisionning recipes and start the VM:

        $ librarian-chef install
        $ vagrant up

2. Go take one or two coffees

3. Open your host browser to http://localhost:8080

## DEMO

I recorded the boot and provisioning process of this VM on
[Shelr.tv](http://shelr.tv/records/511bf85e966080252e000027).
