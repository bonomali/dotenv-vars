dotenv-loader
===

Loads a .env file in your project path, setting each row in environment variables.

## Installation
``` npm install --save dotenv-loader ```

## Usage
- Put a **.env** file in your project root containing one pair of environment variable on each row like ``` NODE_ENV=debug ```
- In the top of your main file put ``` require('dotenv-loader') ```