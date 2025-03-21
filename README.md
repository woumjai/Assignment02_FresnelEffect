# Assignment02_FresnelEffect
<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a id="readme-top"></a>

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->


Assignment 1, VIZA 626 Generative Art &amp; Design (Spring 2025)

<!-- PROJECT LOGO -->
<br />
<div align="center">
  </a>

  <h3 align="center">Fresnel Effect: Ghostly Shader</h3>

  <p align="center">
    I implemented a ghostly shader using the Fresnel effect to create an ethereal rim-lighting effect. By adjusting the Fresnel falloff and blending it with emissive properties, the shader enhances the spectral appearance, making the edges glow while maintaining translucency. This technique helps achieve a convincing ghostly presence in real-time rendering.
    <br />
    <a  /> 
    <br />
    <br />
    <a href="https://carhua.myportfolio.com">Carolyn Hua</a>
    &middot;
    <a href="https://sites.google.com/view/viza626/home">VIZA 626</a>
  </p>
</div>

[![fresnel][images-fig1]](https://example.com)

Figure 1. Ghostly shader showcasing the Fresnel effect. The images display variations in parameter adjustments, including changes to the Fresnel exponent, intensity, and emissive blending, which affect the glow and translucency of the shader.

<!-- Abstract -->
## Abstract
Your abstract here: 100 words here.
The Fresnel effect describes the relationship between a surface's reflectivity and the viewing angle, making it a critical component in realistic shading. This paper explores the significance of Fresnel in rendering and its role in conveying translucency and energy in visual effects. I detail the implementation of the Fresnel term in a custom ghostly shader, using it to enhance edge lighting and create an ethereal appearance. By manipulating Fresnel intensity and blending it with emissive properties, the shader dynamically responds to viewing angles, reinforcing an illusion of spectral presence. 

[![4-comma][images-fig2]](https://example.com)

Figure 2. Fresnel algorithm used in the ghostly shader. This implementation calculates the rim-lighting effect based on the view angle, enhancing the glow and translucency. Adjusting the exponent and intensity parameters controls the falloff, influencing the final appearance of the spectral effect.

<!-- Introduction and Related Works -->
## Introduction and Related Works

Your Introduction and Related Works here: 200 words here.(3 refs)

In real-world optics, the Fresnel effect is influenced by polarization, which affects how light reflects based on the orientation of the light wave. However, in computer graphics, particularly for real-time rendering, this effect is often simplified to optimize performance. By omitting polarization, we focus on the relationship between viewing angle and surface reflectivity, a common CG approach that balances realism with efficiency. As John Hable discusses in his blog on filmic rendering [1], Fresnel is present in all materials, influencing how they interact with light, even if they don’t appear reflective at first glance.

For the purposes of this paper, I explore the simplified Fresnel equation, widely used in CG workflows to create materials that react naturally to varying angles of view. I apply this concept in a ghostly shader designed to enhance the illusion of an ethereal presence. By leveraging Fresnel-driven edge lighting, the shader creates a spectral glow that dynamically responds to the viewer’s perspective. This effect mimics how translucent or semi-transparent materials interact with light, reinforcing the ghostly aesthetic. While avoiding the complexity of full light interactions, this shader demonstrates how the Fresnel effect can be creatively applied in stylized rendering to achieve compelling visual results.

How to use subsection:

### Built With

This section should list any major frameworks/libraries used to bootstrap your project. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.

## Methodology

Your Methodology and Related Works here: 300 words here.

[![4-comma][images-fig3]](https://example.com)

Figure 3. Methodology and Workflow: This figure should provide a comprehensive overview of the process used to create or generate your image.

[![4-comma][images-fig4]](https://example.com)

Figure 4. description for Figure 5

## Result and Future Work
Your Result and Future Work here: 200 words here.

[![4-comma][images-fig5]](https://example.com)

Figure 5. description for Figure 5

## Conclusion
Your Conclusion here: 100 words here

[![4-comma][images-fig6]](https://example.com)

Figure 6. description for Figure 6

<!-- Bibliography -->
## Bibliography 
[1] Hable, John. "Everything Has Fresnel." Filmic Worlds, 5 Dec. 2010, http://filmicworlds.com/blog/everything-has-fresnel/.

[2] Halladay, Kyle. "Fresnel Shaders: From the Ground Up." Kyle Halladay, 18 Feb. 2014, https://kylehalladay.com/blog/tutorial/2014/02/18/Fresnel-Shaders-From-The-Ground-Up.html.

[3] Kim, You-Jin, Misha Sra, and Tobias Höllerer. "Audience Amplified: Virtual Audiences in Asynchronously Performed AR Theater." 2024 IEEE International Symposium on Mixed and Augmented Reality (ISMAR). IEEE, 2024. 



<!-- CONTACT -->
## Contact

Carolyn Hua - chua@tamu.edu

Personal Website: [https://carhua.myportfolio.com](https://carhua.myportfolio.com/)
[2][3]




<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

This work is submitted as part of Assignment 1 for the VIZA 626 course at Texas A&M University, under the instruction of Professor You-Jin Kim, during the Spring 2025 semester.

VIZA 626 Class Website: [https://sites.google.com/view/viza626/](https://sites.google.com/view/viza626/home)

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
[images-fig1]: images/fig1.png
[images-fig2]: images/fig2.jpg
[images-fig3]: images/fig3.jpg
[images-fig4]: images/fig4.png
[images-fig5]: images/fig5.png
[images-fig6]: images/fig6.png
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
