

To get started with the app, clone the repo and then install the needed gems:

```
$ cd ~/tmp
$ git clone https://bitbucket.org/railstutorial/sample_app_4th_ed.git sample_app
$ cd sample_app
$ bundle install --without production
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