# Ridiculously Simple App Engine

Absolutely the simplest App Engine web app I could imagine. 

No backend. Everything goes through the .yaml file. 

Static files go in the /static folder. Nothing but a favicon.

## Local server server

	dev_appserver .

## Deploying

Replace [app id] with your very own App Engine id.

	gcloud app deploy app.yaml --project [app id] --version 1

## Why did I do this?

This is part of a series of ridiculously simple, executable code examples. 

Sometimes we need to cut through the documentation jungle and get to making stuff.

## Credits

Jude Osborn
