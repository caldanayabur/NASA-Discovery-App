# Web Development Project - *NASA Discovery App*

This web app: **A React web app that fetches random discoveries from NASA's Astronomy Picture of the Day (APOD) API and allows users to customize future discoveries using an interactive ban list.**

## Video Walkthrough

Here's a walkthrough:

https://github.com/user-attachments/assets/59b8996f-48fa-432b-943a-485b3ea27160

Video created with Microsoft Clipchamp.

## Notes

**Challenges encountered while building the app.**

Figuring out which attributes to display was challenging because the API returns an image, the media type, the date, the author (sometimes), the title, and the description. Some of these are not attributes a user can use to filter with. For example, the media type is always an image, and the description is always different. I decided to use the date and divide it so that the year and month are displayed separately as attributes. Although it was not always available, I also decided to use the author as an attribute to meet the requirement of having at least three attributes.

## License

    Copyright [2026] [Carolina Aldana]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
