# bwtcjs
This is bwtc algorithm  extracted from  [compressjs](https://github.com/cscott/compressjs). Some obviously unneded parts of code was removed. Also MAGIC word was removed, so stream now starts from data size.

I did this specially for using bwtc compressor in browser, so main file of this repo is `bwtc.min.js`. This file was created with [UglifyJS 2](https://github.com/mishoo/UglifyJS2) by executing this command: `uglifyjs --compress --mangle -o bwtc.min.js -- bwtc.js`
For some if more compression used in UglifyJS (or if Closure Compiler used in ADVANCED mode) resulting file is not working. Sorry, i was not able to fix that, so minification is not at maximum level.

From node.js `bwtc.js` can be required and also used. Also this file is not minified.

Originally [compressjs](https://github.com/cscott/compressjs) was released under GPLv2 livense. So this code, i think, is also GPLv2.

## License (GPLv2)

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 2 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see http://www.gnu.org/licenses/.
