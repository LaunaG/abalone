# Abalone Analysis
A Ruby on Rails application for tracking and analysis of data related to the monitoring of abalone populations. Currently live at [abalone.blrice.net](http://abalone.blrice.net/).

## Getting Started

### Prerequisites
This application is built on following and you must have these installed before you begin:
* Ruby (2.6.3)
* Rails (5.2)
* PostgreSQL (tested on 9.x)

### Setup
After cloning this repo, execute the following commands in your CLI:
```

```

## Deployment
The application is currently deployed on a DigitalOcean droplet via Capistrano. Once your public SSH key has been added to the appropriate user on the necessary server(s), use `bundle exec cap production deploy` to deploy the application, run migrations, and restart the Puma application server. Puma is reverse-proxied behind Nginx. The Nginx configuration is currently maintained outside of the Rails development pipeline.
