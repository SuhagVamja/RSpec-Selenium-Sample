# rspec-browserstack
[Rspec](http://rspec.info/) Integration with LambdaTest.

![LambdaTest Logo](https://www.lambdatest.com/static/images/logo.svg)

<img src = 'http://rspec.info/images/logo.png' height="95">


## Setup
* Clone the repo
* Install dependencies `bundle install`
* Update `*.config.yml` files inside the `config/` directory with your [LambdaTest Username and Access Key](https://automation.lambdatest.com/)

## Run the tests
* To run a single test, run `bundle exec rake single`
* To run parallel tests, run `bundle exec rake parallel`

 To know how many concurrency you need by using our [Concurrency Calculator](https://www.lambdatest.com/concurrency-calculator)

## Notes
* You can view your test results on the [LambdaTest Automate dashboard](https://www.automation.lambdatest.com)
* To generate capabilities for different set of browsers, check out our [capability generator](https://www.lambdatest.com/capabilities-generator/)
* You can export the environment variables for the Username and Access Key of your LambdaTest account

  ```
  export LT_USERNAME=<your username> &&
  export LT_ACCESS_KEY=<your access-key>
  ```