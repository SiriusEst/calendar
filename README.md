# Calendar

Public iCalendar feeds hosted with GitHub Pages.

## Apple Calendar

After GitHub Pages finishes deploying, subscribe with:

```text
https://siriusest.github.io/calendar/UNSW_26T3_Tutorials.ics
```

In Apple Calendar, choose **File → New Calendar Subscription**, paste the URL,
and choose how often Calendar should refresh it.

`UNSW_26T3_Tutorials.ics` is currently a valid empty calendar. Replace its
contents with the real timetable while keeping the filename unchanged; existing
subscriptions will then receive the updated events automatically.

To publish a local update, commit it on `main`, then run:

```sh
./publish
```

The script pushes `main` and fast-forwards the `gh-pages` branch used by GitHub
Pages. When editing on github.com, edit the file on the `gh-pages` branch for the
change to appear at the subscription URL.

This repository is public. Do not add private events or personal information.
