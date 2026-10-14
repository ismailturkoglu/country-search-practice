# Country Search Practice

A country search application built with HTML, CSS, JavaScript, and Bootstrap. It retrieves country information from an API and displays neighboring countries with interactive cards.

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
- Display neighboring countries using interactive cards.
- Search for a neighboring country by clicking its card.
- Handle HTTP errors, network errors, and invalid API responses.
- Display fallback values when certain country information is unavailable.
- Format population values in millions or billions.

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- Bootstrap 5.1.3
- XMLHttpRequest
- REST API
- JSON

## Concepts Practiced

- DOM manipulation and event handling
- Functions and the spread operator
- Asynchronous JavaScript with XMLHttpRequest
- HTTP status code validation
- JSON parsing with `JSON.parse()`
- Error handling with `try...catch`
- Optional chaining (`?.`)
- Template literals
- Array methods (`forEach()`)
- Dynamic HTML rendering with `insertAdjacentHTML()`
- Input validation and string encoding with `trim()` and `encodeURIComponent()`

## API

Country data is retrieved from [countries.dev](https://countries.dev/).

The application uses the following endpoints:

- `/name/{country}` — retrieves country information by name.
- `/alpha/{code}` — retrieves country information using its country code.

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/ismailturkoglu/country-search-practice.git
   ```

2. Open the project folder.

3. Run `index.html` using a local development server, such as the Live Server extension in Visual Studio Code.

4. Enter a country name and click **Search**.

## Purpose

This project was created as part of my JavaScript learning journey to practice working with APIs, asynchronous requests, DOM manipulation, and error handling.

## License

This project is intended for educational and practice purposes.
