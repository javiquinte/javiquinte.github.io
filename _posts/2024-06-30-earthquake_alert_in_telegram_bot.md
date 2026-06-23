---
layout: single
title: "Early Alert of Earthquakes"
categories: Science
header:
  teaser: "/assets/images/telegrambot.png"
gallery:
  - url: /assets/images/telegrambot.png
    image_path: /assets/images/telegrambot.png
    alt: "Early Alerts in Telegram"
    title: "Early Alerts of Earthquakes in Telegram"
---

During the last years I have been running a [Telegram bot][TelegramBot] with early warnings of earthquakes
from the GEOFON data centre.
The positive aspect of this bot is that the warning can be sent as early as the earthquake is
confirmed. As the magnitude calculation (and also the epicenter) is an iterative process and evolve
in time, this bot has the capability to silently update the message with the latest information.
Therefore, the user can always see the most updated data without paying the cost of an early
alert. Speed AND accuracy... 😉

{% include gallery %}

[TelegramBot]: https://t.me/geofonall
