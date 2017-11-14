# Generator
A Laravel 5.4 CRUD Generator Package for Laravel AdminPanel &lt; https://github.com/viralsolani/laravel-adminpanel &gt;

# License
This CRUD Generator is open-sourced software licensed under the MIT license

# Official Documentation
To get started with Generator, use Composer to add the package to your project's dependencies:

`composer require bvipul/generator --dev 0.8`

Since you would be having work of this generator, while creating your project, hence only require it in the dev environment.

### Configuration

After installing the Generator, register the `Bvipul\Generator\Provider\CrudGeneratorServiceProvider` in your `config/app.php` configuration file:

```php
'providers' => [
    // Other service providers...

    Bvipul\Generator\Provider\CrudGeneratorServiceProvider::class
],
```

After adding the provider, you can add the route of this module generator in sidebar file.
```
'admin.modules.index'
```

and you can get the title "Module Management" from package's translation file by using:

```
{{ trans('generator::menus.modules.management') }}
```


# Contribute
You can contribute to this project, by just taking fork of it. We are open for suggestion and PRs. If you have any new suggestions or anything for that matter, contact me at basapativipulkumar@gmail.com



