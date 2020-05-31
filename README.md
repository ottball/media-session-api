# Media Session API

This repository contains code samples demonstrating how to implement the [Media Session API](https://w3c.github.io/mediasession). This repository is linked to an article on [how to use the Media Session API](https://ottball.com/media-session-api/) as published on ottball.com.

## sample-1.html

This sample uses THEOplayer to playback an audio asset with ID3 tags. Depending on the ID3 tags, the Media Session's metadata will be updated.

Known issues:
* It uses the duration info extracted from the ID3 tags to determine where the `nexttrack` is. However, this duration doesn't match the duration of the song in the configured audio stream.
* Switching to previous track through the platform UI doesn't work.

## License
[MIT](https://choosealicense.com/licenses/mit/)
