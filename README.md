# Brady Buten — Portfolio

Personal portfolio site: [bradybuten.github.io](https://bradybuten.github.io)

A single-page site covering robotics and controls work: an autonomous turkey-deterrent robot (UKF, A*, MPC), a Sartorius-sponsored live cell incubator build, vehicle controls at Equipment Technologies, and vision/PLC integration at GM Factory Zero.

## Structure

- `brady_portfolio.html` — the entire site (HTML, CSS, and JS in one file, no build step)
- `Media/` — images, video, and PDFs referenced by the site, organized per project

## Running locally

Open `brady_portfolio.html` directly in a browser. No dependencies, no build step required.

## Routing

The site uses hash-based routing (`#turkey`, `#home`, `#incubator`, `#gm`, `#et`, `#linkage`, `#motionpaint`), so any project page can be linked to directly. The bare URL loads the Turkey Bot project by default.
