# Besta RTOS SDK extension

This SDK extension simplifies Besta RTOS applet development through Flatpak IDEs.

## Build

Simply run

```sh
flatpak-builder --repo=repo builddir org.freedesktop.Sdk.Extension.muteki.yaml
```

## Usage

Add `FLATPAK_ENABLE_SDK_EXT=muteki` to a Flatpak IDE's environment variable, either using command-line or Flatseal.
