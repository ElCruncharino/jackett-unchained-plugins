# Jackett Plugins for Unchained

Unchained search plugins for Jackett/Torznab. Requires a running Jackett server.

## Plugins

- **jackett** - Aggregate search across all configured Jackett indexers
- **knaben** - Knaben indexer
- **rutracker** - RuTracker indexer

## Setup

1. Add this repository in Unchained:
   `https://raw.githubusercontent.com/ElCruncharino/jackett-unchained-plugins/main/repository.json`
2. Install a plugin
3. Edit the plugin URL to point to your Jackett server:
   `http://YOUR_SERVER:9117/api/v2.0/indexers/all/results/torznab/api?apikey=YOUR_API_KEY`
