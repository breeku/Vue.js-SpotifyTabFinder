# Vue.js-PlaylistTabFinder

## [Link](https://playlisttabfinder.now.sh/)

Search for tabs from your Spotify playlists. Currently scrapes tabs from songsterr and inserts them to database.

### Goals:
#### Both:
- [ ] Search for tabs from Ultimate Guitar too
#### Frontend:
- [ ] Should probably imply somewhere that the site is meant for guitar tabs :cat:
- [ ] Filters (tuning, sort).
#### Backend:
- [ ] Prevent spam requesting/ check that theres no pending request with same body
- [ ] Make getpTracks run in parallel, would improve performance massively, and is necessary to scale.
- [ ] Fix track artist check (currently gets artist wrong if theres more than one).

> Created with Created with Vue.js, Node.js, Express and MongoDB
