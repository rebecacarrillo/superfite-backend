# superfite-backend


Backend Framework for Superfite, A BJJ event planning and recruiting platform

this document is being edited in Vim. For now, we areusing vim for development. May add on VS Code or Jetbrains later, but I'm vim gal by default.

Gonna containerize this later but for now putting this quick start here:


# QUICKSTART

Python virtual enviromnent: 

`python -m venv env
source env/bin/activate  # (or `env\Scripts\activate` on Windows)'

We're not making a new Django project right now, but if we were, we'd run the following: 
`python -m venv env
source env/bin/activate  # (or `env\Scripts\activate` on Windows)`


-------


Claude has asked me to check in with myself and assess my energy. 

it has also given me the task of updating my natural flow. 

I would like to open this in obsidian, but that's mostly because I want to add a screenshot of what Claude said. I've reached the limit on Claude for free, apparently; lets check out that pricing

# Captain's Log for Jan 31 2025:

What have I accomplished?

 - created Django app
 - configured Vim more (WIP, added nerdtree and syntax highlighting (as seen in the .virmrc), but I'm encoutering some issues
   running certain commands from the command line of Vim. I had to just do those commands in the terminal but quizas it's not woth the effort right now
 - I set up the repo for a new Django project
 - I established naming convetions for tickets

```
- SUP (for general Superfite tickets)
- BE (Backend tickets)
- FE (Frontend tickets)
- INFRA (Infrastructure/DevOps tickets)
- AI (AI/ML feature tickets)
- DOC (Documentation tickets)
- SEC (Security-related tickets)
- DEVOPS (specifically related to development environment, make delete later)
- R&D (research tickets)


``` 

I asked Claude to specifically give me instructions in a trauma informed way. Eventually,I should include all the output from the chats and my prompts and put them somewhere where I'm documenting my Decision making. There should be a decision making folder in this repo as long as it remains open source

# SHIFT G TO GO TO THE END OF THE FILE IN VIM

---

As I was documenting, I kept thinking about Maya history topics that I wanted to talk about. 
What do I love talking about?

I know it's probably weird of me to refer to my Maya special interest here in the readme of a completely unrelated project, 
but Integration is the name of the game. That's why I'm doing it.

---

02/01/2025

I need a physical quickstart to get setup on this project -- an actual step by step guide. Long term, I'd like to create
a Docker container and some default pieces, but that's out of scope for now

Had a bit of a bug with HTTPS versus SSH authentication. Turns out I had the wring prefix in the call.

I think I should take a break. Salami is watching the screen as I write. maybe let's put the writing in a seperate folder but w/ever. Right now it's time for a break

----

I've updated the prefix list to include DEVOPS. I did this to differentiate tasks like "research AWS" from Infra tasks like "Create a docker container and put it on an EC2 Instance" or something 

As I was doing that I realized research should get a prefix too. Can I add the amperasand in the labels, though --- that's the real question. This train of thought camecame from making a ticket to research AWS Activate

