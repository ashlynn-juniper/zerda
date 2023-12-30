# Zerda Engine

## Note from the developer, Ashlynn Juniper (December 30, 2023)

The Zerda Engine and Zerda Programming Language are labors of love made by a woman frustrated by over a decade of programming,
satisfied by no language which she's tried as of writing.
If you enjoy this engine or find it useful, please consider supporting my work!
I live almost entirely off of a bowl or two of rice and frozen vegetables each day because I can't afford anything else.
People are not meant to go hungry!! 🙁

Ways that you can contribute to my survival include:
* [Subscribe to a paid engine license such as Pro or Studio](https://patreon.com/ashejuniper)
* [Donate currency, or any gift cards that can be used to purchase food](https://patreon.com/ashejuniper)
* Join our community on Discord
* [Report bugs](https://github.com/toast-pigeon/zerda/issues)
* [Suggest new features](https://github.com/toast-pigeon/zerda/issues)

## Design Goals

Zerda is designed:

* To be portable, supporting all major desktop platforms, mobile devices, and consoles.
* To be beginner-friendly by providing an easy-to-learn, high-level syntax.
* To be veteran-friendly by providing hardware acceleration methods in the standard library (GPU, SIMD, threads, etc.).
* To be very error-resistant by enforcing certain rules at the syntactic level.
* To generate platform-optimized code in order to achieve blazingly-fast performance.
* To allow for both static and dynamic typing.
* To write dynamically-typed prototypes and then optimize by specifying the types of existing dynamic variables.
* To transpile to either C++, TypeScript, or JavaScript.
* To take advantage of any hardware present in order to maximize performance.

## Licenses

Edition | Cost (USD) | Splash screen | Commercial-use | Monthly consultation
--------|------------|---------------|----------------|---------------------
Community | Free | ✔ | ✔ | ❌
Pro | $10/month | ❌ | ✔ | ❌
Studio | $100/month | ❌ | ✔ | ✔

### Supported Platforms

Platform | Community | Pro | Studio | Full support
---------|-----------|-----|--------|-------------
Windows | ✔ | ✔ | ✔ | ❌
Linux | ✔ | ✔ | ✔ | ❌
Mac | ❌ | ✔ | ✔ | ❌
Android | ❌ | ✔ | ✔ | ❌
iOS | ❌ | ✔ | ✔ | ❌
Xbox One | ❌ | ❌ | ✔ | ❌
PS4 | ❌ | ❌ | ✔ | ❌
Switch | ❌ | ❌ | ✔ | ❌

### Supported Features

Feature | Community | Pro | Studio | Full support
--------|-----------|-----|--------|-------------
Cross-platform editor | ✔ | ✔ | ✔ | ❌
Building for other platforms | ✔ | ✔ | ✔ | ❌
2D and 3D rendering | ✔ | ✔ | ✔ | ❌
Multi-threading | ✔ | ✔ | ✔ | ❌
Vertex and fragment shaders | ❌ | ✔ | ✔ | ❌
Compute shaders | ❌ | ❌ | ✔ | ❌
Pre-trained AI models | ❌ | ✔ | ✔ | ❌
Runtime-trained AI models | ❌ | ❌ | ✔ | ❌

## Types of Releases

Release Type | Example Version | Stability | Latest Features | Description
-------------|-----------------|-----------|-----------------|------------
Stable | `v1.2.3` | ⭐⭐⭐⭐⭐ | ⭐ | Production-ready
Release Candidate | `v1.2.3-rc` | ⭐⭐⭐⭐ | ⭐⭐ | May contain a few minor bugs
Beta | `v1.2.3-beta` | ⭐⭐⭐ | ⭐⭐⭐ | May contain a few minor bugs and, occasionally, major bugs
Alpha | `v1.2.3-alpha` | ⭐⭐ | ⭐⭐⭐⭐ | May contain a few major bugs
Ace | `v1.2.3-ace` | ⭐ | ⭐⭐⭐⭐⭐ | Likely contains several major bugs
