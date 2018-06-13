# loopback-course

https://github.com/ChickenKyiv/loopback-tutor-intern-10/issues

First step. Loopback intro

## intro
https://github.com/optis/loopback-rest-api - this is the best tutorial that helps me 1 year ago.

Please buzz me before including MongoDB database - so I'll generate a new instance for you.

As I want to see your progress - please use this repo and push your progress here. Share with me progress and questions that I can help you with. Don't hesitate to use my help. i willing to start fast and with less stress for you at the beginning. Also will check your git skills.


## Is there any timeline to finish?
nope, because you only starting this. and I know how hard it can be from
the beginning. But this is the best tutorial that I find about loopback. I
use it too a year ago.
btw, as usually - feel free and ask any questions or seek my help here.

# invite link
Please use this link in order to be added as a contributor: https://github.com/ChickenKyiv/loopback-tutor-intern-10/invitations

---
raven/sentry configuration

`Raven.config('https://77aa2ee9a7ce484497f56278982a0809@sentry.io/305339').install()`

Init:
https://github.com/GroceriStar/groceristar/blob/master/server/server.js#L17

How to use this tracer:
https://github.com/GroceriStar/groceristar/blob/master/server/server.js#L60

if you'll cover your code well with this tracer - when you'll break something - I'll receive an email notification and will be able to understand more clearly what was goes wrong.

![image](https://user-images.githubusercontent.com/1469198/37542679-b443d8f0-2967-11e8-8d98-7fc3e9aabe6b.png)

---
mongodb link

mongodb://he
roku_b05c1rpf:jl8t2p304u5eokkphv0fof57r9@ds153948.mlab.com:53948/heroku_b05c1rpf

You'll need to have a loopback-connector-mongo package in order to setup it well.

Sample: https://github.com/GroceriStar/groceristar/blob/master/server/datasources.json

---
import

this is the most recent version of import script that i did: https://github.com/ChickenKyiv/recipe-search-api/tree/master/bin

how to run this script: https://github.com/ChickenKyiv/recipe-search-api/blob/master/package.json#L15

not remember - but it can be broken at this moment. If it will crash - buzz me - and i'll finish it - cause i'm lazy to do it.

---
for a few tables - you need to update code.
users and Roles must be assigned together.
some information you can see here: https://github.com/GroceriStar/groceristar/blob/master/bin/grocery/users.js 
it's an old version, but you'll be able to see a main logic.
and this file is called here: https://github.com/GroceriStar/groceristar/blob/master/bin/grocery/import.js#L51

---
run automigrate before calling a mongodb database

when you'll switch from file with data into database - you'll need to run loopback.automigrate method.
i have a samples, so buzz me and i'll move that information here.

#5 

---

Some information about migrations:
**first part**
it's a simple thing, you just need to call automigrate and specify tables that you need to drop.
and you need to run that script from CLI

**second part** is complex and related to importing data from js array into db row.

you will need to create a file/files, with arrays(you can grab that data from db.json file)
then you'll need to create a file where you'll actually import data from array into db.
as before - you should check the latest version at [search-api](https://github.com/ChickenKyiv/recipe-search-api) - and see how i did it here

---
delete db.json


add jest
for testing custom methods api endpoints - not for all generated endpoints.
ind links, related to testing by using jest package at this article: https://medium.com/groceristar/things-that-should-read-and-use-javascript-intern-at-groceristar-april-18-collection-bd6541e9ae28
i want to add testing, so we can easy understand what is working and what is not
