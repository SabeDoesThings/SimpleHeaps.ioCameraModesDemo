# Simple Heaps.io Camera Modes Demo
I haven’t seen any first person or third person like camera demos made in heaps so I decided to do it myself.

I used this [sample](https://github.com/nientedidecente/heaps-examples/tree/master/17_heaps_3d_scene) as a base. By Beeblerox.

Demo [video](https://www.youtube.com/watch?v=tkpNVz1c3Ck).

# Build
First make sure heaps is installed via `haxelib git heaps https://github.com/HeapsIO/heaps.git`, make sure you have [nightly](https://github.com/HaxeFoundation/hashlink/releases) version of hashlink is installed, and make sure you `hlsdl`, `hlopenal`, and `hldx` you NEED these for nightly version of hashlink like this.
  hlsdl:
    `haxelib git hlsdl https://github.com/HaxeFoundation/hashlink master libs/sdl`
  hlopenal:
    `haxelib git hlopenal https://github.com/HaxeFoundation/hashlink master libs/openal`
  hldx:
    `haxelib git hldx https://github.com/HaxeFoundation/hashlink master libs/directx`
You will also need differ and will need to install it like `haxelib install differ`.

Then just do `hl game.hl` and then your done :)
