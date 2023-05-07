# *EventSearch - React webapp*

By: **Shubham Jain**

EventSearch is an end-to-end web app for finding the next happening event. The app lets users search events, mark
favorites and view the relevant event/artist details in neat cards.

## <a href="https://shubham-jain-events-webapp.wl.r.appspot.com/search" target="_blank">Link to live web-app</a>

## Features

The following functionality is completed:

- [ ] React Router for single-page application (web-app never reloads the entire page)
- [ ] Config-driven UI -- only show fields that have data
- [ ] Redux is used for central data-store to avoid props-drilling
- [ ] Auto-detect location using ipInfo API
- [ ] Events table showing events in date/time sorted order
- [ ] Custom hook to fetch event details
- [ ] LocalStorage used to store favorite events
- [ ] Back button on Event Card that re-renders the table (not another API call)
- [ ] Spotify API used for getting music-related artist details
- [ ] Use of Context to identify current tab
- [ ] Modal to display map location	(GoogleMaps API)
- [ ] Custom Proxy Server for Backend using Node.js (hosted on GCP)

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<iframe width="560" height="315" src="https://www.youtube.com/embed/ns_cB8L1uT4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

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
