{
  "name": "denvercoder1/readme-typing-svg",
  "description": "⚡ Dynamically generated, customizable SVG that gives the appearance of typing and deleting text. Typing SVGs can be used as a bio on your Github profile readme or repository.",
  "keywords": [
    "github",
    "dynamic",
    "readme",
    "typing",
    "svg",
    "profile"
  ],
  "license": "MIT",
  "version": "0.8.0",
  "homepage": "https://github.com/DenverCoder1/readme-typing-svg/",
  "autoload": {
    "classmap": [
      "src/models/",
      "src/views/",
      "src/controllers/"
    ]
  },
  "require": {
    "php": "^7.4|^8.0",
    "vlucas/phpdotenv": "^5.3"
  },
  "require-dev": {
    "phpunit/phpunit": "^9"
  },
  "scripts": {
    "start": "php7 -S localhost:8000 -t src || php -S localhost:8000 -t src",
    "test": "./vendor/bin/phpunit --testdox tests",
    "format:check": "prettier --check *.md **/**/*.{php,md,js,css} --print-width 120",
    "format": "prettier --write *.md **/**/*.{php,md,js,css} --print-width 120"
  }
}