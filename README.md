![legacynukkit](https://github.com/OksmaWarez/LegacyNukkit/blob/master/images/banner.png)

	This program is free software: you can redistribute it and/or modify
	it under the terms of the GNU Lesser General Public License as published by
	the Free Software Foundation, either version 3 of the License, or
	(at your option) any later version.

	This program is distributed in the hope that it will be useful,
	but WITHOUT ANY WARRANTY; without even the implied warranty of
	MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
	GNU Lesser General Public License for more details.

	You should have received a copy of the GNU Lesser General Public License
	along with this program.  If not, see <http://www.gnu.org/licenses/>.


__A Nuclear-Powered Server Software For Minecraft: Pocket Edition alpha__

-------------

Get LegacyNukkit
-------------
* __[Releases](https://github.com/OksmaWarez/LegacyNukkit/releases)__
* __[Actions](https://github.com/OksmaWarez/LegacyNukkit/actions)__ (**login required**)

Introduction
-------------
LegacyNukkit is an in-development fork of the last version of Nukkit to support Minecraft: Pocket Edition alpha 0.14.3, aiming to backport features and enchancements from later versions.

LegacyNukkit has a few advantages over PocketMine-MP for 0.14.3:
* Written in Java, Nukkit is faster, more stable and more portable. Run the server on anything that has a Java Runtime Environment!
* Having a similar structure with PocketMine-MP, because of this it's easy to contribute to LegacyNukkit's development. And it is also easy to rewrite legacy PocketMine-MP plugins into Nukkit plugins.
* Being in semi-active development, more and more features and enhancements are being backported from later versions.

This in no means is a complete product, and should not be used in a production environment. By using this you agree that you will take appropriate measures like taking backups and not cursing the developers every time you encounter a bug. This is Minecraft: Pocket Edition Alpha after all.

Build JAR file
-------------
- `git submodule update --init`
- `mvn clean package`

Running
-------------
Simply run `start.sh` or `start.cmd`. Or execute `java -jar Nukkit.jar`.

Plugin API
-------------
####**Example Plugin**
Example Plugin which shows the API of Nukkit.

* __[Example Plugin](http://github.com/Nukkit/ExamplePlugin)__

Discussion
-------------
Maybe sometime soon...?
