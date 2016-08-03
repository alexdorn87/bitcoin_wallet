alexcoin-js
=======


## License

Alexcoin-js is released under GNU General Public License, version 2 or later.

This program is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation; either version 2 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program; if not, write to the Free Software Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA 02110-1301, USA.

## Configuration

Input config information to provisioning/hive-js.config

COOKIE_SALT={{ COOKIE_SALT }}

DB_HOST={{ DB_HOST }}

DB_PASSWORD={{ DB_PASSWORD }}

DB_PORT={{ DB_PORT }}

DB_USER={{ DB_USER }}

NODE_ENV={{ NODE_ENV }}

PROXY_URL={{ PROXY_URL }}

## Start Proxy

cd {{ app_dir }}

export `cat {{ base_dir }}/{{ app_name }}.config`

forever start -c "npm start" ./
