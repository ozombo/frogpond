## Installation

    $ git clone https://github.com/jewei/Frognation.git
    $ cd Frognation
    $ composer install

#### Import the DB

Create database called `pond`.

    mysql> create database pond;
    $ mysql -u root -p root < dump.sql


## Tests and Code sniffs

    $ composer run-script phpunit
    $ composer run-script phpcs
