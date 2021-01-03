## Suricata & Snort Enrichment

### Requirements 
- [ ] Installation of pfELK
- [ ] Rename `45-cleanup.conf` => `95-cleanup.conf`
- [ ] Rename `50-outputs.conf` => `99-outputs.conf`
- [ ] Copy files located in the [conf.d](https://github.com/pfelk/pfelk/tree/master/experimental/conf.d) folder to `/etc/logstash/conf.d/`
- [ ] Copy files located in the [ruby]() folder to `/etc/logstash/conf.d/ruby/`
- [ ] Copy files located in the [databases]() folder to `/etc/logstash/conf.d/ruby/`
  - Be sure to unzip [ip_rep_basic.yml.zip](https://github.com/pfelk/pfelk/raw/master/experimental/databases/ip_rep_basic.yml.zip)
    - The file was too large to upload dirclty to GitHub

- [ ] Restart logstash 

### Way Forward
- [ ] Enrich Snort 
- [ ] Build out Suricata Dashboard *currenlty works with the built-in SEIM*
- [ ] Build out Snort Dashboard 