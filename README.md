<h1> Articles_Manager </h1>

<p>Articles Manager is an CRUD Based application where you can create,update or delete the articles to/from the database
This application is built on Symfony Framework where i used twig template engine for views and doctrine orm for database interactions.</p>
<p>
To run this project
You need Composer dependency manager and install symfony framework need any server like apache/nginx 
text editor suggested Sublime/Visual studio Code.
</p>
# Install dependencies
composer install

# Edit the env file and add Database parameters

# Create Article schema
php bin/console doctrine:migrations:diff

# Run migrations
php bin/console doctrine:migrations:migrate

All The Best
