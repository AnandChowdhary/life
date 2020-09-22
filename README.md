# 🧬 Anand's Life

This repository contains the data for [Anand Chowdhary](https://anandchowdhary.com)'s life. It's based on [Stethoscope](https://github.com/stethoscope-js/stethoscope), my template to track your health and life data.

[![Powered by Stethoscope](https://stethoscope.js.org/branding/badge-small.svg)](https://stethoscope.js.org)
[![Stethoscope CI](https://github.com/AnandChowdhary/life/workflows/Stethoscope%20CI/badge.svg)](https://github.com/AnandChowdhary/life/actions?query=workflow%3A%22Stethoscope+CI%22)
[![Update Template CI](https://github.com/AnandChowdhary/life/workflows/Update%20Template%20CI/badge.svg)](https://github.com/AnandChowdhary/life/actions?query=workflow%3A%22Update+Template+CI%22)

**View my life data: https://anandchowdhary.com/life/**

## 🌟 Services

<!-- prettier-ignore-start -->
| Service |
| ------- |
| <img alt="" src="https://cdn2.iconfinder.com/data/icons/social-icon-3/512/social_style_3_lastfm-512.png" width="12"> Last.fm |
| <img alt="" src="https://images.weserv.nl/?url=https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcS5cnw0MQF7TnpSzlRTlIC6z4EHDEPP3B8qBw&usqp=CAU&w=64&h=64&fit=cover" width="12"> Rescue Time |rescuetime) |
| <img alt="" src="https://cdn.worldvectorlogo.com/logos/wakatime.svg" width="12"> Wakatime |
| <img alt="" src="https://images.weserv.nl/?url=https://lh3.googleusercontent.com/23K9TDTOdlo57Pi9JvNtPc9K-utruK6jQEpQGD_E4QBLRJYRAgLcC7gF2Rd_0T1qhLLS&w=64&h=64&fit=cover&mask=circle" width="12"> Pocket Casts |
| <img alt="" src="https://www.gstatic.com/images/branding/product/1x/gfit_512dp.png" width="12"> Google Fit |data/health) |
| <img alt="" src="https://images.weserv.nl/?url=https://static1.ouraring.com/images/symbol-oura-large-white.svg&w=64&h=64&fit=cover&mask=circle" width="12"> Oura Ring |
<!-- prettier-ignore-end -->

## 📊 Data explorer app

To use the web app, you have to visit a URL like the following:

https://stethoscope.js.org/embed/?repo=AnandChowdhary%2Flife&api=rescuetime-time-tracking&latest=top-overview.weeks

In the above example, the query parameters are the following, URL encoded:

- `repo`: Your repository on GitHub, e.g., `AnandChowdhary/life`
- `api`: The data you want to visualize, e.g., `rescuetime-time-tracking`, which corresponds to the directory in [`./data`](./data)
- `latest`: The visualization to display, based on the specific `api.json` keys, e.g., `top-overview.days`

Here are some more visualization of real-time data from my life:

- Sleep tracking: [this week](https://stethoscope.js.org/embed/?repo=AnandChowdhary%2Flife&api=oura-sleep&latest=total.weeks) · [this month](https://stethoscope.js.org/embed/?repo=AnandChowdhary%2Flife&api=oura-sleep&latest=total.days) · [this year](https://stethoscope.js.org/embed/?repo=AnandChowdhary%2Flife&api=oura-sleep&latest=total.months)
- Programming time: [this week](https://stethoscope.js.org/embed/?repo=AnandChowdhary%2Flife&api=wakatime-time-tracking&latest=weeks) · [this month](https://stethoscope.js.org/embed/?repo=AnandChowdhary%2Flife&api=wakatime-time-tracking&latest=days) · [this year](https://stethoscope.js.org/embed/?repo=AnandChowdhary%2Flife&api=wakatime-time-tracking&latest=months)

This is a real-time screenshot of the above RescueTime weekly overview URL:

[![Screenshot of visualization](https://api.microlink.io/?url=https%3A%2F%2Fstethoscope.js.org%2Fembed%2F%3Frepo%3DAnandChowdhary%252Flife%26api%3Drescuetime-time-tracking%26latest%3Dtop-overview.weeks&waitFor=5000&waitUntil=networkidle2&screenshot=true&meta=false&embed=screenshot.url&device=ipadlandscape)](https://stethoscope.js.org/embed/?repo=AnandChowdhary%2Flife&api=rescuetime-time-tracking&latest=top-overview.weeks)

## 📄 License

- Based on: [stethoscope-js/stethoscope](https://github.com/stethoscope-js/stethoscope)
- Code: [MIT](./LICENSE) © [Anand Chowdhary](https://anandchowdhary.com)
- Data in [`./data`](./data): [Open Database License](https://opendatacommons.org/licenses/odbl/1-0/) © [Anand Chowdhary](https://anandchowdhary.com)
