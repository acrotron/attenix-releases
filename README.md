# Attenix Studio releases

Installers of **Attenix Studio**, the Windows application for building, checking and calculating environmental noise
studies of road traffic, railways and industry by the Dutch methods and CNOSSOS-EU, including the strategic noise maps
(geluidbelastingkaarten) of the Environmental Noise Directive. More at [attenix.eu](https://attenix.eu).

This repository holds only the installers and their release notes; it holds no source code.

## Download

Take the newest release under [Releases](https://github.com/acrotron/attenix-releases/releases/latest) and run
`attenix-studio-v<version>-setup.exe`. Each release lists the file's SHA-256 checksum.

- **Windows 10 or 11, 64-bit**, and for the map a graphics card with Vulkan.
- The setup installs Studio for all users of the computer, with the signed calculation modules and the command-line tool
  `attenix`. If .NET 10 or the Visual C++ runtime is missing, it names what is needed and fetches it from Microsoft.
- An earlier version is upgraded in place; your studies and settings are kept.
- The setup is not yet signed with a code-signing certificate, so Windows SmartScreen warns about an unknown publisher:
  choose **More info**, then **Run anyway**.

## Beta

Attenix is in beta: a lot can still change between releases, including functions, the interface, file formats and
results as the working-out of a method is adjusted. Studio has a trial period of 30 days that never blocks anything.
We'd like to hear what works, what doesn't and what is missing: [info@acrotron.com](mailto:info@acrotron.com?subject=Attenix%20feedback).

Attenix and Attenix Studio are made by [Acrotron](https://attenix.eu). Naming Dutch regulations or RIVM's reference
software implies no approval or certification by RIVM, IPLO or any other authority.
