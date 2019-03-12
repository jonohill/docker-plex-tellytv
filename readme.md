# plex-tellytv

The [official Plex image](https://hub.docker.com/r/plexinc/pms-docker), plus [tellytv](https://github.com/tellytv/telly) and FFmpeg.
tellytv makes it easy to use IPTV with Plex DVR.

The `dev` version of tellytv is what's included since the repo advises this is the best option for "most users".

## Usage

Follow the official [Plex image instructions](https://hub.docker.com/r/plexinc/pms-docker). Everything works the same.

For tellytv, follow [their instructions](https://github.com/tellytv/telly/tree/dev) to get your config file prepared, then save it to your Plex configuration directory (the directory you mounted to `/config`) as `telly.config.toml`.
