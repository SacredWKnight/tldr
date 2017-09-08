# streamlink

> Put video from various services into a video player of your choice.

- Quickly streamlink to your default player:

`streamlink {{link}}`

- Streamlink with the highest/lowest quality:

`streamlink {{link}} {{best/worst}}`

- Let the player control the transport of the stream:

`streamlink {{link}} --player-passthrough={{hls/http/trmp}}`

- Write stream data to FILENAME instead of playing it:

`streamlink {{link}} -o={{filename}}`
