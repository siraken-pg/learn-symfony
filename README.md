# Learn Symfony

```bash
# Create a new Symfony project
symfony new my_project --version="6.2.*" --webapp

# Install the dependencies
cd my-project/
composer install

# Checking the Symfony version
bin/console about

# Checking Security Vulnerabilities
symfony check:security

# Run the Symfony server
symfony server:start

# Create a controller
bin/console make:controller [ControllerName]

# Create a database
bin/console doctrine:database:create

# Create an entity
bin/console make:entity

# Create a migration
bin/console make:migration
```
