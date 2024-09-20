# Instagram follower collector

This script was created to streamline the process of collecting follower data from competitor pages on Instagram, along with other information that can be used by a marketing department conducting benchmark studies.

## Quick statement

I initially tried several methods, including using Selenium with both Chrome and Mozilla web services but the browsers were blocking my access, detecting the automation attempts. 
So I had to resort to another method that involves authentication (login) *directly on Instagram*.

The thing is: I use *two-factor authentication* to log into my account, and the main idea of this script is to complete the task without any human intervention. 
To deal with this, I had to start a session on Instagram from my terminal.

Do the same as follows:

```bash
instaloader --login username
```

The terminal will ask you for the password and then your 2FA code. 
No worries. This will only be required once, even if you close the terminal and come back later. 

## Technologies

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white) ![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?style=for-the-badge&logo=Instagram&logoColor=white)

## Features

Collects Instagram follower count, following count, post count, bio, and bio link for competitor pages.
Stores the collected data in both CSV and JSON formats.

## Final considerations

I hope this script saves you some time during your ETL routine.
If you're interested, I also have scripts to collect followers and posts from LinkedIn pages. Check out my repositories to learn more.

## Collaboration

If you have any ideas for improving the code or adding functions to it, I would love to hear from you. 
Contact me via email (franciellekfq@gmail.com).
