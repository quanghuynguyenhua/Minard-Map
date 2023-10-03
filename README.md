<a name="readme-top"></a>

<!-- PROJECT IMAGE -->
<br />
<div align="center">
  
  <h3 align="center">Minard Map</h3>
  <h3 align="center"><a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&width=435&lines=Minard+Map" alt="Typing SVG" /></a>
  <a href="https://github.com/quanghuynguyenhua/Minard-Map/edit/main/README.md">
    <img src="viz1asset/minardMap.png" alt="Logo" width="900" height="500">
  </a></h3>

  

  <p align="center">
    Redesign a notable Minard's Russian campaign map using contemporary interactive methods
    <br />
    <a href="https://github.com/quanghuynguyenhua/Minard-Map"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://www.arcgis.com/apps/CEWebViewer/viewer.html?3dWebScene=2b48caaabd0e44028724c5f109f3de97&fbclid=IwAR3ErA8p4iaar5dxYrx3VzXw_EV70W_ju3A6IzpUhhCDnP5XECZqUCJ6Y0I">View Reference of 3D plot</a>
    ·
    <a href="https://github.com/quanghuynguyenhua/Minard-Map/issues">Report Bug</a>
    ·
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
        <li><a href="#references">References</a></li>
        <li><a href="#facts">Amazing Facts</a></li>
      </ul>
    </li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

In the annals of cartographic history, few maps have achieved the level of acclaim and significance as Charles Joseph Minard's masterpiece— the "Napoleon Map." Crafted in 1869, this remarkable visualization transcends mere cartography; it is a profound narrative of one of history's most epic campaigns. As you embark on a journey through this iconic map, you will step back in time to witness the audacious rise and staggering fall of Napoleon Bonaparte's Grande Armée during the ill-fated Russian campaign of 1812.

<a href= "https://en.wikipedia.org/wiki/Charles_Joseph_Minard">Charles Joseph Minard</a>, a French civil engineer, is celebrated not only for his technical prowess but also for his artistic sensibility. His Napoleon Map, often heralded as a pinnacle of information design, marries geography, statistics, and storytelling in a single, elegant composition. With a deft hand, Minard illustrates not just the geography of the campaign, but also its human toll, painting a vivid portrait of triumph and tragedy on a continental scale.

In this introduction, I shall set the stage for your brief exploration of this cartographic masterpiece.
This is an ambitious project that seeks to bridge the gap between historical cartography and contemporary interactive method. By reviving Minard's timeless work through innovative design and technology, I aim to make this historical narrative more accessible and engaging than ever before. This project represents a tribute to the past, a celebration of modern data visualization, and a testament to the enduring power of storytelling through data.

Here are a bunch of interesting things we should read :smile::

*https://www.edwardtufte.com/bboard/q-and-a-fetch-msg?msg_id=0003mn </br>
*https://www.edwardtufte.com/tufte/minard </br>
*https://edspace.american.edu/visualwar/minard/ </br>
*https://chezvoila.com/blog/minard-map/ </br>
*https://thoughtbot.com/blog/analyzing-minards-visualization-of-napoleons-1812-march </br>
*http://euclid.psych.yorku.ca/datavis/gallery/re-minard.php </br>

Use the `VisualizationAssignment_1_Hua-Quang-Huy-Nguyen.ipynb` to get started.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

This section should list any major frameworks/libraries used to bootstrap your project. Leave any add-ons/plugins for the acknowledgements section.

* Python
* Library: pandas, numpy, folium, ...
* [![Folium][Folium.python]][Folium-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### References

Data is sourced from:
* [https://vincentarelbundock.github.io/Rdatasets/articles/data.html](https://vincentarelbundock.github.io/Rdatasets/articles/data.html)
Any analysis or commentary is the opinion of the author and should not be construed as advice.

### Facts

_Originally created in 1869, Minard's map ingeniously combined geographical information, troop strength, temperature, and time into a single compelling narrative. His work has inspired generations of data analysts, cartographers, and historians.
However, there are some <a href='https://chezvoila.com/blog/minard-map/'> facts</a> that may wow you.

1. It was not contemporary when the map was designed. </br>
Minard created the map 57 years after the event had happened.
2. The march doesn’t start in France, but in then-Poland (now Lithuania).
3. The map doesn’t show the main cause of the losses and doesn't mention Napoleon.
4. Temperatures are in an old-fashioned scale of Reaumur, which vitally needs to convert to Celsius.
5. <a href= "https://www.jla-data.net/eng/minard-map-tidygeocoder/?fbclid=IwAR1WeFzLaoNSOzvZviFDxIdk8YEPtRmZgjpLGpwgjR2qSRj7QSgne5B4Irg"> The names that Monsieur Minard used in his map proved difficult to use in modern geocoding use cases </a></br>
Some toponomy have changed their names ever since.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->
## Roadmap

- [x] Create a visual interactive map.
- [x] Add topology and longitude and latitude.
- [x] Add Ant-path line to demonstrate the direction of each groups.
- [x] Add Circle Bubble to illustrate the volume of men who entered and retracted the field.
- [x] Add Heatmap to show temperature with related date.
- [x] Add Borderline and River GeoJson to clearly demonstrate that geographical condition did affect the loss of men.
- [ ] Multi-language Support.
    - [x] English.
    - [ ] French.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

Here is a demo figure of the final map
  <a href="https://github.com/quanghuynguyenhua/Minard-Map/blob/main/demo.png">
    <img src="/demo.png" alt="Logo" >
  </a>

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

quanghuynguyenhua@example.com

Project Link: [https://github.com/quanghuynguyenhua/Minard-Map](https://github.com/quanghuynguyenhua/Minard-Map)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
<!--
* [Malven's Flexbox Cheatsheet](https://flexbox.malven.co/)
* [Malven's Grid Cheatsheet](https://grid.malven.co/)
* [Img Shields](https://shields.io)
-->
* [GitHub Pages](https://pages.github.com)
* [Font Awesome](https://fontawesome.com)
* [Folium library](https://python-visualization.github.io/folium/latest)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



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
[Folium.python]: https://img.shields.io/pypi/pyversions/Folium?logo=Folium&label=Folium&link=https%3A%2F%2Fpython-visualization.github.io%2Ffolium%2Flatest%2F
[Folium-url]: https://python-visualization.github.io/folium/latest/
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
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
