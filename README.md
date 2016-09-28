# Sparkling Blog
by [Karen Freeman-Smith](https://github.com/karenfreemansmith) and [Shelby Clayton](https://github.com/shabis)

## Description
a blogging platform built with java, spark and postgres

### User Stories:
* As a user, I want to add a post with information I'd like to share with the world.
* As a user, I want to tag my posts with different categories like "Travel", "DIY", or "Cooking", so posts are easier to find.
* As a user, I want to associate a post with a tag. A post should be able to have many tags and a tag should be able to include many posts.
* As a user, I want to be able to update and delete tags, so I can have flexibility with how I categorize posts.
* As a user, I want to edit my posts, so I can make improvements or corrections.
* As a user, I want to be able to delete posts I no longer like.
* As a user, I want people to be able to add comments to my post.
* As a user, I want to list my posts by which has the most comments, so I can see which posts are popular

### Database Diagram:
![database diagram](database.png)

### Technical Specifications:
* Create, Edit, Delete records in tags table:
  * id, text
* Create, Edit, Delete records in posts table:
  * id, title, text
* Create, Edit, Delete records in posts_tags table:
  * id, postid, tagid
* Create, Edit, Delete records in comments table:
  * id, text, timestamp, (optional parentid if time)

## Setup/Installation

## Known Issues

## Legal
