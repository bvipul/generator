# Generator
A Laravel 5.6 CRUD Generator Package for Laravel AdminPanel &lt; https://github.com/viralsolani/laravel-adminpanel &gt;

# License
This CRUD Generator is open-sourced software licensed under the MIT license

# Official Documentation
To get started with Generator, use Composer to add the package to your project's dependencies:

`composer require bvipul/generator ^5.6`

Since you would be having work of this generator, while creating your project, hence only require it in the dev environment.

### Configuration

After installing the Generator, register the `Bvipul\Generator\Provider\CrudGeneratorServiceProvider` in your `config/app.php` configuration file:

```php
'providers' => [
    // Other service providers...

    Bvipul\Generator\Provider\CrudGeneratorServiceProvider::class
],
```

If you need to change what the stubs are generating for you, you can always publish the package's views files by below command:
```
php artisan vendor:publish --tag=generator_views
```

and you can get the title "Module Management" from package's translation file by using:

```
{{ trans('generator::menus.modules.management') }}
```


# Contribute
You can contribute to this project, by just taking fork of it. We are open for suggestion and PRs. If you have any new suggestions or anything for that matter, contact me at basapativipulkumar@gmail.com



