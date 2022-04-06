# typescript-streak-counter
A sample Duolingo-like streak counter.

# `@thestriver/streak-counter` - a sample Duolingo-like streak counter

A sample Duolingo-like streak counter written in TypeScript and meant for the browser (uses `localStorage`).

## Install

yarn add @thestriver/streak-counter

npm install @thestriver/streak-counter

## Usage

import {streakCounter} from '@thestriver/streak-counter'

const today = new Date()
const streak = streakCounter(localStorage, today)
// streak returns an object:
// {
//    currentCount: 1,
//    lastLoginDate: "04/04/2022",
//    startDate: "04/04/2022",
// }
