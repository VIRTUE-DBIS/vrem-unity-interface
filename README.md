# VREM Unity Interface

C# client generated with [OpenAPI](https://swagger.io/specification/) to provide access to
the [Virtual Exhibition Manager](https://github.com/VIRTUE-DBIS/virtual-exhibition-manager) server API
in [Unity](https://unity.com/).

## Setup

To include the latest version of this package in your Unity project, add the following line to your `manifest.json`
file:

```json
    "ch.unibas.dmi.dbis.vrem.client": "ssh://git@github.com/simonpeterhans/vrem-unity-interface.git#main",
```

Alternatively you can also use the Unity Package Manager and add the
URL `ssh://git@github.com/simonpeterhans/vrem-unity-interface.git#main`.

## Development

For development, clone this repository into the `Packages` directory of the Unity project.  
You may want to run `./gradlew clean deployAndTidy` to generate the binaries and (re)open the project in Unity in order
to generate the `.meta` files.
