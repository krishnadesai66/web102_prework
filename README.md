# WEB102 Prework - *Sea Monster Crowdfunding*

Submitted by: **Krishna Desai**

*Sea Monster Crowdfunding** is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

Time spent: **5** hours spent in total

## Required Features

The following **required** functionality is completed:

* [X] The introduction section explains the background of the company and how many games remain unfunded.
* [X] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
* [X] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
* [X] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

The following **optional** features are implemented:

* [X] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

Here's a walkthrough of implemented features:


<a href = "https://imgur.com/a/izgRIY7">Video Walkthrough</a>
<!-- Replace this with whatever GIF tool you used! -->
GIF created with [ScreenToGif](https://www.screentogif.com/) for Windows
<!-- Recommended tools:
[Kap](https://getkap.co/) for macOS

[peek](https://github.com/phw/peek) for Linux. -->

## Notes

Describe any challenges encountered while building the app:
I did have one specific challenge with Challenge 4 where I was looping to find the sum of the backers but it was not appearing on the LiverServer. This was actually due to a careless error formed earlier in Challenge 3 where I was looping through every item in the data. Instead of looping for "i < games.length," I was looping "i <= games.length" which I saw was causing an error in the console log; I was using the console log to print log statements to find the error. games[i] would then be trying to access an undefined element when i would equal 12. As a result of this, I wasn't able to successfully move forward in challenge 4. Upon resolution, I was able to complete the challenge.

## License

    Copyright [2024] [Krishna Desai]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
