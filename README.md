UnBiHealth Control Panel
=============

This is a java application to manage [unbihealth](https://github.com/lhsantos/unbihealth-core/) environments.
It detects compatible games and input devices in the smart space and allows health professionals to create
user profiles, specifying input parameters, and associate them to games.


Structure
=============

The Control Panel is developed using the [uOS middleware](https://github.com/UnBiquitous/uos_core/) as well as the
[unbihealth framework](https://github.com/lhsantos/unbihealth-core/) for health focused ubigame development.

The whole project is available in the `src` folder.


Building
=============

For building this project you'll need to use [Maven](http://maven.apache.org/).

Since UnBiHealth Control Panel is still in development we rely on current unstable versions of the following libraries:

- [uOS-Core 3.2.0](https://github.com/UnBiquitous/uos_core/)
- [uOS-Socket-Plugin 3.2.0](https://github.com/UnBiquitous/uos_socket_plugin)
- [unbihealth 1.0](https://github.com/lhsantos/unbihealth-core/)

It's advised to download the respective code from these libs in order to build the project.
