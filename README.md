# RotMG Asset Ripper
Extracts assets from the game files, and tries to recompile the new sprite atlases into the old spritesheets.

## Usage

1. Download the latest version of https://github.com/AssetRipper/AssetRipper/releases
2. Update the `default_config.json` settings if not using command-line arguments
3. Install dependencies with "npm install".
4. Compile the program with "npm run build".
5. Run the program using `node out/index.ts`
   1. Optional runtime arguments:
      1. `--ar` - Path to AssetRipper executable
      2. `--resources` - Path to RotMG Data `resources.assets` file
      3. `--dest` - Output destination for generated content
      
### Basic Runtime Command Example

Assuming you have updated `default_config.json` then all you need to run is:

`node out/index.ts`

### Full Runtime Command Example

You can overwrite the values in `default_config.json` by specifying them at runtime:

`node out/index.ts --ar /path/to/AssetRipperExe --resources /path/to/rotmg-assets/data/resources.assets --dest /path/to/output`

## Support

Jakcodex operates its own Discord server at https://discord.gg/JFS5fqW.

Feel free to join and ask for help getting setup, hear about new updates, offer your suggestions and feedback, or just say hi. We love to hear from the community!

If you encounter a bug, have a feature request, or have any other feedback you can also check out the [issue tracker](https://github.com/jakcodex/muledump/issues) to see if it's already being discussed. If not then you can [submit a new issue](https://github.com/jakcodex/muledump/issues/new).

## Jakcodex License

Copyright 2023 [Jakcodex](https://github.com/jakcodex)

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

3. Neither the name of the copyright holder nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
