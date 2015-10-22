# Exercise 3

## Logging into your new instance

In this exercise we're going to remotely log into the new EC2 instance that we just created. To do this we'll need to use PuTTY and to convert the SSH key we downloaded in exercise 2.

*****

> Ordinarily I'd just 
> 
> ```
> cp keyfile ~/.ssh/
> chmod 600 ~/.ssh/
> ssh -i ~/.ssh/keyfile ec2-user@ip-address
> ```
> 
> With PuTTY you need to do something with the keyfile to get it to work (turn it into a PEM file?), then tell PuTTY to use that file to connect to the IP address as the given user. I don't have a windows machine to test this on, so will need someone to research this, note down the steps and (ideally) grab some screenshots.
