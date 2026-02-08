# Jackett Plugins for Unchained

Unchained search plugins for Jackett/Torznab. Requires a running Jackett server.

## Plugins

- **jackett** - Aggregate search across all configured Jackett indexers
- **knaben** - Knaben indexer
- **rutracker** - RuTracker indexer

## Setup

1. Download the `.unchained` plugin file you want
2. Open it in a text editor and replace the URL with your Jackett server details:
   `http://YOUR_SERVER:9117/api/v2.0/indexers/all/results/torznab/api?apikey=YOUR_API_KEY`
3. Open the edited file with Unchained to install it

Your phone must be able to reach your Jackett server on the network.
