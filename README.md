# Ruby on Rails Tutorial Sample Application

With some of the free time that I've had at the start of this Summer, I've decided to work through the [Ruby on Rails Tutorial](https://www.railstutorial.org/) once again in order to refresh my memory on some Rails basics. This is the sample applicatioin developed in Chapters 3 - 14.

## License

All source code in the [Ruby on Rails Tutorial](https://www.railstutorial.org/) is available jointly under the MIT License and the Beerware License. See [LICENSE.md](LICENSE.md) for details.

## Getting Started

To get started with the app, clone the repo and then install the needed gems:

```
$ bundle install --without-production
```

Next, migrate the database:

```
$ rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly:

```
$ rails test
```

If the test suite passes, you'll be ready to run the app in a local server.

```
$ rails server
```

For more information, see the [*Ruby on Rails Tutorial* book](https://www.railstutorial.org/book).