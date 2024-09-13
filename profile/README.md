# Starfiles is Going Hydra

## How We Got Here
At Starfiles, we genuinely care about people having access to information and believe censorship is a violation of human rights. We do everything we can in this fight for free information, and we are winning! Starfiles, at the time of writing (09/2024), has served over 30 million file downloads (nearly 2 petabytes or 2048 terabytes). 14 million of which have happened in the last year, despite Starfiles existing for around 7 years. This means 50% of all time usage has happened in the last 15% of Starfiles' existence. This fact is not unique about Starfiles, it has for all of it's existence, been in an exponential state of growth.

## The Problem
From a business perspective, numbers going up is great! But our motivations at Starfiles are not aligned with standard business incentives. As we grow, we start to face new problems. We get new eyes on us, and pressure from outside forces to stop what we're doing, with censorship only increasing. It is important to realise that Starfiles is managed by a small team and we can only deal with so much pressure at a time.  We aren't confident that, at the current rate of growth, Starfiles will be able to exist in a few years.

## Learning From Other People's Mistakes
Many have tried to win the battle for free information & software in different ways, and all have lost. Megafiles was shutdown and forced to comply before re-opening, Bittorrent and Tor have captured 0% of their respective markets, and the Wikileaks founder was kidnapped. There are hundreds more cases just like this. It is important to understand why they failed. It boils down to 2 reasons:
1. Terrible user experience (UX) (e.g. Bittorrent & Tor)
2. Single point of failure (e.g. Megafiles & Wikileaks)

## The Solution
The solution is simple, at least to explain. You need something with a good user experience that doesn't have a single point of failure (decentralisation). In reality, this is a lot harder to achieve. We now face a question. How face we future-proof Starfiles? How can we re-engineer Starfiles to remove it's single point of failure (the team) while maintaing a good UX?

To solve this, we must think about Starfiles at a high level, as being 3 sections:
1. File storage
2. Database+API
3. GUI

### File Storage - Hydrafiles
We have already solved file storage using a technology we created called Hydrafiles. Hydrafiles provides TOR-style privacy for hosts, with zero-UX trade-offs for users. Anyone can clone the [Hydrafiles](https://github.com/StarfilesFileSharing/Hydrafiles) repository and run a node.

### Database+API - B2DB
To solve the database problem our team is currently developing [B2DB](https://github.com/StarfilesFileSharing/B2DB). B2DB is a blockchain that runs SQL instead of money. Our goal with the project (although not yet achieved) is to create a P2P SQL database that can run in a browser with no central authority. If this can be achieved, this technology will allow for many websites requiring a backend to completely replace their backend with a database hosted by their users.

### GUI
Because of the way our GUI has been written, it is impossible to self-host currently. Our team is in the process of rewriting the GUI to allow for self-hosting and third party mirrors.

## Side Note
Although we are focusing on Starfiles' usecases when developing Hydrafiles and B2DB, they are being built in such a way to allow for other projects to take avantage of the progress made by our team.

P.s. If you care about the fight for free software & information and love P2P tech, we would love your contributions.
