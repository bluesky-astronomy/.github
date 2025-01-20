# Astronomy on Bluesky

This organization is a collection point for various open source projects built by & for the astronomy community on Bluesky.

Currently, we have four active, running web projects; three of which relate to our feeds, and one of which is an outreach bot.

## The Astronomy Feeds

We maintain [the Astronomy feeds](https://bsky.app/profile/emily.space/feed/astro), which are a set of 'custom algorithms' that collate astronomy content on Bluesky. These feeds are moderated and come from a curated list of users. Any 'astronomer' - be they professional, amateur, a student, left the field, a science communicator, etc - is welcome to sign up to post to them!

The Astronomy feeds have over a thousand people signed up to post to them and are seen by tens of thousands of unique users daily. A typical week has around a thousand posts and many discussions stemming from them.

These feeds are supported by multiple projects, which live in the [astronomy-feeds](https://github.com/bluesky-astronomy/astronomy-feeds) repository. They're powered by the [ATProto Python SDK](https://github.com/MarshalX/atproto). Our feed library includes a Bluesky firehose client, a Flask server for serving posts, and a bot for handling signups and moderation.

The [rules](https://github.com/bluesky-astronomy/rules) for our feeds and [branding](https://github.com/bluesky-astronomy/branding) resources (i.e. the feed icon) also live in this GitHub organisation.


## Associated bots

We are also developing a number of fun bot accounts to post interesting automated content. Currently, the running bot accounts not directly involved with the running of the feeds are:

- [Galaxy-Zoo-Poster-Bot](https://github.com/bluesky-astronomy/Galaxy-Zoo-Poster-Bot): a bot that posts images hourly that have been classified by volunteers in the Galaxy Zoo survey.
