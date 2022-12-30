# Free Church Accounting Software

[![License](https://img.shields.io/github/license/akaunting/akaunting?label=license)](LICENSE.txt)


This project is a free, open source and online accounting software designed for churches. 


## Requirements

* PHP 8.0 or higher
* Database (eg: MySQL, PostgreSQL, SQLite)
* Web Server (eg: Apache, Nginx, IIS)
* [Other libraries](https://akaunting.com/docs/requirements)

## Framework

This project uses [Laravel](http://laravel.com) as the foundation PHP framework.

## Installation

* Install [Composer](https://getcomposer.org/download) and [Npm](https://nodejs.org/en/download)
* Clone the repository: `git clone https://github.com/akaunting/akaunting.git`
* Install dependencies: `composer install ; npm install ; npm run dev`

```bash
php artisan install --db-name="akaunting" --db-username="root" --db-password="pass" --admin-email="admin@company.com" --admin-password="123456"
```

* Create sample data (optional): `php artisan sample-data:seed`

## Contributing

Please, be very clear on your commit messages and pull requests, empty pull request messages may be rejected without reason.

When contributing code to this project, you must follow the PSR coding standards. The golden rule is: Imitate the existing code.

## Changelog

Please see [Releases](../../releases) for more information what has changed recently.

## Security

Please review [our security policy](https://github.com/akaunting/akaunting/security/policy) on how to report security vulnerabilities.

## Credits

* [Ben Coleman](https://github.com/benKColeman)
* [All Contributors](../../contributors)

## License

This project is released under the [GPLv3 license](LICENSE.txt).
