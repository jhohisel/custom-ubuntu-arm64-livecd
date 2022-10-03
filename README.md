# Create a custom Ubuntu livecd for arm64

### WORK IN PROGRESS

Scripts to create a custom Ubuntu livecd iso image for use in testing experimental kernels with arm64 devices.

Before running this you need a compatible kernel and device tree.

### Example usage

```
./custom.sh /path/to/custom/linux-image.deb
```

or

```
./custom.sh /path/to/custom/linux-image.deb jammy
```

The custom.sh script will automatically create an arm64 livecd image for the release specified (or kinetic if not).
The output is at `~/kinetic-custom/ubuntu-kinetic-arm64-custom.iso` or the same location matching the specified release.
