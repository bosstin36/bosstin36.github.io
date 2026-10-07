---
layout: page
title: CV
permalink: /cv/
---


>My key strength is being highly adaptable in my role. I am able to jump between code, tech-art and design to bridge the gaps between departments and teams. <br>
<br>
>In the past couple of years, here are  examples of work done for clients:
>- C++ UI backend engineering and widget creation for UE5
>- Unity to Godot asset converter tooling
>- Procedural cave + tunnel generation from Houdini to UE5
>- Volumetric cloud painting and skydome baking tools
>- Customisation of FluidFlux and FluidNinja plugins
>- Creating UMG and Postprocess visual effects and shaders
>- Console Profiling and Optimisation of code, blueprint and shaders

<br>

## 🤹‍♀️ Skills

- Extensive knowledge of Unreal Engine, Blueprint and UMG
- Unity, Godot, C#, C++, Python, Verse
- UI and UX implementation
- Profiling and Optimisation (including PS5 + Xbox)
- Procedural content, Houdini, Blender
- Materials/Shaders, Particles, Custom Pipeline and Engine Tooling
- Perforce, UGS, Scrum, Agile


<br>
<hr/>
<br>

## 🎮 Games

<div class="entries-grid-colcade" data-colcade="columns: .entry-col, items: .cv-game" >
    <div class="entry-col entry-col--1"></div>
    <div class="entry-col entry-col--2"></div>

{%- for game in site.data.cv.games -%}

<div markdown="1" class="cv-game" style="height:250px">

{% capture image %}/images/cv/{{game.image}}{% endcapture %}
{% include image.html url=image alt=game.title %}{: .align-left}

<br/>

### {{game.title}}
{: .no-margin}

<p>{{game.role}}<br/><span class="faded-text-color">{{game.studio}}</span></p>

</div>
{%- endfor -%}

</div>


<hr/>
<br>


## 👩🏻‍💻 Work Experience

<div style="display:flex; flex-direction:column" markdown="1">

{%- for job in site.data.cv.jobs -%}

### {{job.title}}
{: .no-margin}

<p><span class="faded-text-color"> {{job.company}}   -  <i>{{job.dates}}</i> </span> 
<br/>
{{job.description}}
</p>

{%- endfor -%}
</div>

<br>
<hr/>
<br>

## 📚 Education

<div style="display:flex; flex-direction:column" markdown="1">

{%- for education in site.data.cv.education -%}

### {{education.award}}
{: .no-margin}

<p><span class="faded-text-color"> {{education.date}} - {{education.from}}<i>{{education.grade}} </i> </span> <br/>

</p>

{%- endfor -%}
</div>

<br>

<br>

