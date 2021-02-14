<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

## Laravel React Boilerplate

<p>
<a href="https://packagist.org/packages/nilanth/laravel-react-boilerplate"><img src="https://img.shields.io/packagist/v/nilanth/laravel-react-redux" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/nilanth/laravel-react-boilerplate"><img src="https://img.shields.io/packagist/l/nilanth/laravel-react-redux" alt="License"></a>
</p>

Laravel React Boilerplate helps to fasten your development, Instead of spending more time on configuring React and SPA Authentication.

### Pre-Configured with

- Laravel 8
- Laravel Sanctum for SPA Auth
- React 17
- Redux 
- React Router
- Axios
- [Ant Design](https://github.com/ant-design/ant-design)
- [Redux Saga](https://redux-saga.js.org/)
- [Sass](https://sass-lang.com/)
- [ESLint](https://github.com/eslint/eslint)
- Preconfigured redux store, actions and saga.

### Pre-Configured Modules

- User Login
- User SignUp
- Auth Routes

## Quick Start

### Laravel Development Environment setup

You can choose either one for your development
1. [Laravel Homestead](https://laravel.com/docs/8.x/homestead)
2. [Laravel Sail](https://laravel.com/docs/8.x/sail)

### Required setup before clone
1. [Composer 2](https://getcomposer.org/download/). 
2. [Node](https://nodejs.org/en/) stable version.

### Usage

- Clone this Repo
- `cd laravel-react-boilerplate`
- Create a .env by copying .env.example and Update the required fields.
- Run `composer install`
- Run `php artisan key:gen`
- Run `yarn install`
- Create a Database
- Update the Database credential to .env file
- Run `php artisan migrate` -> To create needed tables.
- Run `php artisan db:seed` -> To seed some fake users.
- Run `yarn run dev`

### Coming Up 

- Tests
- Custom Error response for API request
- Reset Password
- Demo Link
- Email Verification

## Contributing

Please see [CONTRIBUTING](.github/CONTRIBUTING.md) for details.

## Security Vulnerabilities

Please review [our security policy](../../security/policy) on how to report security vulnerabilities.

## Credits

-   [Nilanth](https://github.com/nilanth)
-   [All Contributors](../../contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
