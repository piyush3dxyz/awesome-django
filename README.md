# Awesome Django

A curated list of awesome Django apps. Inspired by and based on [awesome-python](https://github.com/vinta/awesome-python/).

- [Awesome Django](#awesome-django)
    - [Admin Interface](#admin-interface)
    - [Asset Management](#asset-management)
    - [Authentication](#authentication)
    - [Debugging](#debugging)
    - [Fields](#fields)
    - [File Transfers](#file-transfers)
    - [Forms](#forms)
    - [Migrations](#migrations)
    - [Model Extensions](#model-extensions)
    - [RESTful API](#restful-api)
    - [Search](#search)
    - [Security](#security)
    - [Settings](#settings)
    - [Storage](#storage)
    - [Tagging](#tagging)
    - [Testing](#testing)
    - [Translations](#translations)
    - [Other](#other)
- [Projects](#projects)
- [Resources](#resources)
- [Contributing](#contributing)

## Admin interface

*Packages that extend the Admin interface, adding or improving features.*

* [django-grappelli](https://github.com/sehmaschine/django-grappelli/) - A jazzy skin for the Django Admin-Interface.
* [django-suit](https://github.com/darklow/django-suit/) - Modern theme for Django admin interface.

## Asset Management

*Packages that help manage the static assets of a project.*

* [django-compressor](https://github.com/django-compressor/django-compressor/) - Compresses linked and inline javascript or CSS into a single cached file.

## Authentication

*Packages that improve or extend the authentication methods of Django.*

* [django-allauth](https://github.com/pennersr/django-allauth/) - Integrated set of Django applications addressing authentication, registration, account management as well as 3rd party (social) account authentication.

## Debugging

*Packages that help hunt down bugs.*

* [django-debug-toolbar](https://github.com/django-debug-toolbar/django-debug-toolbar/) - A configurable set of panels that display various debug information about the current request/response.
* [django-devserver](https://github.com/dcramer/django-devserver/) - A drop in replacement for Django's built-in runserver command.
* [django-querycount](https://github.com/bradmontgomery/django-querycount/) - Middleware that Prints the number of DB queries to the runserver console.

## Fields

*Packages that extend the functionality of existing field type or add new field types.*

* [django-image-tools](https://github.com/bonsaistudio/django-image-tools/) - A package to handle images in Django.
* [django-imagekit](https://github.com/matthewwithanm/django-imagekit/) - Automated image processing for Django.
* [django-picklefield](https://github.com/gintas/django-picklefield/) - A pickled object field for Django

## File Transfer

*Packages that help transfer files between projects and users*

* [django-downloadview](https://github.com/benoitbryon/django-downloadview/) - Serve files with Django.
* [django-sendfile](https://github.com/johnsensible/django-sendfile/) - This is a wrapper around web-server specific methods for sending files to web clients.

## Forms

*Packages that extend the functionality of forms or add new types of forms.*

* [django-crispy-forms](https://github.com/maraujop/django-crispy-forms/) - The best way to have DRY Django forms. The app provides a tag and filter that lets you quickly render forms in a div format while providing an enormous amount of capability to configure and control the rendered HTML.
* [django-floppyforms](https://github.com/gregmuellegger/django-floppyforms/) - django-floppyforms is an application that gives you full control of the output of forms rendering. The forms API and features are exactly the same as Django’s, the key difference is that fields and widgets are rendered in templates instead of using string interpolation, giving you full control of the output using Django templates.

## RESTful API

*Packages for developing RESTful APIs.*

* [django-rest-framework](http://www.django-rest-framework.org/) - A powerful and flexible toolkit that makes it easy to build Web APIs.
* [django-rest-swagger](https://github.com/marcgibbons/django-rest-swagger/) - Swagger Documentation Generator for Django REST Framework
* [django-tastypie](http://tastypieapi.org/) - Creating delicious APIs for Django apps since 2010.

## Migrations

*Packages that help migrate the database when there are schema updates.*

* [South](https://bitbucket.org/andrewgodwin/south/src/) - Django application to provide schema and data migrations.

## Model Extensions

*Packages that extend the functionality of models or add new classes of models.*

* [django-aggregate-if](https://github.com/henriquebastos/django-aggregate-if/) - Conditional aggregates for Django queries, just like the famous SumIf and CountIf in Excel.
* [django-model-utils](https://github.com/carljm/django-model-utils/) - Django model mixins and utilities.
* [django-mptt](https://github.com/django-mptt/django-mptt/) - Utilities for implementing a modified pre-order traversal tree in django.

## Search

*Packages that provide search capabilities to projects.*

* [django-haystack](https://github.com/toastdriven/django-haystack/) - Modular search for Django.

## Security

*Packages that improve the security of a project.*

* [django-secure](https://github.com/carljm/django-secure/) - Helping you remember to do the stupid little things to improve your Django site's security.
* [django-stronghold](https://github.com/mgrouchy/django-stronghold/) - Stronghold is middleware to default all your views to login required.

## Settings

*Packages that help manage the configurability of projects.*

* [django-configurations](https://github.com/jezdez/django-configurations/) - A helper for organizing Django project settings by relying on well established programming patterns.
* [python-decouple](https://github.com/henriquebastos/python-decouple/) - Strict separation of config from code.

## Storage

*Packages that extend the functionality of the existing storage backend or provide new storage backends.*

* [django-storages](https://bitbucket.org/david/django-storages/src/) - django-storages is a collection of custom storage backends for Django.

## Tagging
* [django-taggit](https://github.com/alex/django-taggit/) - Simple tagging for Django.

## Testing

*Packages that help test code or generate test data.*

* [django-behave](https://github.com/django-behave/django-behave/) - TestRunner for the Behave BDD module
* [django-faker](https://github.com/joke2k/django-faker/) - Fake-factory to generate test data
* [django-nose](https://github.com/django-nose/django-nose/) - Test runner using nose
* [django-selenium](https://github.com/dragoon/django-selenium/) - Selenium testing support
* [django-slowtests](https://github.com/realpython/django-discover-slowest-tests-runner/) - Locate your slowest tests.
* [factory_boy](https://github.com/rbarrois/factory_boy/) - A test fixtures replacement for Python
* [lettuce-django-terrain](https://github.com/stringfellow/lettuce-django-terrain/) - Terrain file for lettuce in django projects
* [model-mommy](https://github.com/vandersonmota/model_mommy/) - Smart fixtures for better tests.

## Translations

*Packages help with the task of translating projects.*

* [django-rosetta](https://github.com/mbi/django-rosetta/) - Rosetta is a Django application that eases the translation process of your Django projects.
* [django-modeltranslation](https://github.com/deschler/django-modeltranslation/) - Translate dynamic content of existing Django models to an arbitrary number of languages without having to change the original model classes

## Other
* [django-activity-stream](https://github.com/justquick/django-activity-stream/) - Generate generic activity streams from the actions on your site. Users can follow any actors' activities for personalized streams.
* [django-braces](https://github.com/brack3t/django-braces/) - Reusable, generic mixins for Django.
* [django-extensions](https://github.com/django-extensions/django-extensions/) - This is a repository for collecting global custom management extensions for the Django Framework.
* [django-gravatar2](https://github.com/twaddington/django-gravatar/) - Essential Gravatar support for Django. Features helper methods, templatetags and a full test suite!
* [django-markitup](https://bitbucket.org/carljm/django-markitup/src/) - A Django reusable application for end-to-end markup handling.
* [django-smuggler](https://github.com/semente/django-smuggler/) - Django Smuggler is a pluggable application for Django Web Framework that helps you to import/export fixtures via the automatically-generated administration interface.
* [django-solo](https://github.com/lazybird/django-solo/) - Helps working with singletons - things like global settings that you want to edit from the admin site.
* [sentry](https://github.com/getsentry/sentry/) - Sentry is a realtime, platform-agnostic error logging and aggregation platform.

# Projects

*Outstanding Django projects.*

* [Django packages](https://github.com/pydanny/djangopackages/) - Django Packages is a directory of reusable apps, sites, tools, and more for your Django projects.
* [Opps](http://oppsproject.org/) - A content management platform built for large portals.
* [Satchmo](https://bitbucket.org/chris1610/satchmo/src/) - Satchmo is an eCommerce framework created in Django which allows you to develop unique and robust online stores.
* [django-cms](https://github.com/divio/django-cms/) - The easy-to-use and developer-friendly CMS
* [django-oscar](https://github.com/tangentlabs/django-oscar/) - Domain-driven e-commerce for Django
* [mayan-edms](https://github.com/mayan-edms/mayan-edms/) - Open source, Django based DMS (document management system) with custom metadata indexing, file serving integration, OCR capabilities, document versioning and electronic signature verification.
* [mezzanine](https://github.com/stephenmcd/mezzanine/) - A content management platform built using the Django framework.

# Resources

Where to discover new Django apps and projects.

## Websites

* [Django Packages](https://www.djangopackages.com/) - Django Packages is a directory of reusable apps, sites, tools, and more for your Django projects.

# Contributing

Just fork and send a pull request with your awesome django apps and/or projects.
