# [hitboxtracker](https://github.com/rehlds/hitboxtracker) [![Percentage of issues still open](http://isitmaintained.com/badge/open/rehlds/hitboxtracker.svg)](http://isitmaintained.com/project/rehlds/hitboxtracker "Percentage of issues still open") [![GitHub license](https://img.shields.io/github/license/rehlds/hitboxtracker.svg?longCache=true&style=flat-square)](https://github.com/rehlds/hitboxtracker/blob/master/LICENSE) [![Deprecated](https://img.shields.io/badge/status-Deprecated-red.svg?style=flat-square)](https://github.com/rehlds/hitboxtracker/) [![GitHub issues](https://img.shields.io/github/issues/rehlds/hitboxtracker.svg?longCache=true&style=flat-square)](https://github.com/rehlds/hitboxtracker/issues) [![GitHub forks](https://img.shields.io/github/forks/rehlds/hitboxtracker.svg?longCache=true&style=flat-square)](https://github.com/rehlds/hitboxtracker/network) [![GitHub stars](https://img.shields.io/github/stars/rehlds/hitboxtracker.svg?longCache=true&style=flat-square)](https://github.com/rehlds/hitboxtracker/stargazers)

> [!WARNING]
> This project is now outdated and deprecated.

# Description
Dev-tool that demonstrates on client-side true position of the hitboxes calculated by server

# Installation
* Install `hitboxtracker_mm.dll` on your HLDS as metamod plugin
* Put `hitboxtracker.dll` and `cs.exe` to working directory of the game CS 1.6 client
* Run `cs.exe`

# Requirements
* For `Client`: build 4554 and later
* For `HLDS`: Metamod 1.20 and later

# Configuring
<table>
	<tbody>
		<tr>
			<th>r_drawentities</th>
			<th align="left">Description</th>
		</tr>
		<tr>
			<td>0</td>
			<td align="left">No entities</td>
		</tr>
		<tr>
			<td>1</td>
			<td align="left">Default and draws entities normally</td>
		</tr>
		<tr>
			<td>2</td>
			<td align="left">Entities draws as skeletons</td>
		</tr>
		<tr>
			<td>3</td>
			<td align="left">Entities draws hitboxes</td>
		</tr>
		<tr>
			<td>4</td>
			<td align="left">Entities draws with translucent hitboxes and the model beneath the hitboxes</td>
		</tr>
		<tr>
			<td>5</td>
			<td align="left">Individual box for player and weapon</td>
		</tr>
		<tr>
			<td>6 :heavy_plus_sign:</td>
			<td align="left">Same as 4 but draws true position of the hitboxes calculated by server</td>
		</tr>
		<tr>
			<td>7 :heavy_plus_sign:</td>
			<td align="left">Same as 6 but draws not translucent</td>
		</tr>
	</tbody>
</table>

# Preview
![r_drawentities-preview](https://user-images.githubusercontent.com/5860435/34494838-d659c868-f024-11e7-9582-bac8aa62e568.gif)
