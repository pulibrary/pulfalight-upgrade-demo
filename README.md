# Pulfalight-Upgrade-Demo

Demo application for experiments with upgrading Pulfalight to ArcLight 1.x

### Updates from stock ArcLight
- PUL respositories configuration
- Pulfalight Solr schema
- Addition to the Solr schema for `isi` fields
- Pulfalight traject indexing configurations and supporting classes
- Addition of sort_isi, total_component_count_isi, online_item_count_isi,
online_item_count_isi, and component_level_isim fields to the ead indexer
- Pulfalight generated fixtures
- asdf configuration
- Lando configuration
- RSpec, rubocop, etc...

### Development

#### Setup
* Install Lando from https://github.com/lando/lando/releases (at least 3.0.0-rrc.2)

```sh
asdf install
bundle install
yarn install
yarn build:css
```

#### Starting / stopping services
We use lando to run services required for both test and development
environments.

Start and initialize solr and database services with `rake servers:start`

To stop solr and database services: `rake servers:stop` or `lando stop`

#### Start development server
- `rails s`
- Access Pulfalight at http://localhost:3000/
