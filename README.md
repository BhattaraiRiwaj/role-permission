# role-permission
## Laravel Roles Permissions Admin - Spatie version

__Update October 2019__: this project was created in 2017 as Laravel 5.4 version, and now we upgraded it to Laravel 6 version, also changed the design theme from [AdminLTE](https://adminlte.io/) to [CoreUI](https://coreui.io)

- - - - -

This is a Laravel 6 adminpanel starter project with roles-permissions management based on [Spatie Laravel-permission package](https://github.com/spatie/laravel-permission), [CoreUI](https://coreui.io) and [Datatables.net](https://datatables.net).


Part of this project was generated automatically by [QuickAdminPanel system](https://quickadminpanel.com/).


## Usage

This is not a package - it's a full Laravel project that you should use as a starter boilerplate, and then add your own custom functionality.

- Clone the repository with `git clone`
- Copy `.env.example` file to `.env` and edit database credentials there
- Run `composer install`
- Run `php artisan key:generate`
- Run `php artisan migrate --seed` (it has some seeded data - see below)
- That's it: launch the main URL and login with default credentials `admin@admin.com` - `password`

This boilerplate has one role (`administrator`), one permission (`users_manage`) and one administrator user.

With that user you can create more roles/permissions/users, and then use them in your code, by using functionality like `Gate` or `@can`, as in default Laravel, or with help of Spatie's package methods.



## Notice

We are not responsible for any functionality or bugs in **CoreUI**, **Laravel-permission** or **Datatables** packages or their future versions, if you find bugs there.

---
