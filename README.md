# randomsong

`randomsong` is a Python tool designed to run from the command line. It will randomly choose a specified number of songs from a Spotify playlist.

## Usage

`python randomsong [path/to/json/export] [number_of_songs]`

`path_to_json_export` should point to a JSON export of a Spotify playlist. I obtained mine from [Skiley](https://skiley.net). On Skiley, select your playlist, scroll down to &ldquo;Export to File&rdquo;, then click &ldquo;JSON&rdquo; and &ldquo;Export to File&rdquo;.

`number_of_songs` is the number of songs you'd like `randomsong` to choose. This defaults to one.

Alternatively, you may change `json_path` in line 6 of the script to point to your JSON export. Then you can omit `path_to_json_export` when running `randomsong`.

## [Download randomsong](https://jmoll1125.github.io/randomsong/randomsong)