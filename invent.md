Functional designs, all in one place for you to copy and use in your lab.  In a dream world, these items will become seminal ideas that get improved by experts around the world so we can help each other.  Please do not expect sparkling and exotic machines in this page.  Rather, look for the purpose(s) for which the concept was intended and if you have some expertise, know that these are shared in many cases to drive down cost of expensive items, enhance availability of hard-to-get items, or enhance the usability of cheap & free devices that just don't quite meet the needs of our lab.

## DesignRules
In 2025.09 I am making the first try at the set of design rules that guide designs.  This is an immense challenge but following these rules will make prototypes that are modern, with simple materials, fewer decisions, and more reliability.
1. Start with these materials for long beams: Aluminum Extrusion 30mm, Steel EMT conduit 3/4in, Unistrut, and DIN rail.
2. Attach devices using an established standard: Cameras & Instruments (1/4-20 threads, cold-shoe mounts) Electronics modules (DIN rail mounting) and structural joints (EMT conduit joints, unistrut angle brackets).
3. Seek a benchmark for every design.  Include the simplest additional parts to reproduce that assembly. First prefer off-the-shelf parts with families, then 3D printed designs as needed, and common metric fasteners.
4. Design of assembly and design of a part are two separate projects.  Also design of anything new (geometry for sealing, fastener arrangement, nozzle for flow, articulating joint) is an independent project.
5. Only pursue designs which have at most one invention. (ie, an assembly of existing parts that adds suds into a garden sprayer, using all off-the-shelf parts and validated 3D models.  The assembly itself is the design project).  If you want to design a mobile robot with 4 mechanum wheels - then you should be starting with an already validated robot having ordinary wheels).  You cannot validate two unknowns in the same build, except with advanced strategies)
6. To consider any complex geometry, break it down into minimal elements: A chassis geometry is made of rigid beams, joints, panels, and interface (for wires, plumbing, air, or controls).
7. Then build up the geometry in-mind with the preferred materials:  Flat panels 1/4in, 30mm square extrusions, round rods, fasteners, seals, holes, etc).
8. Members are all joined collinear, 90 degrees, or special angle.  Utilize collinear and right-angles as much as possible.


**Guiding Goals**
Designs fill a wide range of applications but have this in common.  The aim is to avoid custom metal fabrication, reuse common components, borrow the max possible geometries from reputable suppliers, and minimize design effort.


## (1)Ready
All the ready devices all in one place.  (or at least some of them.) In order to make new solutions in our world, we need new tools.  To make new tools, we need new workplace solutions.   For each solution that has been designed, implemented, tested, and put into use in the openLab project, I'm publishing my CAD models with the keyword **openlab** on GrabCAD.

**Jump to [GrabCAD collection](https://grabcad.com/library?page=1&time=all_time&sort=recent&query=openlab)**

![img_cad1 preview of grabCAD keyword](img/img_cad1.jpg)


## (2)Concept
Free invention ideas.

This is what I would call "free invention ideas" at age 12 and what I would now call daily notes of relevant tech concepts that have some potential value.   A large portion would be hard to understand without any engineering expertise, a large portion is totally dependent on the context I'm working in, and that leaves a little bit that may have value for those of us with curiosity & an interest.  To be honest, I believe in the path of discovering skillsets of making things, discovering materials, new ways to measure, and so forth - you will naturally get loads and loads of ideas of your own.  And the great thing about acting on your idea is that you can implement it fully in the context that you see it is a good fit.  Just like a hiking boot may be a climber's idea but it does no good for an ice skater.  The more deeply technical we become, the more specific it requires us to constrain our environment to extract the value of a simple concept.  -David M

[download TechNotes 2024 pdf](docs/techNotes_2024.pdf)

![thumbnail 2024](img/img_techNotes2024.jpg)

---

[download TechNotes 2023 pdf](docs/techNotes_2023.pdf)

![thumbnail 2023](img/img_techNotes2023.jpg)

## Standards

Project Readiness Levels
* This is an evolving and new(ish) type of term for dividing projects into various stages.  Someone may do great work at PRL 1 and it looks very different than at PRL6.  By discussing our projects in terms of a "project readiness level" it is easier to see what are the needs and the focus of the engineering for an "invention."  The definitions are not set in stone and I'm publishing to get ongoing feedback from the community to refine our definitions and make it optimally helpful.
  
[Download 2023_Project_Readiness.pdf](https://github.com/user-attachments/files/19146886/2023_Project_Readiness.pdf)

![project readiness snippet](img/img_PRL.jpg)

## CAD-models

Good places to discover CAD models.  We use grabCAD This list was generated with help from ChatGPT on 2025.03


| Feature                           | GrabCAD | Thingiverse | Printables | Free3D    | TraceParts  |
| --------------------------------- | ------- | ----------- | ---------- | --------- | ----------- |
| **3D Model Repository**           | ✅       | ✅           | ✅          | ✅         | ✅           |
| **Geometric Search**              | ❌       | ❌           | ❌          | ❌         | ❌           |
| **Focus on 3D Printing**          | ❌       | ✅           | ✅          | ⚠️ (some) | ❌           |
| **Engineering/Industrial Models** | ✅       | ❌           | ❌          | ⚠️ (some) | ✅           |
| **Collaboration Tools**           | ✅       | ❌           | ❌          | ❌         | ❌           |
| **Version Control**               | ✅       | ❌           | ❌          | ❌         | ❌           |
| **Wide File Type Support**        | ✅       | STL only    | STL only   | Mixed     | CAD formats |

## Tutorial
Here's a deep dive into a highly useful design that you can follow along.
* See how the design standards map into a specific model
* See what model features support printability
* See how geometry is defined by equations to make a part parametric
* See a variation built on top of an initial design to create a new functional part

* Download [Hinge Design Tutorial PDF](docs/)
- ![hinge tutorial preview 1](img/preview_hingeTutorial1.jpg)
- ![hinge tutorial preview 2](img/preview_hingeTutorial2.jpg)

**Takeaways:**

_as described by chatgpt, and I generally agree.  We have not yet used TraceParts but we have used the others often_

- **Use Thangs if** you need **geometric search, version tracking, and both printable & engineering CAD models**.
- **Use GrabCAD for** professional and mechanical engineering CAD files.
- **Use Thingiverse or Printables if** you mainly need **hobbyist 3D printable files**.
- **Use TraceParts if** you want **industry-standard parts and engineering components**.
- **Use Free3D for** a mix of **general 3D models** (not necessarily CAD-focused).

## Incomplete
These projects are not yet ready and I'd love to have support to finish them.

**Universal Joint**
This CV joint (constant velocity joint) has a version-1 attempt, and features a balls-in-cup assembly.  I have not yet been able to test, characterize, and revise the design. But a CV joint has a million use-cases, and it deserves to have a much higher design effort and several different styles of tests that can characterize it.  Given the limits/advantage of 3D printing, what design should become the flagship design for makers?  I hope to raise the performance, test various sizes, and design a representative use-case which accompanies the design documents to define the "central" use case from which other makers can vary.  

Check out [cv joint design on grabCAD](https://grabcad.com/library/cvjoint-1)
[image from cv joint post](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/51ffb6b986a00e788e107c58f944f8ca/original.JPG)
