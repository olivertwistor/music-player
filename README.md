# Music Player
This is a music player that allows the user to create rule based playlists. It's also a podcast aggregator.

I think that the closed-source software [iTunes][1] is a very good music player and an even better podcast aggregator. Then why create another music player and podcast aggregator, especially when there already exists perfectly good open-source alternatives?

One reason is that I haven't found any music player that allows for rule based playlists besides iTunes. Furthermore, iTunes store its rule based playlists within the music library file itself instead of outside of it. By doing that, structure and data isn't decoupled at all, something that is highly problematic if one decides to move to another computer with a different music library. One can't just export the rules (structure) without the music (data).

Another reason is that while iTunes works well with a relatively small number of podcast subscriptions, it quickly becomes a huge memory hog when the number of podcast subscriptions increases. The same is true for the music library. When it becomes "too large", iTunes has a tendency to crash and corrupt the music library in the process. Because structure and data isn't decoupled, all playlists are lost as well. I am acutely aware of this, because I tend to subscribe to huge numbers of podcasts as well as having my whole CD collection imported to iTunes, resulting in many crashes and loss of data.

This app's focus is decoupling of structure and data as well as facilitating the interchangability of various components, for example playlists, music library and podcast subscriptions.

## Table of contents
* [Who is this for?](#who-is-this-for)
* [Prerequisites](#prerequisites)
* [Installation instructions](#installation-instructions)
* [Usage](#usage)
* [Licensing](#licensing)
* [How to contribute](#how-to-contribute)
* [Versioning](#versioning)

## Who is this for?
If you're like me, you'll likely have a big music library as well as many podcast subscriptions. This application would probably suit you if you don't need all the bells and whistles you would get from iTunes and other applications like that, making for a leaner experience. 

## Prerequisites
To run this application, you will need:

* [Java 1.7 or newer][2]

## Installation instructions
More info is coming once the first release is out.

## Usage
More info is coming once the first release is out.

## Licenses
This app is licensed under a GNU General Public License. You find the full license terms in the file [LICENSE][3].

### Libraries
* [JAudiotagger][4], [JLayer][5] and [MP3SPI][6] are all licensed under the GNU Lesser General Public License. You find the full license terms in the files [LICENSE-JAudiotagger][7], [LICENSE-JLayer][8] and [LICENSE-MP3SPI][9].
* [Tritonus][10] is licensed under the GNU General Public License. You find the full license terms in the file [LICENSE-Tritonus][11].

## How to contribute
Thank you for wanting to contribute to this project. Open source is all about community. Go and read the document [CONTRIBUTING.md][12] for more information on with what you can contribute and how to go about it.

## Versioning
This project uses [Semantic Versioning 2.0.0][13] for version numbering. To see what's changed between versions, please read [CHANGELOG.md][14]. That file also has links to the download section of each release.

[1]: https://www.apple.com/itunes/download/
[2]: https://java.com/download/
[3]: LICENSE
[4]: http://www.jthink.net/jaudiotagger/
[5]: http://www.javazoom.net/javalayer/javalayer.html
[6]: http://www.javazoom.net/mp3spi/mp3spi.html
[7]: LICENSE-JAudioTagger
[8]: LICENSE-JLayer
[9]: LICENSE-MP3SPI
[10]: http://www.tritonus.org/
[11]: LICENSE-Tritonus
[12]: CONTRIBUTING.md
[13]: http://semver.org/
[14]: CHANGELOG.md
