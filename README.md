# HelloApp

This is a simple Ruby on Rails application that has been updated from Rails 5.0 to Rails 7.1.

## System Requirements

* Ruby 3.2.2
* Rails 7.1.x
* SQLite 3

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```
   bundle install
   ```
3. Set up the database:
   ```
   rails db:create
   rails db:migrate
   ```
4. Start the server:
   ```
   rails server
   ```

## Testing

Run the test suite with:
```
rails test
```

## Key Features

* Updated to Rails 7.1 from Rails 5.0
* Modern JavaScript handling with importmaps
* Improved security with updated dependencies
* Enhanced performance with bootsnap

## Deployment

This application is configured for deployment with standard Rails practices. The production environment is set up with:

* Force SSL enabled
* Logging to STDOUT for containerized environments
* Asset compilation disabled by default

## License

This application is available as open source under the terms of the MIT License.
