---
layout: page
title: Schedule
subtitle: Check our race schedule this fall
permalink: /schedule/
custom_js:
 - format-google-calendar.min
 - jquery-2.1.1
---

| Date |      Race     |        Distance       |     Location    |     Conference Race     |
|:----:|:-------------:|:---------------------:|:---------------:|:-----------------------:|
| 8/28 |   [Rocketman](http://teamrockettri.org/rocketman/)   |        Olympic        |  Huntsville, AL |        Conference       |
| 9/11 |    [Hot Dam](http://goraceproductions.com/races/2016-hot-dam-sprint-triathlon/)    |         Sprint        |    Evans, GA    |        Conference       |
| 9/18 | Anchor Splash | (Draft Legal) Sprint |  Oak Ridge, TN  |         Pending        |
| 9/25 |  [Lake Lanier](http://gamultisports.com/lakelanierislandstriathlon/)  |         Sprint        | Lake Lanier, GA |        Conference       |
| 10/8 |  [Rock n' Roll](http://gamultisports.com/rocknrollmanraceseries/olympic/) |        Olympic        |    Macon, GA    | Conference Championship |

Note that with the Hot Dam race falling on Battle at Bristol weekend, we will be unable to send a full team to the race, but if you are interested in going, please let us know!

<ul id="events-upcoming">
</ul>
<ul id="events-past">
</ul>

<script>
formatGoogleCalendar.init({
        calendarUrl: 'https://www.googleapis.com/calendar/v3/calendars/7caamt6q92v1vbrna0ergpoqks%40group.calendar.google.com/events?key=AIzaSyDM0OiBBzeDLq_r9Kni1j8YeQAMfKI69mg',
        past: false,
        upcoming: true,
        sameDayTimes: true,
        pastTopN: -1,
        upcomingTopN: 3,
        itemsTagName: 'li',
        upcomingSelector: '#events-upcoming',
        pastSelector: '#events-past',
        upcomingHeading: '<h2>Upcoming events</h2>',
        pastHeading: '<h2>Past events</h2>',
        format: ['*date*', ': ', '*summary*', ' — ', '*description*', ' in ', '*location*']
});
</script>
