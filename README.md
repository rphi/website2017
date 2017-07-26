# SIG: Web - website2016
This is the new website for [CompSoc Edinburgh](http://comp-soc.com).

Built by SIG: Web, Making the Web(site) Great Again.

## How to test
It uses Jekyll. It also works nicely with Docker.

If you use Linux or macOS, run `preview.sh`. It will automatically build, server and watch the directory for changes. It will listen on port 4000.

If you're on Windows, please contribute some instructions. You'll hopefully be able to read `preview.sh` and adapt the commands to play nice with docker-machine, or native Docker if that's your thing.

### Running without Docker
If you have `bundler` installed, type:

- `bundler`, to install the Gemfile packages
- `bundle exec jekyll build --watch` to build and watch the directory for changes

# About the SIG
## What is SIG: Web
SIG: Web is a Special Interest Group of CompSoc, centered around re-building the CompSoc website.

## Goals
* Building & maintaining the new website
* Exploring interesting web technologies, where implementations of which could benefit CompSoc and members (where implementations would be at the discretion of CompSoc's current technical secretary)
* Help members to learn web technologies and web development best practices

## Sounds good, what now?
This page lists some first ideas around what we might need/want for the website, until we can put together a first formal meeting, which will probably be late May / early June 2016.

## Join us <a href="https://www.irccloud.com/invite?channel=%23sigweb&amp;hostname=irc.imaginarynet.uk&amp;port=6697&amp;ssl=1" target="_blank"><img src="https://www.irccloud.com/invite-svg?channel=%23sigweb&amp;hostname=irc.imaginarynet.uk&amp;port=6697&amp;ssl=1"  height="18"></a>

#### Meetings
Meetings will be held on a monthly basis, in person. Meetings will also have a web conference open in the event that a SIG member wishes to join remotely. As such, the meeting venue should be suitable to accommodate this.
#### Online
We hang out in #sigweb on Imaginarynet (irc.imaginarynet.uk), come say hi, have a chat. For now we're throwing around basic ideas of what technology stacks we should consider, and generally are just getting ideas out to others in the group for discussion at our first meeting, where we will start a formal plan.

## Ideas
What follows are some of the key features we have already identified for needs of the new website
* Must be easy to contribute to
* Must be easy to set up / deploy

With those ideas there, some technologies identified that could be of use:
* Docker (for ease of setting up, especially for contributors)
* Jekyll (Can you write text? Then you can contribute!)
* Micro web frameworks (Sinatra/Flask)

We also think it might be nice to have a look at using Bourbon / Neat / Bitters / Refills alongside Sass for laying things out as well, but that's up for discussion :heart:
