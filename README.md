# FightBikeTheft
Bike owners' repo for building tools that proactively fight bike theft
* This is based in Denver and focuses there for now!

Bike theft is easy with the right hardware and hard to prevent or fight. 
The police do only what they can. Registries are low-tech. Pawn shops can easily enter bad serial numbers to 
avoid thefts being discovered. 
Let's build great software to fight bike theft!

## Requirements & Installation
Nothing yet!

## What Problems Can we Realistically Tackle
Fighting a bike theft after the fact is hard. A lucky few receive their bikes back in return after hours of scouring websites that might be selling the bikes and dealing for hours with the lack of effort police detectives are willing/able to put in.

### Better Registry
The Denver Bike Registry sucks. It's clunky, slow as hell, and I've never heard of anyone getting their bike back due to it being registered. It's used only as "proof" that you own the bike, but providing the serial number should be enough, so it doesn't really solve that problem.
Let's build our own registry. It should be as simple as personal attriutes (name, etc), Bike Serial Number, Brand, Model, and comments/notes. Perhaps add existing police report number as an optional?
##### What do we need 
- Where do we host this?
- Need UI dev. Mobile too?
- Can we get this data from bike shops automatically?
- Can we scrape any existing databases? Denver database?
##### What does this solve
As we build this up it could replace any existing database. It could assist with bikes being sold outside the area / state it was stolen from.
We can let OfferUp, Marketplace, etc use our database to flag bikes as stolen when posts are created. 


### Work with Marketplace Apps
Maybe some legal/business-savvy folks could help us get bike posts require a serial number, brand, model, etc on Marketplace apps. 
If we do something similar with Pawn Shops, if they enter a serial number that doesn't match the brand/model

A recent post on this page informed me that pawn shops often enter faulty serial numbers, which makes the bike registry a lot less effective. Also, sites like OfferUp and MarketPlace do not require serial number.
Solution - Fight to require Serial Number, Brand, and Model at both Pawn Shops and on online sellers (any legal savvy folks out there know how to get that started??). The techies should focus on building tools that take in bike registry data, as well as data matching serial numbers to brands/models (can we get that?)
