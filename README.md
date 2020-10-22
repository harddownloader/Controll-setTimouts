
<!-- init Timer: -->
const timeout = (ms) => new Promise(resolve => window.timerHub.setTimeout('nameThisTimer', resolve, ms));

<!-- use Timer -->
await timeout(25)

<!-- stop Timers -->
window.timerHub.stop('nameThisTimer')