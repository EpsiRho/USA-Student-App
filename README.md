# USA Student App
A better app for navigating school that isn't hot garbage web-views.

# Mission

My college, the University of South Alabama has an app on the app store and google play called "University of South Alabama".

This app... *sucks*. Big time.

It just uses web-views to load the website for every button you click.

Plus the UI just looks abysmal.

So the goal is to make a better one in .NET Maui! One that uses (What little REST APIs they have) to populate a nice looking and easy to use UI for students.

# Hurdles

Most of the info you would get from these sites has little to no REST APIs that can be called. So I will be doing html crawling for some proof of concepts, and hoping to convince the college to do a proper REST API for me to use (or let me make the API for them)

Another hurdle is .NET Maui. This is a very new project type, and is currently (as of 12/27/21) still under development. This may cause issues.

# Prototypes / PoC

All PoCs will be in one app, that will be designed to look finished.

## Version b0.0.1

- [ ] Complete home page interface
  - [ ] Buttons for quick access as soon as you open the app.
    - [ ] Customize what buttons show
  - [ ] Slide over for side menu, shows all options + Settings
- [ ] Settings Page prototype
  - [ ] Contains home button customizer.

## Version b0.0.2

- [ ] USA Dining Site [O](https://usouthal.campusdish.com/)
  - [ ] Shows all on campus places to eat
  - [ ] Shows times they are open, and if they are currently open at a glance
  - [ ] Shows the currently scheduled menu (If there is one)

## Version b0.0.3

- [ ] Quick contacts to campus services
- [ ] Events schedule

## Version b0.0.4

- [ ] USA News
- [ ] USA Socials (Tucked away somewhere)

## Version b0.0.5

TBD



