# duckdb-snap
DuckDB CLI packaged for the Ubuntu Snap Store

## Installation

Currently this is not available on the snap store, so you will have to build it yourself.

Make sure the [snapcraft](https://snapcraft.io/snapcraft) snap is installed and working.

    sudo snap install snapcraft --classic

Clone this repo:

    git clone https://github.com/lab1702/duckdb-snap.git

Go to the snap subdirectory inside the repo:

    cd duckdb-snap/snap

Build snap:

    snapcraft

Install snap:

    sudo snap install ./duckdb_1.0.0-1_amd64.snap --dangerous

## Other Documentation

* DuckDB: [duckdb.org](https://duckdb.org)
* Snap store: [snapcraft.io](https://snapcraft.io)
