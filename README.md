# Calendar

Public iCalendar feeds hosted with GitHub Pages.

## Apple Calendar

Subscribe to either calendar with:

```text
COMP3331 26T3 Tutorials:
https://siriusest.github.io/calendar/UNSW_26T3_Tutorials.ics

myTimesheet reminders:
https://siriusest.github.io/calendar/myTimesheet-reminders-2026_1.ics
```

In Apple Calendar, choose **File → New Calendar Subscription**, paste the URL,
and choose how often Calendar should refresh it.

Keep each filename unchanged when updating it so existing subscriptions receive
the new events automatically.

To publish a local update, commit it on `main`, then run:

```sh
./publish
```

The script pushes `main` and fast-forwards the `gh-pages` branch used by GitHub
Pages. When editing on github.com, edit the file on the `gh-pages` branch for the
change to appear at the subscription URL.

This repository is public. Do not add private events or personal information.
