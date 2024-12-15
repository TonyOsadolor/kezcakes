<p align="center"><a href="https://market.tonytechstudios.com.ng" target="_blank"><img src="https://tonytechstudios.com.ng/Tmart1.jpg" width="200" height="auto"></a></p>

## About TTMarket

KEZ CAKES is a web application for online Cake Shop. The shop offers different services related to cakes, sales, booking and training.
<br>
The aim of this web app is to allow customers and potential clinets, view catalogs, 
add to carts, book for wedding cakes and training sessions.
<br>
All our Cakes designs are uniquely sourced and carefully crafted to meet your needs, without breaking the bank or having to use your savings,
We believe everyone can be Happy while enjoying their favourites cake flavours...

## How it works

<ol>
    <li>Open the website address on your broswer</li>
    <li>Select your Preferred/Desired Cake(s) from the available catalogs</li>
    <li>Click Add to Cart, Click Checkout</li>
    <li>Enter Your shipping Information, and Click on your preferred Payment Method</li>
    <li>You can pay online using any of our available payment solution</li>.
</ol>

## Project Sponsors

We would like to extend our thanks to the following sponsors for funding Domain. Tony Osadolor Innovations [Host Page](https://tinnovations.com.ng).

### Stacks

- **Backend : PHP / Laravel**
- **Frontend : HTML - Bootstrap**
- **Frontend Framework : LiveWire**

## Contribution Guide
##### Setting up your workspace
Before running this app, locally make sure you have the following software installed:
<ul>
    <li>XAMPP/WAMP/LAMP or it's equivalent</li>
    <li>NPM</li>
    <li>Composer</li>
    <li>A Web Browser</li>
</ul>
Now, follow this steps to start contributing:
<ol>
    <li>Go to https://github.com/TonyOsadolor/kezcakes and fork the repo.</li>
    <li>After forking, go to your github page. Clone your forked repo. Create a project folder on your local machine. Navigate to it in the terminal. Run: <code>git clone https://github.com/< your github-username >/kezcakes</code>.</li>
    <li>Run <code>cd kezcakes</code></li>
    <li>Run <code>composer install</code></li>
    <li>Run <code>npm install</code></li>
    <li>Copy all the contents of the <code>.env.example</code> file. Create <code>.env</code> file and paste all the contents you copied from <code>.env.exmaple</code> file to your <code>.env</code> file.</li>
    <li>Run <code>php artisan key:generate --show</code> to retrieve a base64 encoded string for Laravel's APP_KEY in <code>.env</code></li>
    <li>Set your DB_DATABASE = <code>kezcakes</code></li>
    <li>If you are using XAMPP , run it as an administrator. Start Apache and Mysql. Go to <code>localhost/phpmyadmin</code> and create new database and name it <code>kezcakes</code>.</li>
    <li>Run php artisan serve from your terminal and the app will be running on <code>http://127.0.0.1:8000/</code> on your browser</li>
</ol>
##### REMINDER on contributing:
<ol>
    <li>Always create branch for your task <code>git checkout -b &lt;branchname&gt;</code>.</li>
    <li>After you make changes:</li>
    <ul>
        <li><code> git add .</code></li>
        <li><code> git commit -m "some comments"</code></li>
        <li><code> git push origin < name of your branch > </code></li>
    </ul>
    <li>Create PR.</li>
</ol>

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

In order to ensure that the Project is used for it rightful existence, please review and abide by the [Code of Conduct](#).

## Security Vulnerabilities

If you discover a security vulnerability within Project, please send an e-mail to Anthony Osadolor via [support@tinnovations.com.ng](mailto:support@tinnovations.com.ng). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
