# leda-radio

A small relay for voice: it carries spoken replies from a local Claude Code session to a phone.

Text-to-speech runs on the computer. Each reply is encrypted there and published to this repository. A web page (served by GitHub Pages) running on the phone fetches the file, decrypts it in the browser and plays it. The encryption key lives only on the user's own devices, never in this repository.

Status: experimental, work in progress. Proper documentation will follow.

Released under the Unlicense: use it as you like.
