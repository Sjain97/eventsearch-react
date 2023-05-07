# *EventSearch - React web app*

By: **Shubham Jain**

EventSearch is an end-to-end web app for finding the next happening event. The app lets users search events, mark
favorites and view the relevant event/artist details in neat cards.

## Features

The following functionality is completed:

- [x] React Router for single-page application (web-app never reloads the entire page)
- [x] Config-driven UI -- only show fields that have data
- [x] Redux is used for central data-store to avoid props-drilling
- [x] Auto-detect location using ipInfo API
- [x] Events table showing events in date/time sorted order
- [x] Custom hook to fetch event details
- [x] LocalStorage used to store favorite events
- [x] Back button on Event Card that re-renders the table (not another API call)
- [x] Spotify API used for getting music-related artist details
- [x] Use of Context to identify current tab
- [x] Modal to display map location	(GoogleMaps API)
- [x] Custom Proxy Server for Backend using Node.js (hosted on GCP)

## <a href="https://shubham-jain-events-webapp.wl.r.appspot.com/search" target="_blank">Link to live web-app</a>

## Video Walkthrough

Here's a walkthrough of implemented user stories:
[YouTube Link](https://www.youtube.com/watch?v=ns_cB8L1uT4)

<img src='https://github.com/Sjain97/eventsearch-react/blob/main/event-search-react.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [Kap](https://getkap.co/) for macOS


## License

    Copyright [2023] [Shubham Jain]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
