### Notice:

**You can use this visual builder to create templates and submit PRs to this repo if they work: [Shipwright](https://shipwright.yacht.sh) it's currently pretty early in development but should be able to take portainer templates (that don't have type 2 or 3 templates) and import them for editing.**

This Template is made for [Yacht](https://github.com/SelfhostedPro/Yacht/tree/vue) create an issue if you would like something added.

# Yacht Templates for Selfhosted Projects/Homelabs

This is a template focused on helping people spin up selfhosted services using Yacht.
## Versions

The following table shows the corresponding url to use for the application you're using.

| Application  | URL |
| ------------- | ------------- |
| Yacht | https://raw.githubusercontent.com/Hakker/selfhosted_templates/master/Template/yacht.json |
The others aren't maintained


### Prerequisites

1. A server/NAS with docker installed
2. A Yacht setup.

*Want something we don't have? Make an issue and we'll work on adding it*

### Installing

1. Login to the Web-UI for the corresponding project.
2. Navigate to the area where you add a template (in portainer you'll need to enable external templates)
3. Add the template URL corresponding to the application you're using in the table above.

### Information
All templates are already configured to bind mount to various places on your drive. This branch works without the need for OMV. The following folders are all created in /portainer/

* **Files** - General file storage.
  * **AppData** - Subfolder where application data (unrelated to served data) is stored.
    * **Config** - Subfolder where configuration files for every container are stored.
    * **Data** - Subfolder where dat for most containers are stored.
* **Downloads** - Where bittorrent and usenet downloaders download files to.
* **TV** - Where tv shows are stored/moved to after downloaded.
* **Movies** - Where movies are stored/moved to after downloaded.
* **Music** - Where music is stored/moved to after downloaded.
* **Books** - Where books are stored/moved to after downloaded.
* **Comics** - Where comics are stored/moved to after downloaded.
* **Podcasts** - Where podcasts are stored/moved to after downloaded.

- example on Ubuntu it's /yacht/AppData/Config/[container] and /yacht/AppData/Data/[container]
## App List

- Airsonic
- Authelia
- Bazarr
- Beets
- Bitwarden RS
- Booksonic
- Calibre Web
- Cardigann
- Chevereto
- Chowdown
- Code Server
- Codiad
- COPS
- CouchPotato
- Daapd
- DashMachine
- Dashy
- Davos
- DeeMix
- Deluge
- Domoticz
- Duck DNS
- Duplicati
- Emby
- EmbyStat
- FileBrowser
- Flame
- FreshRSS
- Gazee
- GOPHISH
- Grafana
- Grocy
- Guacamole
- Headphones
- Heimdall
- Home Assistant
- Homer
- HTPC Manager
- Huginn
- InfluxDB
- Jackett
- Jellyfin
- Kodi Headless
- Lanraragi
- LazyLibrarian
- Let's Encrypt
- LibreSpeed
- lidarr
- Lychee
- MariaDB
- McMyAdmin 2
- Medusa
- MineOS
- Minetest
- Minisatip
- Mstream
- Murmur
- MusicBrainz
- Muximux
- Mylar
- Navidrome
- Nginx
- Nginx Proxy Manager
- NZBGet
- Ombi
- OpenVPN Access Server
- Organizr v2
- OScam
- Papermerge
- PhotoShow
- Pi-Hole
- Piwigo
- Plex
- Plex Requests
- ProjectSend
- Prometheus
- ProtonMail Bridge
- Pydio
- qBittorrent
- Quassel IRC
- Radarr
- Reactive-Resume
- Resilio Sync
- ruTorrent
- SABnzbd
- Shiori
- SickChill
- SickGear
- SmokePing
- Snibox
- Sonarr
- SWAG
- SyncThing
- Tautulli
- Teamspeak
- TheLounge
- TiddlyWiki
- Tiny Tiny RSS
- Transmission
- Transmission-OpenVPN
- Tvheadend
- Ubooquity
- Unifi Controller
- Watchtower
- WebGrab+Plus
- Whoogle
- Wikijs
- YouTubeDL-Material
- ZNC

## Contributing

If you wish to contribute make a pull request, create an issue, or email me.

## Authors
* **Hakker** - *Current Fork*
* **NASHosted** - *Initial Work*
* **SelfhostedPro** - *Initial Work*
* **Jos Visser** - *Initial work* - [Qballjos](https://github.com/Qballjos)

## Acknowledgments

* LinuxServer.io for the old Template
* Inspiration being too lazy to create each container template manualy
