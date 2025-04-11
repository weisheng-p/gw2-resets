# GW2 Reset Timers
[Reset Timer for GW2](https://weisheng-p.github.io/gw2-resets/)

## FAQs
### what is this?
This are the reset timer for [Guild Wars 2](https://www.guildwars2.com).

I'm using this as a means to test out [temporal api](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Temporal) that are set to be mainstream soon.

### Wait Im not a nightly build how is this working?
This is possible with a [polyfill library](https://www.npmjs.com/package/temporal-polyfill)

If you choose to use them, please be aware of some of the [limitation](https://github.com/fullcalendar/temporal-polyfill/blob/main/packages/temporal-polyfill/scripts/test262-config/expected-failures.txt)

### How does this compare with other existing library
- It works
- APIs are slightly different
- Formatting of dates are not Temporal's responsiblity, so it can be rough

You can at `dayjs` branch to compare the difference in implementations
