<a name="readme-top"></a>

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
-->

[![Contributors][contributors-shield]][contributors-url]
[![Donate][donate-shield]][donate-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![Apache License 2.0][license-shield]][license-url]
[![Downloads][downloads-shield]][downloads-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/ZeroxyDev/montally">
    <img src="https://i.ibb.co/hF33Hzs/Square310x310-Logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">MonTally | Advanced Pokémon encounter counter with shiny odds.</h3>

  <p align="center">
    PokéMMO & Pokémon Revolution Online Encounter Counter: Simplifying your Pokémon counting experience across both platforms.
    <br />
    <a href="https://montally.app/">Website</a>
    ·
    <a href="https://github.com/ZeroxyDev/montally/issues">Report Bug</a>
    ·
    <a href="https://github.com/ZeroxyDev/montally/issues">Request Feature</a>
    ·
    <a href="https://discord.gg/ByuAz2uBG8">Discord</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#customization">Customization</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

MonTally allows you to keep track of your Pokémon encounters and provides an estimate of shiny odds. Whether you're playing PokéMMO or Pokémon Revolution Online, MonTally simplifies the counting experience.

MonTally now supports **Windows**, **Linux**, and **macOS**, and also includes native **PokeMMO integration** with profiles and real-time sync options.

Feel free to contribute to the project with suggestions, or ideas!

Preview of `MonTally`:

<span><img src="https://i.ibb.co/Qcz3NVX/1.png" alt="Logo" height="200"></span>
<span><img src="https://i.ibb.co/VLLLBkv/4.png" alt="Logo" height="200"></span>
<span><img src="https://i.ibb.co/1G5bhwb/2.png" alt="Logo" height="200"></span>
<span><img src="https://i.ibb.co/GPC7Nsr/3.png" alt="Logo" height="200"></span>
<span><img src="https://i.ibb.co/56VPxYK/5.png" alt="Logo" height="200"></span>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->

## Getting Started

### Prerequisites

- Windows 10 or later.
- Linux distributions capable of running AppImage files.
- macOS compatible with the current MonTally build.
- Java 21 JDK or newer is recommended if you want to use MonTally's native PokeMMO integration.
  - Official Oracle JDK 21 download: https://www.oracle.com/java/technologies/downloads/#java21

### Installation

#### Windows

1. Download MonTally from [here](https://github.com/ZeroxyDev/montally/releases).
2. Navigate to the settings and configure MonTally according to your preferences.
3. Open your PokéMMO or Pokémon Revolution Online game.
4. Ensure that you are using Windows 10 or a later version.

When running the installer of MonTally application, you may encounter a message indicating that the **application is not signed**. This is a common occurrence for unsigned software. Follow these steps to proceed securely:

1. Upon seeing the "application not signed" message, click on "More Info."
2. Look for the option that allows you to continue or run the application despite the lack of a digital signature.
3. Click on "Run Anyway" to initiate the application safely.

This message is a standard security caution, and by following these steps, you can confidently launch the MonTally application.

<span><img src="https://i.ibb.co/7KR1hSg/wdf1.png" alt="Logo" height="300"></span>
<span><img src="https://i.ibb.co/4PtBMWp/wdf2.png" alt="Logo" height="300"></span>

#### 🐧 Linux

1. Download the `mon-tally_x.x.x_amd64.AppImage` file from [here][downloads-url] (where x.x.x represents the latest available version).
2. Make the AppImage executable using one of these methods:
   - From the terminal:
     ```bash
     chmod +x mon-tally_x.x.x_amd64.AppImage
     ```
   - Or using the file manager:
     - Right-click the file
     - Select Properties
     - Go to the Permissions tab
     - Enable "Allow executing file as a program"

3. Run MonTally by:
   - Double-clicking the AppImage file in your file manager
   - Or from the terminal:
     ```bash
     ./mon-tally_x.x.x_amd64.AppImage
     ```

4. Navigate to the settings and configure MonTally according to your preferences.
5. Open your PokéMMO or Pokémon Revolution Online game.

#### 🍎 macOS

1. Download the macOS `.dmg` build from [here][downloads-url].
2. Open the downloaded `.dmg` file.
3. Drag `MonTally.app` into your `Applications` folder.
4. Try opening the app normally, or use right-click → `Open` if macOS blocks it.
5. If macOS still says the app is damaged, open Terminal and run:

   ```bash
   xattr -dr com.apple.quarantine /Applications/MonTally.app
   ```

6. Open `MonTally.app` again from `Applications`.

> Note: current macOS builds may trigger Gatekeeper warnings because they are not notarized yet.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->

## Usage

MonTally is designed to be flexible and user-friendly. Here's a simple guide on how to use it:

1. Launch the MonTally application.

2. Access the settings to customize Pokémon detection:
   - **Automatic Mode:** MonTally will effortlessly detect and log all encountered Pokémon automatically.
   - **Manual Mode:** Users can select specific Pokémon to track, providing more control over the counting process.

3. Go to **Settings** and select **"Select Capture Area"**. Position the capture area so it encloses the region where Pokémon names appear during battles. Be sure to include enough space to account for horde battles, where multiple Pokémon names might appear on the screen.

![capturesettings](https://github.com/user-attachments/assets/6e92993e-bfeb-47e8-b46a-c998ee074cf7)

4. Ensure that the game is running, and there are no obstructions blocking Pokémon names.

5. For the best experience in games like PokeMMO, consider the following recommendation:
   - In the game settings, go to **Interface settings**.
   - Enable **"Always Show Battle HUD"** to ensure accurate Pokémon detection and logging during battles.
   - In the game settings, go to **Video settings**.
   - Disable **"Show Battle Background"** to avoid distractions that could interfere with Pokémon detection and logging.

6. Begin seamlessly counting and tracking your Pokémon encounters!

### PokeMMO Native Integration

MonTally also supports a native PokeMMO integration flow:

> IMPORTANT: If MonTally cannot use PokeMMO's bundled runtime on your system, install **Java 21 SDK or newer** first. Older Java versions such as Java 8 are not compatible with this workflow.
>
> Official download: https://www.oracle.com/java/technologies/downloads/#java21

1. Open **Settings** and switch to the **PokeMMO** profile.
2. Click **Connect PokeMMO** to launch or reconnect the game through MonTally.
3. Enter the game and load your character.
4. Use **Sync with PokeMMO** if you want to import your current tracker data into the active profile.
5. Optionally enable **Match PokeMMO in real time** if you want MonTally to fully mirror PokeMMO tracker data.

This workflow is recommended when you want stricter real-time sync and profile-based separation for PokeMMO hunts.


<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Known Bugs

Despite its robust functionality, MonTally may encounter certain issues. Here is a list of known bugs and possible solutions:

1. **Issue:** Detection becomes incorrect after moving the game to another monitor.

   - **Solution:** Re-open **Select Capture Area** and save the area again after moving the game window. MonTally supports multiple monitors, but the capture area must match the monitor where the game is currently running.

2. **Issue:** Incorrect Pokémon Count
   - **Description:** The MonTally application occasionally exhibits inaccurate counts, especially during initial usage. The counts may either be higher or lower than the actual number of Pokémon encountered.
   - **Solution:** Actively use the application; as more encounters are recorded, the counting accuracy tends to improve.

3. **Issue:** Unintended Pokémon Detection in Inventory.

   - **Description:** MonTally is erroneously detecting Pokémon when browsing Pokémon in the backpack or other locations.
   - **Solution:** Temporarily disable the counter in the settings during these specific moments. Alternatively, consider not placing Pokémon in the upper half of the screen.
   
4. **Issue:** "Always on Top" mode not working in borderless windowed mode (e.g., in PokeMMO).  
   - **Description:** When running games in borderless windowed mode, such as PokeMMO, MonTally's *Always on Top* functionality may not behave as expected and can fail to stay above the game window.  
   - **Solution:** Change the game's graphics API to a more compatible one, such as *ANGLE* or *DirectX*. This can usually be adjusted in the advanced graphics settings of the game.


Please note that we are continuously working to improve the application and address these issues. If you come across any additional bugs, feel free to report them so that we can continue enhancing the MonTally experience.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CUSTOMIZATION -->

## Customization

MonTally allows you to fully customize the look of your tracker with custom images. Follow this guide to design your own unique visuals using the provided resources.

## 🖼️ Image Specifications

To ensure proper integration in MonTally, custom assets must match the following dimensions:

- **Border Image**: `350x109 px`
- **Main Image**: `500x500 px`

These sizes are required to maintain alignment and avoid layout issues.

## 🧩 Customization Template

Use the following resources to create your custom visuals:

- [customization.psd](https://github.com/ZeroxyDev/MonTally/blob/main/assets/images/customization/customization.psd) — Photoshop file with guides and layers for precise editing.  
- [frame-border.png](https://github.com/ZeroxyDev/MonTally/blob/main/assets/images/customization/frame-border.png) — Default border example.  
- [frame-image.png](https://github.com/ZeroxyDev/MonTally/blob/main/assets/images/customization/frame-image.png) — Default main image example.

Open the PSD in Photoshop (or a compatible editor), customize the content, and export your assets in `.png` format with the exact sizes mentioned above.

## 🧪 Visual Guide

<span><img src="https://github.com/ZeroxyDev/MonTally/blob/main/assets/images/tutorials/custom-c-customize.png" width="30%" /></span>
<span><img src="https://github.com/ZeroxyDev/MonTally/blob/main/assets/images/tutorials/custom-c-settings.png" width="30%" /></span>
<span><img src="https://github.com/ZeroxyDev/MonTally/blob/main/assets/images/tutorials/custom-c.png" width="30%" /></span>

These visuals demonstrate both the creation process and the in-app appearance.

## ✅ Tips for Best Results

- Keep your designs clean and visually balanced.
- PNG format is recommended for transparency and quality.
- Always match the exact dimensions to avoid UI misalignment.
- Test your design within MonTally to ensure correct placement.

---

With these tools and guidelines, you can easily bring your own visual style to MonTally. Happy customizing!



<!-- ROADMAP -->

## Roadmap

Key Features:

- [x] Pokémon encounter tracking.
- [x] Shiny odds estimation.
- [x] Versatile Scenario Detection.
  - [x] Individual encounters.
  - [x] Double encounters.
  - [x] Hordes encounters.
- [x] Compatibility with both PokéMMO and Pokémon Revolution Online.
- [x] User-selectable Detection Modes:
  - [x] Automatic Mode: MonTally detects and logs encountered Pokémon automatically.
  - [x] Manual Mode: Users can choose specific Pokémon to track, providing more control.
- [ ] Multi-language Support.
  - [ ] Spanish.
- [x] Detailed Pokémon Information:
  - [x] Users can view comprehensive information about Pokémon by clicking on their names or images.
  - [x] Information includes shiny ratio, types, locations, statistics, capture rate in wild encounters, and more.
- [x] Extreme Detection Mode:
  - [x] Experience heightened sensitivity for Pokémon detection with the Extreme Detection Mode, ensuring accuracy in various gameplay scenarios.
- [x] Auto-updates: Stay current with the latest features and improvements effortlessly.
- [x] Turbo Mode:
  - [x] Turbo mode added for enhanced performance.
- [x] Debug Mode:
  - [x] Debug mode added for easier issue identification.
- [x] ON/OFF Mode:
  - [x] ON/OFF mode introduced for customizable functionality.
- [x] Edit enounters
- [x] Reset Counters:
  - [x] Reset counters for each Pokémon upon opening.
  - [x] Persistent Shiny ratio in each Pokémon (unless the general counter is reset).
- [x] General Counter Reset:
  - [x] General counter reset option, resetting all statistics.
- [x] Pokémon Image Options:
  - [x] Added the option to use Pokémon images locally or from the API.
- [x] Customizable.
  - [x] Custom colors
  - [x] Custom sprites
  - [x] Custom images in total encounters
- [x] Data Reset Option.

See the [open issues](https://github.com/ZeroxyDev/montally/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the development community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please open an issue with the tag "enhancement".

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- DONATE -->

## Support MonTally Development

MonTally is fueled by the passion of supporters like you. Your donations go a long way in fueling ongoing improvements and innovations.

If you've found value in MonTally or appreciate the time and effort invested, I invite you to consider making a donation. Every contribution, big or small, helps me enhance and refine MonTally for a better experience.

Don't forget to show some love by starring this project! Your support is highly appreciated and motivates me to keep pushing MonTally to new heights.

[Support MonTally development here](https://ko-fi.com/zeroxydev)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- LICENSE -->

## License

Distributed under the Apache License 2.0 License. See `LICENSE.md` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->

## Contact

ZeroxyDev - [@ZeroxyDev](https://twitter.com/ZeroxyDev)

Project Link: [https://github.com/ZeroxyDev/montally](https://github.com/ZeroxyDev/montally)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->

## Acknowledgments

- [Img Shields](https://shields.io)
- [PokeAPI](https://github.com/PokeAPI/pokeapi)
- [Bulbagarden](https://archives.bulbagarden.net/wiki/Category:Shuffle_icons)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/ZeroxyDev/montally.svg?style=for-the-badge
[contributors-url]: https://github.com/ZeroxyDev/montally/graphs/contributors
[downloads-shield]: https://img.shields.io/github/downloads/zeroxydev/montally/total?color=%2331c754&label=Downloads&logoColor=%23ffffff&style=for-the-badge
[downloads-url]: https://github.com/ZeroxyDev/MonTally/releases/latest
[forks-shield]: https://img.shields.io/github/forks/ZeroxyDev/montally.svg?style=for-the-badge
[forks-url]: https://github.com/ZeroxyDev/montally/network/members
[stars-shield]: https://img.shields.io/github/stars/ZeroxyDev/montally.svg?style=for-the-badge
[stars-url]: https://github.com/ZeroxyDev/montally/stargazers
[issues-shield]: https://img.shields.io/github/issues/ZeroxyDev/montally.svg?style=for-the-badge
[issues-url]: https://github.com/ZeroxyDev/montally/issues
[license-shield]: https://img.shields.io/github/license/ZeroxyDev/montally.svg?style=for-the-badge
[license-url]: https://github.com/ZeroxyDev/montally/blob/main/LICENSE.md
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/zeroxydev
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[Tailwind.com]: https://img.shields.io/badge/Tailwind-ffffff?style=for-the-badge&logo=tailwindcss&logoColor=38bdf8
[Tailwind-url]: https://tailwindcss.com/
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com
[donate-shield]: https://img.shields.io/badge/$-donate-ff69b4.svg?style=for-the-badge
[donate-url]: https://ko-fi.com/zeroxydev
