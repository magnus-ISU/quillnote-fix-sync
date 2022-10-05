# Quillnote (with fixed syncing)

Quillnote is a beautiful application which had broken nextcloud syncing.

jsixface fixed this (a tiny change, it was mostly working just never tested much or something?), but the PR has been ignored for a while and the upstream repo hasn't been updated in a while.

I decided to compile the fixed version and, now that I've seen it works, upload it.

# Building

To build, I had to open in android studio. Trying to use gradle directly didn't seem to work.

# Don't be an idiot

I deleted quillnote to install the new version, and I didn't take a backup of all my notes. I lost most of them, all the changes I made since I had set up the nextcloud sync in the first place (if syncing worked in the first place, I would have lost nothing). Anyway, quillnote makes it easy to export a backup of all your notes, so learn from my stupidity and don't make the same mistake when installing this one.

# Quillnote

<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/1.png" width="256"/><img src="fastlane/metadata/android/en-US/images/phoneScreenshots/2.png" width="256"/><img src="fastlane/metadata/android/en-US/images/phoneScreenshots/4.png" width="256"/>


Take beautiful markdown notes whenever you feel inspired. Place them in notebooks and tag them accordingly. Stay organized by making task lists, set reminders and keep everything in one place by attaching related files.

Quillnote is fully free and open-source. It will never show you ads, ask you for unnecessary permissions or upload your notes anywhere without you knowing.

<a href="https://f-droid.org/packages/org.qosp.notes">
    <img src="https://fdroid.gitlab.io/artwork/badge/get-it-on.png"
    alt="Get it on F-Droid"
    height="80">
</a>
<a href='https://play.google.com/store/apps/details?id=org.qosp.notes'><img alt='Get it on Google Play' src='https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png' height="80"/></a>

## Features
With Quillnote, you can:

- Take notes with Markdown support
- Make task lists
- Pin your favorite notes to the top
- Hide notes you do not want others to see
- Set reminders for events you do not want to miss
- Add voice recordings and other file attachments
- Group related notes in notebooks
- Add tags to notes
- Archive notes you want out of your way
- Search through notes
- Sync with Nextcloud (experimental)
- Backup your notes to a zip file which you can restore at a later time
- Toggle between Light and Dark mode
- Choose between multiple color schemes

## License
```
Copyright (C) 2021 Michael Soultanidis

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.
```
