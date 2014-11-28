Cooking experience at my own kitchen ;)
==================================

# Requirements

The following software is required to run this tutorial:

- [VirtualBox](http://www.virtualbox.org/): Software that allows virtualized environments to run on your system.
- [Vagrant](https://github.com/mitchellh/vagrant): Software that provides an easy to use interface with various virtual environment providers.
- [Chef](https://github.com/opscode/chef): Configuration management software used to provision infrastructure via cookbooks(collections of scripts).
- [Berkshelf](https://github.com/berkshelf/berkshelf): Used to organize the cookbooks required by the infrastructure.
- test-kitchen(https://github.com/opscode/test-kitchen): An application that tests cookbooks by running tests across a user defined set of platforms.

- Install [Vagrant](https://github.com/mitchellh/vagrant) and [VirtualBox](http://www.virtualbox.org/) for your system using the directions provided on their websites.

- Ruby version 1.9.1 or greater is required. You can check your version by running ruby --version  on the commandline. If your version is not sufficient, check the [Download Ruby](http://www.ruby-lang.org/en/downloads/) page for ways to get a newer version, or use [my script](https://gist.github.com/ravibhure/134adce1b072bdf70533)

- Next, install the chef, test-kitchen and berkshelf gems. You may need to use sudo if your user doesn't have permissions to install gems.

			$ gem install chef 
			$ gem install test-kitchen --pre
			$ gem install berkshelf
			$ gem install kitchen-vagrant


# Yes, you can find more details at [kitchen](http://kitchen.ci/)
