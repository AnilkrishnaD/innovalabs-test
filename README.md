# My Project

## Overview

This project is uses vuex to manage the state of my appliaction and helps how
pass data from cparent to child and child parent.

## Installation

1. Clone this repository.
2. Install dependencies with `npm install`.

## Usage

1. Run the development server: `npm run dev`.
2. Open the application in your web browser at usin your `localhost`.

## Technologies Used

- Vue.js
- Vuex
- Vue Router
- PrimeVue
- axios (for apis)

## Parent to child and child to parent data passing

- In UsersList we used props to send the users list array (parent to child)
- In Search bar we used emits to pass the string to parent componet (to filter
  users)
- we can use provide and inject methods if need passs the data from child to
  child
- by using provide you can set the data and using inject you can consume the
  data

## User creation form with dynamic requested details

- Dummy requested form data configured in dummyjson file with a name export
  formConfig
- You can change that config and json data or make an api request to fetch data

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file
for details.
