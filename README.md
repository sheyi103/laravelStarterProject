<p align="center"><a href="https://laravel.com" target="_blank"><img src="./retailcode_logo.png" width="400"></a></p>

<!--<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>-->

## RetailCode (API Service)
RetailCode is a real time Electronic Voucher Distribution (EVD) for Airtime, Data amd Bills.


## Installtion

### Prequisite
* Docker Desktop (Mac OSX or Windows)

### Download Code
Ensure that you hace write access to the codebase, then run the following command.

```
git clone git@github.com:FBIS-Tech/retailcode-service.git
```

### Run
Ensure that Docker is running and then run the following command:

```
cd retailcode-service && ./vendor/bin/sail up
```

App runs on `locahost` port `80`. Visit `localhost` on your browser and see app running.
You can make changes to app code and still it reflect on your browser.



## Contributing to RetailCode
We love your input! We want to make contributing to this project as easy and transparent as possible, whether it's:

- Reporting a bug
- Discussing the current state of the code
- Submitting a fix
- Proposing new features
- Becoming a maintainer

### We Develop with Github
We use github to host code, to track issues and feature requests, as well as accept pull requests.

### We Use [Github Flow](https://guides.github.com/introduction/flow/index.html), So All Code Changes Happen Through Pull Requests
Pull requests are the best way to propose changes to the codebase (we use [Github Flow](https://guides.github.com/introduction/flow/index.html)). So pull requests are welcomed.

1. Clone the repo (request access if you do not have one) and create your branch from `main` or `master` or `dev` as the case may be.
2. If you've added code that should be tested, add tests.
3. If you've changed APIs, update the documentation.
4. Ensure the test suite passes.
5. Make sure your code lints.
6. Issue that pull request!
7. Get at least on or two peer reviews


### Report bugs using Github's [issues](https://github.com/briandk/transcriptase-atom/issues) or Jira Issues as the case may be.
We use GitHub issues to track public bugs. Report a bug by [opening a new issue](); it's that easy!

## Write bug reports with detail, background, and sample code
[This is an example](http://stackoverflow.com/q/12488905/180626) of a bug report for reference purposes. Here's [another example from Craig Hockenberry](http://www.openradar.me/11905408), an app developer whom I greatly respect.

**Great Bug Reports** tend to have:

- A quick summary and/or background
- Steps to reproduce
  - Be specific!
  - Give sample code if you can. [My stackoverflow question](http://stackoverflow.com/q/12488905/180626) includes sample code that *anyone* with a base R setup can run to reproduce what I was seeing
- What you expected would happen
- What actually happens
- Notes (possibly including why you think this might be happening, or stuff you tried that didn't work)

People *love* thorough bug reports. I'm not even kidding.

### Use a Consistent Coding Style
we use Udacity Git Commit Message Style [Udacity Git Commit Message Style Guide](https://udacity.github.io/git-styleguide/). so ensure that your commit messages are in line with the guide above before creating pull request.

* 2 spaces for indentation rather than tabs
* Ensure code is porperly formated before creating pull requests
* Remove unused imports/includes and lines of code as well as debug logs.
* Add proper loggin if need be

## Code of Conduct

In order to ensure that all contributions is welcomed, please review and abide by the [Code of Conduct](https://docs.google.com/document/d/1kP9Qhr4fCh6oUNi7TNOgeyaV0H6tvu5r43io8yGfbVw/edit?usp=sharing). 

Note: Open the link with yuor company Google email account.
