## Preamble
The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT" (and its shortened variant "SHAN'T"), "SHOULD", "SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in this document are to be interpreted as described in 
[RFC-2119](https://datatracker.ietf.org/doc/html/rfc2119).  
  
See also: [RFC-8174](https://datatracker.ietf.org/doc/html/rfc8174).
# API Notes
According to [Semantic Versioning v2.0.0](https://semver.org/), a product using Semantic Versioning MUST declare a public API. Since Bean Tycoon 2 uses Semantic Versioning v2.0.0 (like most other software on GitHub), we (thus I) feel obligated to
include a public API starting now. If you see any issues with this document, please let me know in the Issues tab. Thank you.  
## Dependencies
This game's source code comes in SB3 format. This is the file format used by [Scratch v3.0 projects](https://scratch.mit.edu). Despite that, the compatibility of this game with Scratch v3.0 is unclear. Here's why:  
- From v0.1.0-v0.3.0, the game should be fully compatible with Scratch v3.0 Online and Offline and any modifications for the 2.
- However, v0.3.1 introduces music. This bumps up the game size from 50.8KB to 90MB. Scratch v3.0 Online supports a max of 50MB per project. Thus, v0.3.1 and onwards are incompatible with Scratch v3.0 Online. You MUST either use the offline editor
or a variation of Scratch v3.0.
- v0.3.3 is the 1st version to use non-compatible Scratch extensions, making the game fully incompatible with all versions of Scratch to date. You SHOULD use [TurboWarp](https://turbowarp.org/) to play the game.
The game nowadays is built with TurboWarp in mind, an FOSS alternative to Scratch v3.0 with better speed and more customization.
### What does Bean Tycoon 2 use that Scratch doesn't support?
Well, as mentioned earlier, the game is too big for Scratch v3.0 Online, so the Offline version and TurboWarp deal with the large file size. v0.3.3 begins using TurboWarp's JSON extension and v0.3.10b1 begins using TurboWarp's Key Simulation
extension. You can try these out at [https://extensions.turbowarp.org/](https://extensions.turbowarp.org/).
