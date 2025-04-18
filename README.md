# vrh-deobfuscator
An automatic downloader and deobfuscator for VRoid Hub models.
For educational use only. I'll get really mad if you don't use it for educational reasons.

# Why are issues disabled?
This was mostly made for research purposes, I have no interest in actively enabling piracy (not that piracy is bad lol). If you would like to fix issues with the project, feel free to submit a pull request.

# Usage
Are you sure you should be using this?

# Usage, but like, actually
```bash
# Install dependencies
pnpm install
# Run with a URL for things you want to legally obtain
node src/index.js https://hub.vroid.com/en/characters/147647967680376151/models/259570871427745417
```

# Troubleshooting
gltf-transform does some things to every model that breaks them when used as a VRM, so the tool automatically patches each model up for usage as a VRM.

To resolve most issues, simply take the resulting VRM and throw it into Blender or Unity (w/ either version of the VRM extension) and re-export a new VRM from there. Try both versions of the Unity extension & Blender.


# Relevant blog post
[You can read more about this here, if you even care.](https://toon.link/blog/1740863435/borrowing-intellectual-property)
