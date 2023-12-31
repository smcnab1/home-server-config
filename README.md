<!-- TOP ROW OF BADGES -->

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![Kofi][kofi-badge]][kofi-url]
<a name="readme-top"></a>

<!-- PROJECT HEADING -->

# Home Server Config

This is my **first** time creating or using a Home Server. I began with a Raspberry Pi 4B and a **very** old HDD, playing with <a href="https://www.openmediavault.org/">Open Media Vault</a> but got bitten by the NAS bug and have created a full home server/lab for the house.

<!-- CONTENTS -->

<div align="center">
<a href="#hardware">Hardware</a>
|
<a href="#container">Containers & Machines</a>
|
<a href="#contributing">Contributing</a>
|
<a href="#license">License</a>
|
<a href="#contact">Contact</a>
</div>
&nbsp;

<!-- HARDWARE -->

<a name="hardware"></a>

## Hardware _(as at Mar 23)_

This is a list of the hardware I **currently** use as part of my Home NAS setup. Any suggestions drop them as a <a href="https://github.com/smcnab1/home-server-config/issues/new?assignees=smcnab1&labels=Priority%3A+Low%2C+Type%3A+Feature&template=feature_request.md&title=%5BFR%5D">feature request.</a>
<br />

<!-- start-table -->
<details><summary><b>View all Hardware</i></b></summary>
<table>
    <thead>
        <tr>
            <th>Servers & Dekstops 🖥</th>
            <th>Qty (#)</th>
            <th>Price per unit (£)</th>
            <th>Price (£)</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><a href="https://amzn.to/3YYFtyw">Lenovo M73 Tiny ThinkCentre (1TB SSD, 16GB RAM, i7)</a></td>
            <td>2</td>
            <td>199.99</td>
            <td>388.98</td>
        </tr>
        <tr>
            <td><a href="https://amzn.to/3Xc0xQD">Apple Mac Mini 2020 (M1, 250GB)</a></td>
            <td>1</td>
            <td>699.99</td>
            <td>699.99</td>
        </tr>
        <tr>
            <td><a href="https://amzn.to/3TYq6DL">ODROID N2+ (4GB RAM)</a></td>
            <td>1</td>
            <td>83.00</td>
            <td>83.00</td>
        </tr>
        <tr>
            <td><a href="https://thepihut.com/collections/raspberry-pi-boards/products/raspberry-pi-4-model-b?variant=31994565689406">Raspberry Pi 4 Model B, 8GB RAM</a></td>
            <td>1</td>
            <td>75.50</td>
            <td>75.50</td>
        </tr>
        <tr>
            <td><a href="https://thepihut.com/collections/raspberry-pi-boards/products/raspberry-pi-4-model-b?variant=31994565689406">Raspberry Pi 4 Model B, 4GB RAM</a></td>
            <td>1</td>
            <td>75.50</td>
            <td>75.50</td>
        </tr>
        <tr>
            <td><a href="https://thepihut.com/collections/raspberry-pi-boards/products/raspberry-pi-4-model-b?variant=31994565689406">Raspberry Pi 4 Model B, 2GB RAM</a></td>
            <td>1</td>
            <td>75.50</td>
            <td>75.50</td>
        </tr>
        <tr>
            <td><i><b>Total</b></i></td>
            <td>&nbsp;</td>
            <td>&nbsp;</td>
            <td><b>1398.47</b></td>
        </tr>
        <tr>
            <td>&nbsp;</td>
            <td>&nbsp;</td>
            <td>&nbsp;</td>
            <td>&nbsp;</td>
        </tr>
    </tbody>
    <thead>
        <tr>
            <th>Storage 💾</th>
            <th>Units (#)</th>
            <th>Price per unit (£)</th>
            <th>Price (£)</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><a href="https://www.ebay.co.uk/itm/404066298784">Synology DS218+ 2 Bay Desktop NAS</a></td>
            <td>1</td>
            <td>293.47</td>
            <td>293.47</td>
        </tr>
        <tr>
            <td><a href="https://amzn.to/3CcXrDB">Seagate IronWolf 8TB Hard Drive</a></td>
            <td>2</td>
            <td>159.00</td>
            <td>318.00</td>
        </tr>
        <tr>
            <td><a href="https://amzn.to/3WWevWo">Crucial BX500 1TB SSD</a></td>
            <td>5</td>
            <td>56.11</td>
            <td>280.55</td>
        </tr>
        <tr>
            <td><a href="https://amzn.to/3i8FfUR">Fanxiang S101 512GB SSD</a></td>
            <td>2</td>
            <td>49.32</td>
            <td>98.64</td>
        </tr>
        <tr>
            <td><a href="https://amzn.to/3CeY3J8">SanDisk 128GB USB Flash Drive</a></td>
            <td>4</td>
            <td>14.95</td>
            <td>59.80</td>
        </tr>
        <tr>
            <td><i><b>Total</b></i></td>
            <td>&nbsp;</td>
            <td>&nbsp;</td>
            <td><b>1050.46</b></td>
        </tr>
        <tr>
            <td>&nbsp;</td>
            <td>&nbsp;</td>
            <td>&nbsp;</td>
            <td>&nbsp;</td>
        </tr>
    </tbody>
    <thead>
        <tr>
            <th>Networking 👨‍💻</th>
            <th>Units (#)</th>
            <th>Price per unit (£)</th>
            <th>Price (£)</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><a href="https://amzn.to/3YYYPDL">TP-Link JetStream 16-Port Switch</a></td>
            <td>1</td>
            <td>105.55</td>
            <td>105.55</td>
        </tr>
        <tr>
            <td><a href="https://amzn.to/3Id8bWl">TP-Link TL-SG1005D 5-Port Switch</a></td>
            <td>1</td>
            <td>12.99</td>
            <td>12.99</td>
        </tr>
        <tr>
            <td><a href="https://amzn.to/3voJRcG">TP-Link TL-SG108S 8-Port Switch</a></td>
            <td>1</td>
            <td>17.49</td>
            <td>17.49</td>
        </tr>
        <tr>
            <td><a href="https://amzn.to/3VAtq7B">TP-Link TL-ER605 Router</a></td>
            <td>1</td>
            <td>47.69</td>
            <td>47.69</td>
        </tr>
        <tr>
            <td><a href="https://amzn.to/3Z2Ajl2">TP-Link TL-WA1201 Access Point </a></td>
            <td>1</td>
            <td>39.02</td>
            <td>39.02</td>
        </tr>
        <tr>
            <td><a href="https://amzn.to/3WTgpXP">TP-Link TL-UE306 USB 3.0 to Ethernet Adapter</a></td>
            <td>2</td>
            <td>11.99</td>
            <td>23.98</td>
        </tr>
        <tr>
            <td><i><b>Total</b></i></td>
            <td>&nbsp;</td>
            <td>&nbsp;</td>
            <td><b>246.72</b></td>
        </tr>
        <tr>
            <td>&nbsp;</td>
            <td>&nbsp;</td>
            <td>&nbsp;</td>
            <td>&nbsp;</td>
        </tr>
    </tbody>
    <thead>
        <tr>
            <th>Total of All Devices<br /> [as at Dec 22 (UK)]</th>
            <th></th>
            <th></th>
            <th><b>😳£2,695.65😳</b></th>
        </tr>
    </thead>
</table>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

</details>
&nbsp;
<!-- CONTAINERS & MACHINES -->

<a name="container"></a>

## Containers & Machines _(as at Mar 23)_

This is a list of all of my containers & machines within my setup. These also include the <a href="https://www.docker.com/">Docker</a> Containers I currently use.

<!-- pve-01-services -->
<details><summary><b>PVE-01 [Lenovo M73 Tiny, 16GB RAM, 1TB SSD, i7] <i>(as at Mar 23)</i></b></summary>

<table>
<thead>
<tr>
<th colspan="2">&nbsp;<strong>PVE-LXC-100</strong>&nbsp;- 1 CPU | 2.5GB RAM | 1GB SWAP</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: center; vertical-align: middle;" colspan="2"><em>&nbsp;&nbsp;Ubuntu 20.04 | Docker 20.10</em></td>
</tr>
<tr>
<td><strong>OpenProject</strong></td>
<td><em>OS Application</em></td>
</tr>
<tr>
<td><strong>Portainer Agent</strong></td>
<td><em>Docker Container</em></td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th colspan="2">&nbsp;<strong>PVE-LXC-101</strong>&nbsp;- 1 CPU | 6GB RAM | 1GB SWAP</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: center; vertical-align: middle;" colspan="2"><em>&nbsp;&nbsp;Ubuntu 20.04</em></td>
</tr>
<tr>
<td><strong>Grafana</strong></td>
<td><em>Docker Container</em></td>
</tr>
<tr>
<td><strong>UptimeKuma</strong></td>
<td><em>Docker Container</em></td>
</tr>
<tr>
<td><strong>Loki</strong></td>
<td><em>OS Application</em></td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th colspan="2">&nbsp;<strong>PVE-LXC-102</strong>&nbsp;- 2 CPU | 3GB RAM | 1GB SWAP</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: center; vertical-align: middle;" colspan="2"><em>&nbsp;&nbsp;Ubuntu 20.04 | Docker 20.10</em></td>
</tr>
<tr>
<td><strong>OpenVPN</strong></td>
<td><em>OS Application</em></td>
</tr>
<tr>
<td><strong>Portainer Agent</strong></td>
<td><em>Docker Container</em></td>
</tr>
<tr>
<td><strong>Jellyseerr</strong></td>
<td><em>Docker Container</em></td>
</tr>
<tr>
<td><strong>Sonarr</strong></td>
<td><em>Docker Container</em></td>
</tr>
<tr>
<td><strong>Radarr</strong></td>
<td><em>Docker Container</em></td>
</tr>
<tr>
<td><strong>Prowlarr</strong></td>
<td><em>Docker Container</em></td>
</tr>
<tr>
<td><strong>Transmission</strong></td>
<td><em>Docker Container</em></td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th colspan="2">&nbsp;<strong>PVE-LXC-103</strong>&nbsp;- 1 CPU | 2.5GB RAM | 1GB SWAP</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: center; vertical-align: middle;" colspan="2"><em>&nbsp;&nbsp;Ubuntu 20.04 | Docker 20.10</em></td>
</tr>
<tr>
<td><strong>Portainer Agent</strong></td>
<td><em>Docker Container</em></td>
</tr>
<tr>
<td><strong>BitWarden</strong></td>
<td><em>Docker Container</em></td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th colspan="2">&nbsp;<strong>PVE-LXC-105</strong>&nbsp;- 1 CPU | 3GB RAM | 1GB SWAP</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: center; vertical-align: middle;" colspan="2"><em>&nbsp;&nbsp;Ubuntu 20.04 | Docker 20.10</em></td>
</tr>
<tr>
<td><strong>Portainer Agent</strong></td>
<td><em>Docker Container</em></td>
</tr>
<tr>
<td><strong>NextCloud</strong></td>
<td><em>Docker Container</em></td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th colspan="2">&nbsp;<strong>PVE-VM-104</strong>&nbsp;- 2 CPU | 6GB RAM</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: center; vertical-align: middle;" colspan="2"><em>&nbsp;&nbsp;Debian 11 | Proxmox Backup Server 2.3-1</em></td>
</tr>
<tr>
<td><strong>Proxmox Backup Server</strong></td>
<td><em>OS Application</em></td>
</tr>
</tbody>
</table>

<p align="right">(<a href="#readme-top">back to top</a>)</p>
</details>

<!-- pve-02-services -->
<details><summary><b>PVE-02 [Lenovo M73 Tiny, 16GB RAM, 1TB SSD, i7] <i>(as at Dec 22)</i></b></summary>
This section is currently a work in progress
<p align="right">(<a href="#readme-top">back to top</a>)</p>
</details>

<!-- raspi-1-services -->
<details><summary><b>RASPI-1 [Raspberry Pi 4B, 8GB RAM, 1TB SSD] <i>(as at Dec 22)</i></b></summary>
<table>
<thead>
<tr>
<th colspan="2">&nbsp;<strong>RASPI-1</strong>&nbsp;- 8GB RAM</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: center; vertical-align: middle;" colspan="2"><em>&nbsp;&nbsp;Raspbian Lite 64Bit OS | Docker 20.10</em></td>
</tr>
<tr>
<td><strong>NetData</strong></td>
<td><em>OS Application</em></td>
</tr>
<tr>
<td><strong>Portainer Agent</strong></td>
<td><em>Docker Container</em></td>
</tr>
</tbody>
</table>

<p align="right">(<a href="#readme-top">back to top</a>)</p>
</details>

<!-- raspi-2-services -->
<details><summary><b>RASPI-2 [Raspberry Pi 4B, 4GB RAM, 1TB SSD] <i>(as at Dec 22)</i></b></summary>
<table>
<thead>
<tr>
<th colspan="2">&nbsp;<strong>RASPI-2</strong>&nbsp;- 4GB RAM</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: center; vertical-align: middle;" colspan="2"><em>&nbsp;&nbsp;Raspbian Lite 64Bit OS | Docker 20.10</em></td>
</tr>
<tr>
<td><strong>NetData</strong></td>
<td><em>OS Application</em></td>
</tr>
<tr>
<td><strong>PiHole (Slave)</strong></td>
<td><em>OS Application</em></td>
</tr>
<tr>
<td><strong>Gravity-Sync</strong></td>
<td><em>OS Application</em></td>
</tr>
<tr>
<td><strong>Portainer-CE</strong></td>
<td><em>Docker Container</em></td>
</tr>
<tr>
<td><strong>MariaDB</strong></td>
<td><em>Docker Container</em></td>
</tr>
<tr>
<td><strong>NetBox</strong></td>
<td><em>Docker Container</em></td>
</tr>
<tr>
<td><strong>Node-RED</strong></td>
<td><em>Docker Container</em></td>
</tr>
<tr>
<td><strong>NGINX Proxy Manager</strong></td>
<td><em>Docker Container</em></td>
</tr>
<tr>
<td><strong>phpMyAdmin</strong></td>
<td><em>Docker Container</em></td>
</tr>
</tbody>
</table>
<p align="right">(<a href="#readme-top">back to top</a>)</p>
</details>

<!-- raspi-3-services -->
<details><summary><b>RASPI-3 [Raspberry Pi 4B, 2GB RAM, 1TB SSD] <i>(as at Dec 22)</i></b></summary>
<table>
<thead>
<tr>
<th colspan="2">&nbsp;<strong>RASPI-2</strong>&nbsp;- 4GB RAM</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: center; vertical-align: middle;" colspan="2"><em>&nbsp;&nbsp;Raspbian Lite 64Bit OS | Docker 20.10</em></td>
</tr>
<tr>
<td><strong>NetData</strong></td>
<td><em>OS Application</em></td>
</tr>
<tr>
<td><strong>Gravity-Sync</strong></td>
<td><em>OS Application</em></td>
</tr>
<tr>
<td><strong>Portainer Agent</strong></td>
<td><em>Docker Container</em></td>
</tr>
<tr>
<td><strong>Omada Controller</strong></td>
<td><em>Docker Container</em></td>
</tr>
<tr>
<td><strong>PiHole (Master)</strong></td>
<td><em>Docker Container</em></td>
</tr>
<tr>
</tbody>
</table>
<p align="right">(<a href="#readme-top">back to top</a>)</p>
</details>

<!-- synology-services -->
<details><summary><b>SYN-NAS-01 [Synology DS218+ NAS Enclosure, 10GB RAM, 16TB Storage] <i>(as at Dec 22)</i></b></summary>
<table>
<thead>
<tr>
<th colspan="2">&nbsp;<strong>SYN-NAS-01</strong>&nbsp;- 10GB RAM</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: center; vertical-align: middle;" colspan="2"><em>&nbsp;&nbsp;Synology DMS | Docker 20.10</em></td>
</tr>
<tr>
<td><strong>NetData</strong></td>
<td><em>OS Application</em></td>
</tr>
<tr>
<td><strong>Docker</strong></td>
<td><em>OS Application</em></td>
</tr>
<tr>
<td><strong>Jellyfin</strong></td>
<td><em>Docker Container</em></td>
</tr>
<tr>
<td><strong>PhotoPrism</strong></td>
<td><em>Docker Container</em></td>
</tr>
<tr>
</tbody>
</table>
<p align="right">(<a href="#readme-top">back to top</a>)</p>
</details>

<!-- homeassistant-services -->
<details><summary><b>ODR-HA-01 [ODROID N2+, 4GB RAM, 250GB Storage] <i>(as at Dec 22)</i> Full Details on <a href="https://github.com/smcnab1/home-server-config">Home-Server-Config Git</a></i></b></summary>
<table>
<thead>
<tr>
<th colspan="2">&nbsp;<strong>ODR-HA-01</strong>&nbsp;- 4GB RAM</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: center; vertical-align: middle;" colspan="2"><em>&nbsp;&nbsp;Home Assistant OS</em></td>
</tr>
<tr>
<td><strong>NetData</strong></td>
<td><em>Add-On</em></td>
</tr>
<tr>
<td><strong>ESPHome</strong></td>
<td><em>Add-On</em></td>
</tr>
<tr>
<td><strong>Frigate NVR</strong></td>
<td><em>Add-On</em></td>
</tr>
<tr>
<td><strong>Google Drive Backup</strong></td>
<td><em>Add-On</em></td>
</tr>
<tr>
<td><strong>Logspout</strong></td>
<td><em>Add-On</em></td>
</tr>
<tr>
<td><strong>Mosquitto Broker</strong></td>
<td><em>Add-On</em></td>
</tr>
<tr>
<td><strong>Studio Code Server</strong></td>
<td><em>Add-On</em></td>
</tr>
<tr>
<td><strong>Terminal & SSH</strong></td>
<td><em>Add-On</em></td>
</tr>
<tr>
<td><strong>Zigbee2MQTT</strong></td>
<td><em>Add-On</em></td>
</tr>
<tr>
</tbody>
</table>
<p align="right">(<a href="#readme-top">back to top</a>)</p>
</details>
&nbsp;

## Back Matter

<!-- CONTRIBUTING -->

<a name="contributing"></a>

### Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement" or "feature-request".
Don't forget to give the project a star! Thanks again!

1. Fork the Project.
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### License

This project is licensed under the [MIT License](LICENSE.md).

<!-- CONTACT -->

<a name="contact"></a>

### Contact

[![Email][email-badge]][email-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
[![GitHub][git-badge]][git-url]
[![Kofi][kofi-badge]][kofi-url]
<br />

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->

[contributors-shield]: https://img.shields.io/github/contributors/smcnab1/home-server-config.svg?style=for-the-badge
[contributors-url]: https://github.com/smcnab1/home-server-config/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/smcnab1/home-server-config.svg?style=for-the-badge
[forks-url]: https://github.com/smcnab1/home-server-config/network/members
[stars-shield]: https://img.shields.io/github/stars/smcnab1/home-server-config.svg?style=for-the-badge
[stars-url]: https://github.com/smcnab1/home-server-config/stargazers
[issues-shield]: https://img.shields.io/github/issues/smcnab1/home-server-config.svg?style=for-the-badge
[issues-url]: https://github.com/smcnab1/home-server-config/issues
[license-shield]: https://img.shields.io/github/license/smcnab1/home-server-config.svg?style=for-the-badge
[license-url]: https://github.com/smcnab1/home-server-config/blob/master/LICENSE.md
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/sammcnab/
[email-badge]: https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white
[email-url]: mailto:shacodinggit@gmail.com
[git-badge]: https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white
[git-url]: https://github.com/smcnab1
[kofi-badge]: https://ko-fi.com/img/githubbutton_sm.svg
[kofi-url]: https://ko-fi.com/sammcnab1
