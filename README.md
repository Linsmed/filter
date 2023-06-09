# Frontend Mentor - Job listings with filtering solution

This is a solution to the [Job listings with filtering challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/job-listings-with-filtering-ivstIPCt). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page
- Filter job listings based on the categories

### Screenshot

![](./jobList.PNG)

### Links

- Solution URL: [Add solution URL here](https://https://github.com/Linsmed/jobs-list)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

-This project was built with react using vite

## Installation

-git clone https://github.com/Linsmed/jobs-list.git

### npm install

### npm run dev

### Built with

- Semantic HTML5 markup
- Tailwind CSS
- [React](https://reactjs.org/) - JS library

### What I learned

I learnt more on how to use conditional rendering.See example of code below

```jsx
 const { jobs, handleFilter, jobClicked, setJobClicked } = props;

  return (
    <div className="py-3 sm:px-20 px-5 max-w-7xl mx-auto">
      <div className="bg-white py-5 px-10 lg:flex lg:justify-between items-center drop-shadow-2xl rounded-lg">
        <div className="lg:flex gap-5 items-center">
          <div className="lg:mt-0 -mt-12">
            <img src={jobs.logo} alt="" className="w-14 lg:w-full" />
          </div>
          <div className="flex pb-1 pt-1">
            <div>
              <div className="flex gap-3 pb-1">
                <h1 className="text-darkCyan font-bold pt-1 text-md">
                  {jobs.company}
                </h1>
                {jobs.new && (
                  <div className="text-white text-sm bg-darkCyan rounded-full font-bold flex items-center px-2.5 my-0.5">
                    NEW!
                  </div>
                )}
                {jobs.featured && (
                  <div className="text-white bg-veryDarkCyan flex items-center px-2.5 rounded-full font-bold text-sm my-0.5">
                    FEATURED
                  </div>
                )}
              </div>
              <div

```

In all,this project has made me to be more comfortable with tailwindCss and react

### Continued development

I am still hoping to be more comfortable with the use of hooks and to be able to play around with my custom hooks.

- [Example resource 1](https://https://www.w3schools.com/react/react_hooks.asp) - This helped me to understand hooks in react. I really liked this pattern and will use it going forward.
  I also make use of stack overflow whenever I get stuck.

## Author

- Website - [Ejibode Ibraheem A](https://www.your-site.com)
- Frontend Mentor - [@Linsmed](https://www.frontendmentor.io/profile/Linsmed)
- Twitter - [@EjibodeI](https://www.twitter.com/EjibodeI)

## Acknowledgments

I will want to express my profound gratitude to the initiators of ADA software engineering programme,Enugu for giving the rare privilege to partake in this internship programme.I must say I have really learnt a lot within this 7 months.The sky is the starting point for me.
Special thanks to our facilitator,Ada,who has been lenient with us and has never get tired in providing solutions for us whenever I get stuck.
