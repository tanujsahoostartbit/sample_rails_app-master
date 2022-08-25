# Ruby on Rails sample application for pagination and sample setup


## Getting started

To get started with the app, first clone the repo and `cd` into the directory:

```
$ cd sample_rails_app
```

Then install the needed gems (while skipping any gems needed only in production):

```
$ bundle install --without production
```

Install JavaScript dependencies:

```
$ yarn install
```

Next, migrate the database:

```
$ rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly:

```
$ rails test
```

If the test suite passes, you'll be ready to run the app in a local server:

```
$ rails server
```

## Help page

For general help on the Rails Tutorial, see the [Rails Tutorial Help page](https://www.railstutorial.org/help).

