---
layout: essay
type: essay
title: "UHM Event Locator"
# All dates must be YYYY-MM-DD format!
date: 2022-11-01
published: true
labels:
  - Software Engineering
  - JavaScript
  - Meteor
---

*In collaboration with [Evan Araki](https://evanaraki.github.io/) and [Melvin Alhambra](https://melvinjae.github.io/)*

## Overview

*Problem*: UH Manoa is a large campus with many events that students may attend. Students not familiar with the campus may not know where certain buildings are. Some events may or may not pique people’s interest and just might not be aware of them.

*Solution*: This application shows what events-open to the public-are happening around campus on a specific day [giveaways, free samples, competitions, etc.].

## Mockup

- Navbar that lets you browse events by specific tags/broad categories
- Landing page
- Login Page for site managers/organizations that want to post events
- Form to submit event
- Admin/organization home page
- Calendar page 
- Events page 
- Title 
- Description 
- Location (some kind of maps api)
- Photos (optional) 
- RSVP (if it has)

## Case Ideas

- User browses landing page and looks at event info
  - user >> Landing page. Displays events relevant to day / broad interests (ie: music festival) >>  click on event from list >> event details page
- User searches for specific events and looks at event info 
  - user >> landing page >> use nav bar to search by tags >> list of events with relevant tags >> event details page
- Organization wants to submit an event 
  - Admin >> admin login page >> admin home page >> submit form to site managers for approval to be event host >> account receives authentication >> create event post through admin home page
- Site managers approve submissions and decide if organization is legit 
  - Site manager >> admin login >> admin home page >> can view any admin requests, can view and edit users, can view and edit events (moderation purposes)


## Beyond the Basics

- Map API integration to view location of events
- Messaging system interface
- User file upload (images)
