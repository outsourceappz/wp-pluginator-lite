# wp-pluginator-lite
A Lite Version of WordPress Pluginator (wp-pluginator)

[WordPress Pluginator](http://www.outsourceappz.com/products/wordpress-pluginator-orm-migrations) is an opinionated scaffolding tool for creating modern WordPress plugin. it helps you kick start new   wordpress plugin, prescribing best practices and to help you stay productive.
  
It provides the following tools/functionality to make your life easier.
  * A [Plugin Boilerplate Generator](http://www.outsourceappz.com/docs/wordpress-plugin-orm-plus-migrations/4.1/plugin).
  * Plugin integrated with an elegant [ORM](http://www.outsourceappz.com/docs/wordpress-plugin-orm-plus-migrations/4.1/orm), powered by a easy to use [query builder](http://www.outsourceappz.com/docs/wordpress-plugin-orm-plus-migrations/4.1/queries).
  * Plugin integrated with [Database Migrations Manager](http://www.outsourceappz.com/docs/wordpress-plugin-orm-plus-migrations/4.1/migrations) which helps to manage plugin database table insertions/updates.
  * Standalone [Validation](http://www.outsourceappz.com/docs/wordpress-plugin-orm-plus-migrations/4.1/validation) functionality which can be used with the ORM as well.
  * Tool to generate [ORM models](http://www.outsourceappz.com/docs/wordpress-plugin-orm-plus-migrations/4.1/model).
  * Tool to generate [database migrations](http://www.outsourceappz.com/docs/wordpress-plugin-orm-plus-migrations/4.1/migrations#creating-migrations)
  

## Installation
First, download and unzip wp-pluginator-lite.zip file. You will find wp-pluginator-lite.phar file extracted.

Then, check if it works

    php wp-pluginator-lite.phar help

To be able to type just `wp-pluginator-lite`, instead of `php wp-pluginator-lite.phar`, you need to make the file executable and move it to somewhere in your PATH. For example:

    chmod +x wp-pluginator-lite.phar
    sudo mv wp-pluginator-lite.phar /usr/local/bin/wp-pluginator-lite

Now try running `wp-pluginator-lite help`

  
  
  ** Note: `This lite version provides a basic plugin boilerplate generation functionality without the ORM and database migrations`
