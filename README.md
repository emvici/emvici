findhit-emvici
=====================

emvici is an open-source javascript MVC framework for developers

Our goal is to make the web faster and reliable for all persons on earth (and maybe on other planets too).

So we packed a plugable framework with all the needs for developers:
* Easy to learn, as **jQuery**;
* Class based, you can extend capabilities of other classes on your class, AWESOME.
* Plugable, so you won't need to download jQuery, probably we will do a plugin for that!
* Social intended, we will handle logins, passwords and emails for you! :)
* Open-Source, it means that you can help others on your knowledge contributions!

## What does **emvici** means?

**emvici** is inspired on **MVC** pattern which stands for **Model**, **View**, **Controller**.

Usually **MVC** is used often on server-side and on client-side, there are tons of frameworks for each side, but the problem is to bind all of them on a single working project.

Some problems might be:
* Views folder tend to be confused with multiple folders for multiple proposes (like: Email views, Layouts for them, Server Generated Views, Layouts for them and Client Generated Views)
* Models will turn huge files on large projects because Controllers should stay only with basic evaluation.
* Controllers are hard to organize since they can process each request type for a single kind of task, then you wont know if you should create an API Controller or populate API methods on each Model's Controller... sick.

Then we have think if there was a way of creating a framework that we won't need to supply and bind plugins and handle all the heavy lifting, and then was when **emvici** was born.

We arranged a way of connecting everything and handling transports between server and client sides, for more information about file's structure please check out our [findhit-emvici-skeleton](/findhit/findhit-emvici-skeleton) repo. (This repo is used by **emvici** on `emvici create [project-name]` command)

## Instalation

```bash
npm install findhit/findhit-emvici -g
```

## Usage

```bash

emvici create projectname
cd projectname/

npm install -g

projectname serve

```