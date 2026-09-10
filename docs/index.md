---
title: Home
layout: home
nav_order: 1
permalink: /
---

{: .fs-9 }

<!-- <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; margin-bottom: 1.5rem;">
  <iframe src="https://www.youtube.com/embed/DaMCTH4qZTE" title="SPROUT overview video" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border: 0;" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div> -->

<i>An open-source, open-hardware soft robot platform for search and rescue and confined space operations.</i>
{: .fs-6 .fw-300 }

[Get started with Documentation]({{ site.baseurl }}/documentation/){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 }
[View the repository on GitHub](https://github.com/hadr-robotics/sprout){: .btn .fs-5 .mb-4 .mb-md-0 }

---

## What is SPROUT?

SPROUT is a fully open-source, open-hardware soft robot built for search-and-rescue
applications. It pairs a pneumatically-actuated "vine robot" body with a
field-deployable compute box that handles onboard computation, power
regulation, actuator control, sensing, and networking.

Everything needed to build your own SPROUT — mechanical CAD, PCB designs, bills
of materials, assembly instructions, and the full software/ROS 2 stack — is
released here under the MIT license.

## Site Map

This site mirrors the folder structure of the [`SPROUT_Design`]({{ site.github_tree }}/SPROUT_Design) directory in the repository, so every page here has a matching source folder you can browse, clone, or download.

| Section | What's inside | Source folder |
|---|---|---|
| [Documentation]({{ site.baseurl }}/documentation/) | Bill of materials, enclosure prep, assembly, and wiring guides for the compute box | [`SPROUT_Design/Documentation`]({{ site.github_tree }}/SPROUT_Design/Documentation) (photos and BOM spreadsheet only — guides are authored directly on this site) |
| [CAD]({{ site.baseurl }}/cad/) | SolidWorks/STEP models for the compute box and robot base | [`SPROUT_Design/CAD`]({{ site.github_tree }}/SPROUT_Design/CAD) |
| [Electronics]({{ site.baseurl }}/electronics/) | Custom Arduino shield PCB (KiCad project, gerbers, schematics) | [`SPROUT_Design/Electronics`]({{ site.github_tree }}/SPROUT_Design/Electronics) |
| [Software]({{ site.baseurl }}/software/) | Jetson bootstrap guide and the `sprout_ros` ROS 2 stack | [`SPROUT_Design/Code`]({{ site.github_tree }}/SPROUT_Design/Code) |

## License

SPROUT is released under the [MIT License]({{ site.github_blob }}/LICENSE).

---

## Team

> Team and affiliation information withheld for double-blind review.

{% comment %}
<style>
  .team-grid {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 2rem;
    margin: 1.5rem 0 2rem;
  }
  .team-member {
    width: 140px;
    text-align: center;
  }
  .team-member img {
    width: 120px;
    height: 120px;
    object-fit: cover;
    border-radius: 50%;
    display: block;
    margin: 0 auto 0.6rem;
    box-shadow: 0 1px 4px rgba(0, 0, 0, 0.2);
    background-color: #eaf5ec;
  }
  .team-member .team-name {
    font-weight: 600;
    font-size: 0.95rem;
  }
  .team-member .team-role {
    font-size: 0.8rem;
    color: #5c5962;
  }
</style>
{% endcomment %}