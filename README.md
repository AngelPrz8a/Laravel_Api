
![Logo](https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg)


## Blog with API Rest

An API that displays blog's post, creating new versions with new features without altering the old ones.

## Tech Stack

**Client:** [TailwindCSS](https://tailwindcss.com)

**Server:** [Laravel](https://laravel.com/)


## Installation

1. Clone this repository.
2. Navegate to the project directory
3. Run `composer install` to install the dependencies.
4. Configure your environment variables.
5. Run `php artisan key:generate` to generate an application key.
6. Run `php artisan migrate` to create the tables in your database.
7. Run `php artisan db:seed` to fill the database with test data.


    
## API Reference

#### Login

| Type | Path     | Description                | Params| Return
| :-------- | :------- | :------------------------- | :---- |:--|
| `Post` | `/api/login` |Validate that the user exists | name, email, password|token


#### Get all - Version 1

| Type | Path     | Description                
| :-------- | :------- | :-------------------------
| `Get` | `/api/v1/posts` | Display all posts 

#### Get one - Version 1

| Type | Path | Description 
| :- | :- | :-|
| `Get` | `/api/v1/posts/${id}` | Display one specific post 

#### Delete 

| Type | Path | Description 
| :- | :- | :-|
| `Delete` | `/api/v1/posts/${id}` | Delete one post


#### Get all - Version 2

| Type | Path     | Description                
| :-------- | :------- | :-------------------------
| `Get` | `/api/v2/posts` | Display all posts 

#### Get one - Version 2

| Type | Path | Description |
| :- | :- | :-|
| `Get` | `/api/v2/posts/${id}` | Display one specific post| 

## Links

[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://angelprz008a.github.io/Portafolio/)

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/angel-programmer-junior/)

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

