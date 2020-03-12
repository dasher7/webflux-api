# WebFlux API

WebFlux is part of the Spring Framework. It is part of the reactive-web-stack, supports Reative Streams and it also fully non-blocking.
Reactive is a programming paradigm in which our code must react to change, and, in those terms, non-blocking is reactive
because we can now react to change, like data being available.

If you'd like to get more info, see this link: [Web on Reactive Stack](https://docs.spring.io/spring/docs/current/spring-framework-reference/web-reactive.html)

## Usage

You'll find some APIs in the project, here I'll show you the two main API:

** GET /callme **
This API will create 100000000 of mocked * User *

** GET / **
On the main root, you'll be able to retrieve all the user that are being created and than saved into de DB.
NOTE: You need a non-blocking client to call this API and see it in action. I suggest to just use your browser.

## Installation

In your console, simply:

``` git clone https://github.com/dasher7/webflux-api.git ```

Import your code into your favourite IDE, I invite you to use Sping Tools Suite (STS 4).

Be sure to have a version of MongoDB installed on your machine.
Create a database called rt_weblux listening on port 27017.

Update your dependcy via Maven and run the app.
It will start a server on * localhost:8080 * use the embedded TomCat provided by Spring Boot.

# Contribuiton and Usage

Feel free to use the project for your own like.
NOTE: The project is always a WIP, because I will always try new things and test new topic.

# License

[MIT](https://choosealicense.com/licenses/mit/)


