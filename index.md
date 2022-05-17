<div id="top"></div>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="images/logo.png" alt="Logo" width="150" height="150">
  </a>

  <h3 align="center">iHybrid za QGIS</h3>

  <p align="center">
    navodila za pomoč uporabnikom pri namestitvi
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template"><strong>Več o iHybridu »</strong></a>
    <br />
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template">iObcina</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">iKomunala</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">iSlovenija</a>
  </p>
</div>















<!-- TABLE OF CONTENTS -->
<details>
  <summary>Kazalo</summary>
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
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>




<!-- ABOUT THE PROJECT -->
## Nekaj o projektu

V  paleto prostorskih rešitev dodajamo vmesnik **iHybrid - QGIS**, ki podatke spletnega portala iObcina.si / iKomunala.si prenese v okolje QGIS. Razviti vmesnik se dopolnjuje s prostorskimi orodji programa in uporabniku omogoča dostop do svežih in urejenih podatkov, ki lahko služijo kot odlična podlaga pri delu. Vmesnik med drugim omogoča:
- Pregled vektorskih in rastrskih podatkov, 
- prenos in urejanje vektorski podatkov v lokalno okolje za trenutno ali celotno območje občine,
- poizvedovanje po posameznih identitetah in še mnogo več ...



## Kako začeti

V nadaljevanju je opisan postopek kako namestiti vmesnik. Ker je vmesnik trenutno še v razvoju, se lahko navodila za namestitev še nekoliko spremenijo.

### Zahteve
Vmesnik trenutno deluje le znotraj operacijskega sistema Windows 7 (in več). Za uporabo vmesnika iHybird je potrebno namestiti osnovni program  **QGIS v 3.10** ali več. Namestitev je lahko tako samostjona, kot tudi preko OSGeo4W installerja. Če QGIS-a še nimate, ga lahko namestite preko [QGIS](https://qgis.org/en/site/forusers/download.html) povezave. 



### Kako namestiti

1) Prenesemo .zip datoteko vmesnika, ki jo dobimo na povezavi **tukaj**. Datkteko poljubno shranimo lokalno na računalnik in pustimo v formatu .zip . 
2) Odpremo program QGIS. V orodni vrstici (Menu toolbar) poiščemo zavihek **Plugins** in odpremo orodje Manage and Install Plugins. 
3) Odpre se orodje, kjer v zavihku na levi izberemo **Install from ZIP**
4) S klikom na (...) poiščemo datoteko pot do datoteke .zip, ki smo jo predhodno shranili in nato izbiro potrdimo s gumbom Install Plugin.

**Edit:** Po koraku 4) se lahko pojavi pogovorno okno Securty warning, ki sprašuje ali smo prepričani, da želimo namestiti vmesnik neznanega avtorja. Potrdimo izbiro in zaključimo namestitev. (do tega pride, saj vmesnik ni javno obljavnjen v repozitorju QGIS)


<!-- USAGE EXAMPLES -->
## Uporaba

V orodni vrstici zgoraj se je ustvarila bližnjica do programa iHybrid. Ob kliku nanjo se na desni strani odpre vtičnik v katerega se je potrebno prijaviti.
- Izbrati je  potrebno portal in občino znotraj katere bomo delali
- Vnesti je potrebno uporabniško ime in geslo, ki sta enaka kot na spletnih portalih iObčina.si / iKomunala.si

**Edit:** Za vsako občino se je potrebno imeti svoj račun. Če še nistre registrirani, prosim izberite občino in se registrirajte [tukaj](https://www.iobcina.si/selectiobcina/) in nato nadaljujte v programu QGIS.


## Licenca
Na voljo je 10 dnevna brezplačna licenca. Če želite podaljšati licenco, nas prosim kontaktirajte preko kontaktneca centra... Tukaj nadaljuj...


<!-- ROADMAP -->
## Roadmap

- [x] Add Changelog
- [x] Add back to top links
- [ ] Add Additional Templates w/ Examples
- [ ] Add "components" document to easily copy & paste sections of the readme
- [ ] Multi-language Support
    - [ ] Chinese
    - [ ] Spanish

See the [open issues](https://github.com/othneildrew/Best-README-Template/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Your Name - [@your_twitter](https://twitter.com/your_username) - email@example.com

Project Link: [https://github.com/your_username/repo_name](https://github.com/your_username/repo_name)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Malven's Flexbox Cheatsheet](https://flexbox.malven.co/)
* [Malven's Grid Cheatsheet](https://grid.malven.co/)
* [Img Shields](https://shields.io)
* [GitHub Pages](https://pages.github.com)
* [Font Awesome](https://fontawesome.com)
* [React Icons](https://react-icons.github.io/react-icons/search)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
