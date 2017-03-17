# Vagrant Drupal 8
Stock Drupal 8 site for vanilla development.

## To Get Started

1. Save or clone this repo, renaming the folder to the name of your project.
2. Save `private/example.config.yml` as `config.yml`, changing the hostname and/or ip as you see fit.
3. Add the hostname and ip from `config.yml` to your machine's `hosts` file.
4. Run `vagrant up` from within the `private` directory. A Drupal 8 install will be created within a `docroot` folder in your project root.
5. On line 761 of `docroot/sites/default/settings.php`, change `localhost` to the hostname you set in `config.yml`
