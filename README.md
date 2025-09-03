# Stonxe

## Original conditions
* What is published cannot be edited or deleted.
* The person posting must have a valid account (onboarding).

## Afterthoughts
* To validate accounts, in addition to onboarding, it could be validated by credit card.

## Problems
* Those who use Twitter use it for anonymity.

## Possible solutions
* It offers a 10-pack for $1.10 per month. This allows you to follow 10 people, with each person following earning 10 cents, and the platform earning 10 cents for the infrastructure/business.
* Create the concept of angels and demons. Demons that don't require onboarding and can pay with crypto. A demon's post will have replies from other demons first, and vice versa.
* 3 views (general and into answers), to filter by light blue, purple, or red, to see only messages from angels, mixed, or demons. (background bar gradient).
* Messages with stars. 1 star is public, 2 stars are sensitive content, and 3 stars are for police.
* Add screenshot from shared links.
* Allow add answers before confirm send message (with counter 10'' allowing cancel), to create a thread.
* Allow set message as sensitive content before send it. Allow other users to flag message as sensitive.
* LIKE: 8 light blue / 42 violet / 34 red. DISLIKE: 22 light blue / 245 violet / 223 red.
* Allow select display messages into answers (only angels/mix/only demon)
* Add icon for define a user as angel or demon.
* Add icon like an sphere white or black. Karma define the color. Only LIKE/DISLIKE of Angels can define the karma value. Click on karma list Angels likes. (use total counter and a separated table for each user).
* Sort answers by timestamp.
* When an user A write a message, and other B answer it (only Angel or if demon, hide challenge for all, and wait autorization from thread owner), if the answer have more 25% likes (that original message):
   The system automatically start the challenge. The challenge consists in push sub thread to challenge section, allowing only answer user A, next B, next A etc.
* Support private and public groups, private messages, # hashtags and mentions @
* Convert answer into challenge if owner thread answer it.

## Infrastructure
* Cloudflare + N Pomerium Load Balancer + N NginX with Python Fast API + N Cassandra
* Model the tables messages by country and by person (duplicate)
