# Country Search Practice

A country search application built with HTML, CSS, JavaScript, and Bootstrap. It uses AJAX to retrieve country information from an API and dynamically displays country details and neighboring countries.

## Live Demo

https://ismailturkoglu.github.io/country-search-practice/

## Features

- Search for countries by name.
- Submit searches using the Enter key or the Search button.
- Display country details, including:
  - Flag
  - Population
  - Official language
  - Capital city
  - Currency and currency symbol
- Display neighboring countries in interactive cards.
- Search for a neighboring country by clicking its card.
- Handle HTTP errors, network errors, and invalid API responses.
- Display fallback values when certain country information is unavailable.
- Format population values in millions or billions.

## Technologies Used

- HTML5
- CSS3
- Bootstrap 5.1.3
- JavaScript (ES6+)
- AJAX (`XMLHttpRequest`)
- REST API
- JSON

## Concepts Practiced

- AJAX and asynchronous HTTP requests
- `XMLHttpRequest` for sending HTTP requests
- DOM manipulation and event handling
- HTTP status code validation
- JSON parsing with `JSON.parse()`
- Error handling with `try...catch`
- Optional chaining (`?.`)
- Template literals
- Array methods (`forEach()`)
- Spread syntax (`...`)
- Dynamic HTML rendering with `insertAdjacentHTML()`
- Input validation with `trim()`
- URL encoding with `encodeURIComponent()`
- Conditional expressions and fallback values

## API

Country data is retrieved from [countries.dev](https://countries.dev/).

The application uses the following endpoints:

- `/name/{country}` — retrieves country information by name.
- `/alpha/{code}` — retrieves country information using its country code.

## Purpose

This project was created as part of my JavaScript learning journey to practice AJAX, asynchronous JavaScript, API integration, JSON parsing, DOM manipulation, and error handling.

## License

This project is intended for educational and practice purposes.

## Author

**İsmail Türkoğlu**

- GitHub: [@ismailturkoglu](https://github.com/ismailturkoglu)
