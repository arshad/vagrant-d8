Vagrant for Drupal 8
==========

Vagrant setup for Drupal 8. Code taken from http://drupal.org/project/vdd with some tweaks.

### Installation

    $ git clone https://github.com/arshad/vagrant-d8.git vagrant-SITENAME
    $ cd vagrant-SITENAME
Edit config.json and configure IP, Site name, and Git. Then run:
    
    $ vagrant up

Once vagrant is provisioned and up, you can remove everything inside www and place Drupal in there.
