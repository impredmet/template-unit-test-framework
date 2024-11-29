# Template Unit Test Framework

Template for @btc-vision/unit-test-framework

## Description

This project is a template for setting up a unit test framework using the `@btc-vision/unit-test-framework` package.

## Prerequisites

- [Click here to see the prerequisites](https://docs.opnet.org/developers/getting-started/prerequisites).

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/impredmet/template-unit-test-framework
   cd template-unit-test-framework
   ```

2. Install the dependencies:

   ```sh
   npm install
   ```

## Usage

### Build the Project

To build the project, run:

```sh
npm run build
```

### Watch for Changes

To watch for changes and automatically rebuild the project, run:

```sh
npm run watch
```

### Clean the Build Directory

To clean the build directory, run:

```sh
npm run clean
```

## Project Structure

- `src/`: Contains the source code.
- `src/tests/`: Contains the test files.
- `build/`: The output directory for the compiled files.
- `gulpfile.js`: Gulp configuration file.
- `tsconfig.json`: TypeScript configuration file.
- `eslint.config.js`: ESLint configuration file.
- `package.json`: Project metadata and dependencies.

## Running Tests

To run the tests, first build the project using:

```sh
npm run build
```

Then, execute the test files directly using Node.js. For example:

```sh
node ./src/tests/file.js
```

## License

This project is licensed under the MIT License.
