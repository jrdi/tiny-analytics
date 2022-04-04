# tiny analytics

## Create a Tinybird account

It's free https://ui.tinybird.co/signup!

## Install and configure Tinybird CLI

The Tinybird CLI allows you to use all the Tinybird functionality directly from the command line and allows you to fully integrate your data project with git. 

Instruction to install and configure https://docs.tinybird.co/cli.html

## Push your data project

The following command will create a data source `ds_tiny_analytics` and an endpoint `tiny_analytics`
 
```bash
tb push
```

## Configure your website to send events to Tinybird

More info http://github.com/tinybirdco/tinybird-tracker

## Visualize your data

Go to the retool dashboard and use your `api_token`, created automatically in the push process, to visualize your data. 
