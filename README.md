## Description:

_An app that has a few plus(+) and minus(-) buttons and a counter value info. if press (+) or (-), the counter value info will be increased or decreased accordingly._

## Tech Stack:

**React.js: -** _React.js is a popular front-end open-source Javascript library for building dynamic & interactive user interfaces._

**Tailwind CSS: -** _Tailwind CSS is a utility-first CSS framework designed for rapidly building custom user interfaces._

**Next.js (app-router): -** _Next.js is an open-source, lightweight & powerful React's Production-rate framework. Designed for building highly performant and scalable web applications. This ReactJS framework for building server-side-rendered & client-side-rendered web applications. It includes a number of features that file system-based routing, really Fast, universal rendering & such Image Optimization._

**Lucide Icon: -** _Lucide is an open-source icon library that provides a consistent & customizable set of vector(SVG) files for displaying icons and symbols in digital and non-digital projects._

**Shadcn-UI: -** _Shadcn is an open-source & offering a collection of high standards customizable, accessible, modern, responsive, & reusable UI components library for web applications._

**Next-themes: -** _next-themes is a React library that simplifies theme implementation in applications. It provides a complete solution for theme management, including dark/light modes, system preference detection, and theme persistence._

## Features:

1. **Dark mode: -** _To change the mode of the application._
2. **Navigation Links: -** _To Navigate in three pages on the application ._
3. **Counter Value Display: -** _To display the calculated value._
4. **Three Types of Counter: -** _To feel basic to advance and expert level of counting._

## Explanation:

**App Name: -** _Counter App_
**Pages/Levels: -** _3 pages: Basic, Advanced, Expert._
**Navigation: -** _All pages are accessible via a Navbar._
**Common Component: -** _All 3 pages use a Card component._
**Logic: -** _In the folder here contains 3 components where all the logic is handled._
**State: -** _Each of the 3 component has a local-state(useState) defined with count and setCount._

**Page Details:**

1. **Basic Page: -**

- _This page will be the homepage of the app._
- _It will display the current counter value._
- _It will have two buttons: (+) to increase the count and (-) to decrease the count._
- _There are no limits on the counter value._

2. **Advanced Page: -**

- _This page will display the current counter value._
- _It will have four buttons: (+), (-), (+10), and (-10)._
- _There are no limits on the counter value._

3. **Expert Page: -**

- _This page will display the current counter value._
- _It will have four buttons: (+), (-), (+10), and (-10)._
- _The counter value must be between 0 and 100, inclusive._
- _The buttons should be disabled based on the counter's value._
- _When the count is 0, the (-) and (-10) buttons must be disabled._
- _When the count is 100, the (+) and (+10) buttons must be disabled._

    **Event Handling: -** _Button onclick events trigger functions that use setCount to update the counter value._
    **Basic & Advanced Logic: -** _No limits on the counter value (can increase or decrease indefinitely)._

    **Expert Logic: -**

- _The counter value cannot be negative or greater than 100._
- _Buttons are disabled based on the counter value._
- _If count is 0, the (-) and (-10) buttons are disabled._
- _If count is 100, the (+) and (+10) buttons are disabled._

## App Structure:

_1. The app should have three pages that a user can navigate between using a Navbar._
_2. Each of the three pages should use a Card component._
_3. All the logic and functionality for the counter will be handled in three separate components located in a Logic folder._
_4. In each of the three logic components, a state should be defined with a count variable and a setCount function to track the counter's value._
