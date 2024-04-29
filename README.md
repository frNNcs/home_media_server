# Home Media Server
My home media server setup is designed for seamless entertainment. Powered by Plex, it brings together the best of TorrentDay, Sonarr, Radarr, and Overseerr to create a smooth viewing experience.

Using TorrentDay as my primary source, I've leveraged Sonarr and Radarr to automate media management and discovery. With these tools in sync, I can effortlessly stream content from my digital library.

But that's not all - with Overseerr on board, my family can request their favorite series and movies, which are then seamlessly added to our collection using Radarr and Sonarr. To tie it all together, Jackett helps me adapt tznab requests for TorrentDay, ensuring a streamlined media management experience.

## Workflow Diagram

![image](https://github.com/frNNcs/home_media_server/assets/34633159/dee60c62-bb05-467f-aeef-3cbd81afd4eb)

### Services Overview

* [Plex](https://github.com/plexinc/pms-docker)
* [Sonarr](https://github.com/Sonarr/Sonarr)
* [Radarr](https://github.com/Radarr/Radarr)
* [Overseerr](https://github.com/sct/overseerr)
* [Jackett](https://github.com/Jackett/Jackett)
* [Transmission](https://github.com/transmission/transmission)

## Getting Started

1. Obtain your Plex token by visiting [https://plex.tv/claim](https://plex.tv/claim) and add it to the `docker-compose.yml` file.
2. Run the command: `docker compose up -d`
3. Configure services as desired (e.g., Sonarr, Radarr, Overseerr).

## Tips

You can view all services through the [Dashy](https://github.com/Lissy93/dashy) dashboard on [localhost:4000](http://localhost:4000)


Feel free to modify this example to fit your project's unique needs!
