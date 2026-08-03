<div align="center">

![Banner](https://capsule-render.vercel.app/api?type=waving&color=0:6C63FF,100:00C9A7&height=200&section=header&text=VPN%20Configs%20Mirror&fontSize=46&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Espejo%20automático%20de%20configuraciones%20VPN%20gratuitas&descAlignY=55&descSize=18)

[![Actualización Frecuente](https://github.com/bastidev-wav/vpn-mirror/actions/workflows/frequent_update.yml/badge.svg)](https://github.com/bastidev-wav/vpn-mirror/actions/workflows/frequent_update.yml)
![Último commit](https://img.shields.io/github/last-commit/bastidev-wav/vpn-mirror?color=6C63FF&label=última%20actualización&style=flat-square)
![Configuraciones activas](https://img.shields.io/badge/configuraciones-23-00C9A7?style=flat-square)
![Licencia](https://img.shields.io/github/license/bastidev-wav/vpn-mirror?color=6C63FF&style=flat-square)

</div>

## 📡 ¿Qué es esto?

Agregador automático que recolecta configuraciones VPN gratuitas desde múltiples repositorios de código abierto en GitHub y las centraliza en un único lugar, actualizado periódicamente.

## ⚙️ Cómo funciona

1. Un workflow de **GitHub Actions** se ejecuta **cada hora** según un cron.
2. El script lee la lista de fuentes desde [`urls.txt`](./urls.txt).
3. Cada fuente se descarga y se compara mediante hash **MD5** para detectar cambios; si cambió, se guarda en [`githubmirror/`](./githubmirror).
4. La tabla de abajo se regenera con la hora y fecha de Chile 🇨🇱 (`America/Santiago`).

## 📋 Configuraciones

|N°|                                                  Archivo                                                  |                    Fuente                    |Hora (CLT)|Fecha (CLT)|
|--|-----------------------------------------------------------------------------------------------------------|----------------------------------------------|----------|-----------|
| 1| [`1.txt`](https://raw.githubusercontent.com/bastidev-wav/vpn-mirror/refs/heads/master/githubmirror/1.txt) |               sakha1370/OpenRay              |   03:58  | 03.08.2026|
| 2|    [`2.txt`](https://raw.githubusercontent.com/pog7x/vpn-configs/refs/heads/master/githubmirror/2.txt)    |             sevcator/5ubscrpt10n             |   19:18  | 14.07.2026|
| 3|    [`3.txt`](https://raw.githubusercontent.com/pog7x/vpn-configs/refs/heads/master/githubmirror/3.txt)    |           yitong2333/proxy-minging           |   05:03  | 03.08.2026|
| 4|    [`4.txt`](https://raw.githubusercontent.com/pog7x/vpn-configs/refs/heads/master/githubmirror/4.txt)    |                 acymz/AutoVPN                |   05:03  | 03.08.2026|
| 5|    [`5.txt`](https://raw.githubusercontent.com/pog7x/vpn-configs/refs/heads/master/githubmirror/5.txt)    |         miladtahanian/V2RayCFGDumper         |   05:03  | 03.08.2026|
| 6|    [`6.txt`](https://raw.githubusercontent.com/pog7x/vpn-configs/refs/heads/master/githubmirror/6.txt)    |           roosterkid/openproxylist           |   05:03  | 03.08.2026|
| 7|    [`7.txt`](https://raw.githubusercontent.com/pog7x/vpn-configs/refs/heads/master/githubmirror/7.txt)    |            Epodonios/v2ray-configs           |   05:03  | 03.08.2026|
| 8| [`8.txt`](https://raw.githubusercontent.com/bastidev-wav/vpn-mirror/refs/heads/master/githubmirror/8.txt) |             CidVpn/cid-vpn-config            |   03:58  | 03.08.2026|
| 9|    [`9.txt`](https://raw.githubusercontent.com/pog7x/vpn-configs/refs/heads/master/githubmirror/9.txt)    |mohamadfg-dev/telegram-v2ray-configs-collector|   05:03  | 03.08.2026|
|10|   [`10.txt`](https://raw.githubusercontent.com/pog7x/vpn-configs/refs/heads/master/githubmirror/10.txt)   |               mheidari98/.proxy              |   05:03  | 03.08.2026|
|11|   [`11.txt`](https://raw.githubusercontent.com/pog7x/vpn-configs/refs/heads/master/githubmirror/11.txt)   |          youfoundamin/V2rayCollector         |   05:03  | 03.08.2026|
|12|[`12.txt`](https://raw.githubusercontent.com/bastidev-wav/vpn-mirror/refs/heads/master/githubmirror/12.txt)|              LalatinaHub/Mineral             |   03:58  | 03.08.2026|
|15|   [`15.txt`](https://raw.githubusercontent.com/pog7x/vpn-configs/refs/heads/master/githubmirror/15.txt)   |        miladtahanian/Config-Collector        |   05:03  | 03.08.2026|
|16|   [`16.txt`](https://raw.githubusercontent.com/pog7x/vpn-configs/refs/heads/master/githubmirror/16.txt)   |             Pawdroid/Free-servers            |   05:03  | 03.08.2026|
|16|[`16.txt`](https://raw.githubusercontent.com/bastidev-wav/vpn-mirror/refs/heads/master/githubmirror/16.txt)|                 free18/v2ray                 |   03:58  | 03.08.2026|
|17|   [`17.txt`](https://raw.githubusercontent.com/pog7x/vpn-configs/refs/heads/master/githubmirror/17.txt)   |         MhdiTaheri/V2rayCollector_Py         |   05:03  | 03.08.2026|
|19|   [`19.txt`](https://raw.githubusercontent.com/pog7x/vpn-configs/refs/heads/master/githubmirror/19.txt)   |           MhdiTaheri/V2rayCollector          |   05:03  | 03.08.2026|
|20|   [`20.txt`](https://raw.githubusercontent.com/pog7x/vpn-configs/refs/heads/master/githubmirror/20.txt)   |               Argh94/Proxy-List              |   05:03  | 03.08.2026|
|20|[`20.txt`](https://raw.githubusercontent.com/bastidev-wav/vpn-mirror/refs/heads/master/githubmirror/20.txt)|         wuqb2i4f/xray-config-toolkit         |   03:58  | 03.08.2026|
|21|   [`21.txt`](https://raw.githubusercontent.com/pog7x/vpn-configs/refs/heads/master/githubmirror/21.txt)   |                shabane/kamaji                |   11:09  | 02.08.2026|
|23|   [`23.txt`](https://raw.githubusercontent.com/pog7x/vpn-configs/refs/heads/master/githubmirror/23.txt)   |        igareck/vpn-configs-for-russia        |   05:03  | 03.08.2026|
|24|   [`24.txt`](https://raw.githubusercontent.com/pog7x/vpn-configs/refs/heads/master/githubmirror/24.txt)   |                Mr-Meshky/vify                |   05:03  | 03.08.2026|
|25|   [`25.txt`](https://raw.githubusercontent.com/pog7x/vpn-configs/refs/heads/master/githubmirror/25.txt)   |             V2RayRoot/V2RayConfig            |   10:28  | 05.07.2026|

## 🚀 Uso rápido

```bash
# Clonar el repositorio
git clone https://github.com/bastidev-wav/vpn-mirror.git
cd vpn-mirror

# Instalar dependencias
pip install -r requirements.txt

# Configurar variables de entorno
export GH_TOKEN="tu_token_de_github"
export REPO_NAME="usuario/repositorio"

# Ejecutar
python main.py
```

## 📦 Dependencias

| Paquete | Uso |
|---------|-----|
| [aiohttp](https://pypi.org/project/aiohttp/) | Peticiones HTTP asíncronas |
| [aiofiles](https://pypi.org/project/aiofiles/) | Lectura/escritura de archivos asíncrona |
| [PyGithub](https://pypi.org/project/PyGithub/) | Integración con la API de GitHub |
| [py-markdown-table](https://pypi.org/project/py-markdown-table/) | Generación de tablas en Markdown |
| [tzdata](https://pypi.org/project/tzdata/) | Base de datos de zonas horarias IANA para `zoneinfo` |

## ⚠️ Aviso

Este proyecto se ofrece únicamente con fines **educativos e informativos**. Quienes lo mantienen no alojan, crean ni respaldan ninguna configuración VPN — todos los archivos se espejan desde repositorios públicos de código abierto. Úsalo bajo tu propia responsabilidad y de acuerdo con las leyes de tu país.

<div align="center">

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:00C9A7,100:6C63FF&height=100&section=footer)

</div>
