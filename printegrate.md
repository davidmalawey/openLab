## Printegrate:
Integrating 3d printing with off-the-shelf parts. This page is for examples that integrate 3D printing with OTS parts.  I'll call it printegrating, to set apart these designs from all the world's 3D printed parts.

**Problem** Designers are uninformed in design-for-manufacturing in FDM; these examples show how. Designers need modularity to raise effort on each piece of a design.  These examples demonstrate demonstrate modularity.  Designers are unaware of the best off-the-shelf components; these examples highlight suitable components. Designers are reinventing the same designs; these designs aim for best-in-class quality.

**Problem2** Open Source Parts must be adjustable; these open parts are adjustable.  Parametric parts lack instruction on how to adjust parameters; these examples indicate how to adjust them.  Open designs only suit a specific need; these examples are versatile.

**Value** Printegrated parts are the optimal type of part to open source; the most leveraged way for designers to create value. Compared to a parametric part, we double the value by including parameters which are derived from the mating part. Compared with plain prints, they capture the qualities of a metal part. They intrinsically reduce the time and material for printing. They spur ideas because the audience is familiar with the 50-year-old part. To support engineering research, the assembled printegrations carry documentation produced by the manufacturers of the off-the-shelf parts. To support evaluation, the OTS parts carry certifications & testing metrics.

>
> MMET Students & Professors:
> As your Technical Laboratory Coordinator I would like to 

**Reducer**
An example part for reducing a hole to host a fastener.  One example is to outfit concentric shafts in a steel outlet box to achieve nicely-aligned axes in a gearbox.   The second example offers a location for M8 fastener in a large 14mm hole of a disc brake.  Utility aside, it's a lesson in compliant mechanisms, gaining concentricity, bearing loads on a 3D printed part, retaining a steel nut with friction.  
* Jump to grabCAD post:[reducer model](https://grabcad.com/library/reducer-115)

- ![grabcad image, reducer1](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/bf1a57fef2f3299b50b64ec13ba34092/original.jpg)
- ![grabcad image, reducer in disc brake](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/7da5515543f983b4f8067bdb2cd499ce/original.jpg)
- ![linked image, reducer section](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/37432ac2405823741c98dce59bbf3fd1/original.JPG)


**Hinge**
Printable and print-in-place design for a hinge for 2020 extrusions. Tap M6 threads in a 2020 extrusion or mount to the side of the extrusion with M5x10mm fastener as usual.  The hinge pin uses 1/4 or 6mm stock such as HDPE tubing, or a simple steel cotter pin. The hinge model is highly parametric and many variations are possible. Note the limits on the rotation built into the model.  The rotation stops at +90 or -90 for the template parts.  Important templates include hingeEnd for extrusion ends, hinge30 for 3030 extrusions, and hingeRod for joining 10mm rebar to the assembly.  
* Model for [hingeEnd here](https://grabcad.com/library/hinge_end-1)
* model for [hingeRod here](https://grabcad.com/library/hingerod-1)
* model for [pivotBeam here](https://grabcad.com/library/pivotbeam-1) which features dual-rotation for 180 degrees while maintaining strength.
  
- ![grabcad image, hinge end](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/f669f96e0e3e77caca9a3cbfcb0a2fa9/original.jpg)
- ![grabcad image, hinge](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/7da5515543f983b4f8067bdb2cd499ce/original.jpg)
- ![linked image hingeRod](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/5c48d2f9cdffdb95629a98a5248e95d4/original.jpg)

  
**PivotBeam**
This double-hinge model predates the hinge designs for 2020 extrusion, and uses a 3/8 pin instead of the smaller 1/4 pin.  Again, the common LDPE tubing for water distribution fits in this design.  The hinge has 2DOF which means the strategy for CAD modeling is rebuilt from the beginning of the feature tree, compared with other hinge parts.  The model will print-in-place without supports, and produce three separate but interlinking bodies.
* Model for [pivotbeam on GrabCAD](https://grabcad.com/library/pivotbeam-1)

- ![linked image, pivotBeam](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/429120eb8b0ff14aba73812c9da91e6d/original.JPG)
- ![linked pivotbeam photo](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/664899e789a93b41ac4b7d161640d058/original.jpg)
- ![linked pivotbeam photo2](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/a3ca020667c495bd0a8325c0842493a8/original.jpg)


**HingeRound**
A special variation of the hinge which connects round tube.  The initial version works with 29mm OD tube, found in EMT Conduit of 1" trade-size.  This assembly consists of two CAD models: one for the hinge and one for the collars.  With this configuration, the collars are printed in an optional z-direction for speed and strength, while the hinge prints with two interconnected bodies, ready for pin-insert and snap-apart.  You can use superglue for a permanent bond between the ABS components, with a strong seam visible in the photos.  Alternatively, you can revise the main model to include the collar.  To raise the strength: add a metal hinge pin, raise the hinge-pin diameter, and increase exterior diameter of the bodies overall.  Several further changes are ready: add more fasteners to distribute load on the plastic if you intend to subject a strong pulling.  Note the flat faces on the round body; these are for improved printing performance, and creating a datum for marking and setup of the assembly. It's recommended to keep this flat region as it assists along several steps in building.
* Jump to [Hingeround CAD model](https://grabcad.com/library/hingeround-1)
  
- ![linked image, hingeround photo](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/b2471e29b4ba01e5b0f7791156417441/original.jpg)
- ![linked image, CAD model](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/b88f4c8838ccb6dfb9dc0de70199b694/original.jpg)
- ![linked photo, loaded hingeround](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/3ff876afc4f515b2722eeb109c970ba8/original.jpg)


**Collar**
This is a simple concept of gaining a concentric mate of round stock and unistrut steel channel. The example features 2-in PVC, schedule 40, and the collar set up to carry the weight of PVC while allowing it to turn. 
* see model for [unistrut collar here](https://grabcad.com/library/collar-14)
* see short video on youtube [for collar usage here](https://youtube.com/shorts/XqiS53RV34g).

- ![linked image, collar model](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/ce92b71f3c218147a42ce9fdc590a258/original.JPG)
- ![linked image, collar model2](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/2b9a81fce493bf2a91a5af277c61fad9/original.jpg)
- ![linked image, collar photo](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/43eadd1ba47b55aa9428b22af6dedacd/original.jpg)


**Hub**
Model and tutorial for integrating a bearing in a 3D print.  This model features two integrations:  The bearing and the steel octagon box are both integrated and the hub becomes a joining feature between two highly-useful parts. See images below featuring M5 machine screws, hex nuts, octagon handybox, and M8 screw as a shaft.
* Access the [Hub 3D Model on GrabCAD](https://grabcad.com/library/hub_0-1) 
* See the [youtube video here](https://youtu.be/QnAuQ8QLtgs) which is a full tutorial for the design process.
  
- ![hub assembly snapshot](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/20a22f48b02a1b4dba5f0afc02ead7f7/original.JPG)
- ![hub photo](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/1a4d9a8ec5c7cb4b650467375a733be5/original.jpg)
- ![hub snippet](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/0cf23646a2659c552a9b16fa881fd029/original.JPG)


**Sleeve**
A conforming geometry for the thin spiraling boss of a fiberglass rebar.  The aim of this part was to produce a strong connection to the fiberglass rebar (which has over 15,000lbs or 67 KN tensile strength) so that we can print connections and utilize this strength in our assemblies. The bar and sleeve (previously called "collar") was superglued and tested to 600lbs of pulling force without any signs of damage.  Get the [Sleeve CAD model here.](https://grabcad.com/library/sleeve_v1-1).

* See the youtube short, [introducing the rebar material](https://youtube.com/shorts/__aNzykhsqg?si=pgXa3hF_W7QmUM_o)
* see the youtube short, [demonstrating beam reinforcement with pinkbar](https://youtube.com/shorts/lyPtJus9-OI?si=nC0oP-atsofADlBO)
* see the youtube short, [testing tensile strength of sleeve joint](https://youtube.com/shorts/SVHGuEITloo?si=WJlmOZ7XONILFock)

- ![sleeve photo 1](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/166826426e365bdc536ee4de1cf8c5cf/original.jpg)
- ![sleeve photo 2](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/db2c6f84bf317579390448e15449b9c7/original.jpg)
- ![sleeve photo 3](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/a2d8eb6bbe586ff88a69bc10e5fd48b9/original.jpg)


**Mandrel**
A load-bearing part to secure a steel rod at the end.  The mandrel carries a nut (M8 hex nut), then inserts into round tube, then expands when tightened.  The mandrel compresses against the tube inside, generating friction to prevent spinning of the tube.  The fastener can pull the mandrel tightly against a flat surface with a hole.  One asseembly is demonstrated which connects the tube at 90 degrees to a steel channel (unistrut).
* Download the [Mandrel CAD model here](https://grabcad.com/library/mandrel_v1-1)
* Check out short [video on youtube for mandrel](https://youtu.be/PWyZB1nha_o)

- ![mandrel image 1, steel assembly](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/759aaa89313ae58071e69d521411cda0/original.jpg)
- ![mandrel image 2, nut inserted](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/e19dcb028bdd568342ec71ea30c5f467/original.jpg)
- ![mandrel image 3, with EMT spec](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/e9f004058d14212b1579f17170506f73/original.jpg)


**BottleCap**
A threaded cap for glass bottles.  Adjust the size to fit a new bottle.  Adjust the thread to make a new (but still printable) thread.  Add a sealing feature to gain airtightness.  Study the design tree to learn to make threads in Solidworks.  This design is intended for many different purposes.  In the example, the purpose is fitting this cap to a drink bottle, for a result that is more re-usable, more customizable, more durable, and gives control over color to the user. Implement an off-the-shelf seal for surefire watertight and airtight fit, like [these 35mm seals on amazon](https://amzn.to/478Fnt0).  Jump to the [CAD model on GrabCAD](https://grabcad.com/library/cap-43) and download a parametric model.  These threads tolerate a strong tightening torque on the cap but the cap does not perform airtight sealing right off-the-print.  There is much to learn from this example part.

- ![bottle cap original & printed](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/c533e0dcbd636781b1bc4650e1dd0c9a/original.jpg)
- ![cap bottles size photo](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/a5b9940805f403c7d8faa2a230da1468/original.jpg)
- ![cap size snippet](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/1148c8c902ae0bd4ff8536bd32c8df54/original.jpg)


**Bearing**
This bearing is: A functional load-bearing design with print-in-place geometry.  A low-cost bearing which accepts many sizes of balls, and many materials.  A parametric part which can be adjusted for inner diameter, outer diameter, and width to mate any pair of round geometries.  A desich which can bond permanently to a matching PVC tube for permanent integration.  The design has so many utilities that a [repository, OpenSpin,](qr.net/openspinproject) was initiated to expand the documentation.  
* Access the initial CAD [model here on grabCAD](https://grabcad.com/library/openspin-1)
* Check [short video "borrow a tolerance"](https://www.youtube.com/shorts/3tW8U1KpCsk)
* Check [short video "use balls"](https://www.youtube.com/shorts/EInM1E-zxMI)

- ![bearing image main](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/4161ce89bc52bb879fad5b71377b365d/original.jpg)
- ![bearing image, variations](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/85c3e4fc8e32438015643e06781cb890/original.jpg)
- ![bearing image, mated](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/c4d4ce72795777b3a0208e7b9dd5bd8a/original.jpg)


**RollerBracket**
A tested & validated design to attach wheels to your 3030 aluminum extrusion.  It includes two fasteners, carries a 6mm center pin, and accomodates a common OTS skate wheel with the high strength & durability of urethane.  These rollers are used in the lab for custom built racks and holding up for 3+ years. 
* Access [roller bracket model](https://grabcad.com/library/roller_bracket-1) and see the third photo showing M8 fastener which threads into the end of the extrusion.
* View [short video roller bracket](https://youtu.be/yQp7ltsO5FE)

- ![linked image roller bracket](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/c4b9bf3698a272ce76726224b1d1e4cd/original.jpg)
- ![linked image 2](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/645d1f8ea41fa2f610d8cd5d655461fd/original.jpg)
- ![linked image 3](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/7b85a325f323775c1595ebdd859ab726/original.jpg)


**Caster**
A caster bracket for implementing the very popular OTS casters having 76mm diameter wheel and a snap-in pin.  These are so popular that you can sometimes find the whole caster assembly (minus this 3D printable bracket) for a lower cost than a wheel, per piece. Modern versions have a heavy urethane wheel, good quality bearings, and stamped steel fork with a steel hinge-pin and ball-bearing pivot.  That is, two degrees of freedom for your rolling chassis and we can reliably accomodate these into a 3D print without any postprocessing. The pin fits vertically while two horizontal holes guide your M6 fasteners into aluminum rail or other chassis material.

- ![linked image, caster CAD](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/55b5e3ff608a42cd27007b29a782002a/original.jpg)
- ![linked image, caster on scuttle](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/8883ef0c4fed7c84f0a7f30b38196285/original.jpg)
- ![linked image, caster CAD section](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/bc6c62b2490a850b201959967b3f9c6f/original.jpg)


## Multipurpose
The value and the purpose of these posts has several parallel elements.  An example for CAD modeling, a functional printable part, an initiation to a community-supported design series, even technologies suited for academic publication.  Researchers are invited to reach out and co-author journal papers if desired.  An initial discussion in the following video helps break out the value of each element in the open models, which is far different than a typical online post.  Jump to [value breakdown](https://youtu.be/IvZXdxWh7dg?t=435) in the youtube video for the explanation.

<iframe width="600" src="https://www.youtube.com/embed/IvZXdxWh7dg" title="How to solve a simple 60 year old problem" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
