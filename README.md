# Build

To build and install Zatikon based on this repository, run the following in the project's directory:

```sh
flatpak-builder --user --install --force-clean build-dir com.chroniclogic.Zatikon.yml
```

# Validations

To check the validity of the project's metadata, run:

```sh
flatpak run org.freedesktop.appstream.cli validate com.chroniclogic.Zatikon.metainfo.xml

desktop-file-validate com.chroniclogic.Zatikon.desktop
```

# Flathub build status

On update, you can check the status of the package at https://buildbot.flathub.org/#/
