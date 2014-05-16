projects-libraries-composer-summary
===================================

Installation

1) Repository Clone

	git clone https://github.com/ehrlichandreas/projects-libraries-composer-summary.git
	
2) Go into the project

	cd projects-libraries-composer-summary

3) Download composer.phar

	Use tutorial on https://getcomposer.org/download/

4) Update composer and download the latest libraries

	rm composer.lock
	php composer.phar selfupdate
	php composer.phar install
	php composer.phar update -o
	php composer.phar dump-autoload -o

