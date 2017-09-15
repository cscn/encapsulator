# Encapsulator

[![DOI](https://zenodo.org/badge/94570522.svg)](https://zenodo.org/badge/latestdoi/94570522)

## Installation

```
gem install encapsulator
```

## Building from source

### Fedora 25

```
sudo dnf install ruby
gem install json rgl rake bundler
git clone https://github.com/tfjmp/encapsulator.git
cd encapsulator
rake install
encapsulator --install fedora
encapsulator -h
```

### Ubuntu

```
sudo apt install ruby
gem install json rgl rake bundler
git clone https://github.com/tfjmp/encapsulator.git
cd encapsulator
rake install
encapsulator --install ubuntu
encapsulator -h
```

### MacOS

```
brew install ruby
gem install json rgl rake bundler
git clone https://github.com/tfjmp/encapsulator.git
cd encapsulator
rake install
encapsulator --install mac
encapsulator -h
```

## USAGE

```
# extract info from ddg.json
encapsulator --info <your_RDT_prov.json>
# select an output node to generate the code to be generate
encapsulator --code <your_RDT_prov.json> <output_node_name> <new R script>
```
