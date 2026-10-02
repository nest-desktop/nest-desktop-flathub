# NEST Desktop Flatpak

NEST Desktop is build in Flatpak a utility in which users can run apps in isolation from the rest of the system.

## Flathub

Flathub is the central place for building and hosting Flatpak builds.

## Using the Flathub repository

To install applications that are hosted on Flathub, use the following:

```
flatpak remote-add flathub https://flathub.org/repo/flathub.flatpakrepo
flatpak install flathub <appId>
```

For more information and more applications see https://flathub.org

## Install NEST Desktop

To install NEST Desktop application from Flathub, use the following:

```
flatpak install --user flathub io.github.nest_desktop.nest-desktop
```

## Start NEST Desktop

Run it in the application desktop or start it in terminal:

```
flatpak run io.github.nest_desktop.nest-desktop
```
