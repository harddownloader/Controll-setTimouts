
// init Timer:
const timeout = (ms) => new Promise(resolve => window.timerHub.setTimeout('nameThisTimer', resolve, ms));

// use Timer
timeTimout = 25 // in ms
await timeout(timeTimout)

// stop Timers
window.timerHub.stop('nameThisTimer')