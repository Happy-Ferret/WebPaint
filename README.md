# WebPaint
## _Draw and Save Your Doodles online_!

Webpaint is an drawing Web App where you can save your drawings for opening them up later!.

### Used technologies:

- A lot of Vanilla JS, [EcmaScript 6](https://www.ecma-international.org/ecma-262/6.0/index.html) and a little bit of [jQuery](https://jquery.com/)
- The [JavaScript Processing Framework](https://p5js.org) (p5.js) for drawing
- [Twitter Bootstrap](https://getbootstrap.com/) as CSS framework
- [Font Awesome](https://fontawesome.com/) for the social icons
- [Firebase Realtime Database](https://firebase.google.com/docs/database/) for data storage i.e. saving the doodles
- [Firebase Hosting](https://firebase.google.com/docs/hosting/) for deployment

## Current Features

- Doodle Download (jpg)
- Save doodle to database
- Load currently saved doodles
- Open up a saved doodle

![Landing Page](/screenshots/landing.png)

## ToDo

There is still a lot of work to be done.

A few ideas are:

- Color and stroke palette
- Saving with author name and doodle name
- Load view filtering
- Loading by id parameter (in url)
- Geometric palette (rectangles, circles etc)
- User Authentication (User system for saving private doodles for example)

Feel free to submit your own ideas with a Pull Request!
-

## Local Build

1. Clone the repository (I personally adopted to use SSH for git)
```
git clone git@github.com:Pl4gue/WebPaint.git
```
2. Install npm packages
```
npm install
```
3. Deploy locally using Firebase Hosting
```
firebase serve
```
4. Access your local build on `localhost:5000`.

# Contribute

Feel free to submit a PR at any time, no matter if it's an enhancement of your own, one of the ToDo-features from above or just a simple bug fix!