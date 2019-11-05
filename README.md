# Lando-RabbitMQ
A simple Lando RabbitMQ base file

This repo will enable RabbitMQ using Lando.

# How to use

## Starting RabbitMQ
Open a bash/cmd and start lando!

```lando start```

```BOOMSHAKALAKA!!!```

## Web interface 
You can locate the RabbitMQ site at a pre-defined proxy

**proxy:** 

```rabbit.lndo.site```

**Credentials:**

**User:** guest

**Pass:** guest

## RabbitMQ Commands

I've added a lando command to manage RabbitMQ with a simple command line.

Example: ```lando rabbit```

Note: This command can only be run where the ```.lando.base.yml``` is located!

# Custom Settings

To override settings please make an own: ```.lando.yml```
