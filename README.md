# Getting Started

To get started with the app, clone the repo and then install the gems as needed

- - -

$ bundle install --without production

- - -

Then migrate the database

- - -

$ rails db:migrate

- - -

Then run the test suite to verify that everything works

$ rails test

- - -

If the test suite passes, you can run the app in a local server

- - -

$ rails server