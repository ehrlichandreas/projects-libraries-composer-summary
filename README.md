projects-libraries-composer-summary
===================================

Installation

1) Repository Clone

	git clone https://github.com/ehrlichandreas/projects-libraries-composer-summary.git
	
2) Go into the project

	cd projects-libraries-composer-summary
	
3) Pull the newest contents of the project

	git pull

4) Download composer.phar

	Use tutorial on https://getcomposer.org/download/

5) Update composer and download the latest libraries

	rm composer.lock
	php composer.phar selfupdate
	php composer.phar install
	php composer.phar update -o
	php composer.phar dump-autoload -o

6) Use the vendor autoloader in your php scripts

	include_once THISPATH . '/vendor/autoload.php';
	
  or
	
	include_once THISPATH . '/vendor/autoload_52.php';
