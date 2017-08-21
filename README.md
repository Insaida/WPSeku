![python](https://img.shields.io/badge/python-2.7-brightgreen.svg) ![license](https://img.shields.io/badge/license-GPL-brightgreen.svg)
# WPSeku v0.2.1 - Wordpress Security Scanner 
WPSeku is a black box WordPress vulnerability scanner that can be used to scan remote WordPress installations and test for common security issues.

## Installation
```
# git clone https://github.com/m4ll0k/WPSeku.git
# cd WPSeku
# pip install -r requirements.txt
# python wpseku.py
```

![screen1](https://camo.githubusercontent.com/ae86d06707213143fb5b9ffafbf2b74a97c22308/687474703a2f2f692e696d6775722e636f6d2f6748526d73454d2e706e67)

## Usage
`python --target http://youtargethere.com`

![screen2](http://i.imgur.com/jSHWt0P.png)
![screen3](http://i.imgur.com/gGhmGdz.png)
![screen4](http://i.imgur.com/bBj8QdN.png)

## Examples
```
# wpseku.py --target http://localhost
# wpseku.py -t http://localhost/wp-admin/post.php -m GET -q "post=49&action=edit" [-x,-s,-l]
# wpseku.py --target http://localhost --brute --wordlist dict.txt
# wpseku.py --target http://localhost --brute --user test --wordlist dict.txt
```



## License
WPSeku is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation version 3 of the License. WPSeku is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details. You should have received a copy of the GNU General Public License along with WPSeku; if not, write to the Free Software Foundation, Inc., 51 Franklin St, Fifth Floor, Boston, MA  02110-1301  USA.

WPSeku uses WPScan Vulnerability Database API (https://wpvulndb.com/api).
