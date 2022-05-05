# rust-game
PoC Rust game using Bevy engine based on mwbryants repo [monster-fighter](https://github.com/mwbryant/monster-fighter).


## Requirements
* Rust Stable 1.24.3+
* Bevy 0.7.0+

Bevy requires some setup on Linux, instructions can be found [here](https://github.com/bevyengine/bevy/blob/main/docs/linux_dependencies.md).

## Ubuntu 20.04

```bash
sudo apt-get install g++ pkg-config libx11-dev libasound2-dev libudev-dev
```

if using Wayland, you will also need to install

```bash
sudo apt-get install libwayland-dev libxkbcommon-dev
```

Depending on your graphics card, you may have to install one of the following:
`vulkan-radeon`, `vulkan-intel`, or `mesa-vulkan-drivers`

Compiling with clang is also possible - replace the `g++` package with `clang`.


### Usage
Run game
```
cargo run
```  

### Tests
Run unit tests
```
cargo test
```

## Authors
* Viktor From [viktorfrom](https://github.com/viktorfrom)

## License
Licensed under the MIT license and in accordance to the repo this project is based on. See [LICENSE](LICENSE) for details.