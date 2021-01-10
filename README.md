# PolyOrigin

![Singularity Build](https://github.com/powerPlant/polyorigin-srf/workflows/Singularity%20Build/badge.svg)

Singularity recipe files for [PolyOrigin](https://github.com/chaozhi/PolyOrigin.jl) - A package for haplotype reconstruction in connected polyploid F1 populations

## Usage

### Downloading / Installing

Obtain the latest asset from the action page, `unzip` and `tar -zxf` the files to preferred location.

### Running

    singularity exec polyorigin-x.x.x.sif julia

Where `x.x.x` translates to the version. Alternatively, use the `julia` symlink if you installed using the notes above.

### Building

    make
    make install

* For users without root `make BUILD_OPTIONS=--fakeroot;`.
* To install to a different location pass `PREFIX=...`, i.e. `make install PREFIX=~/singularity-images`
