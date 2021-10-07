# Assignment 1: Making Shoes

I made a pair of Japanese [Geta](https://en.wikipedia.org/wiki/Geta_(footwear)), largely because I was quite limited on time and this particular kind of shoe would be much easier than other types of footwear to fabricate under a tight schedule. This is for the following reasons

- Apart from the fabric thong, the shoe is made of a single rigid body.
- The geometry of the rigid body is blocky and amenable to quick prototyping.
- The geometry of the rigid body can be fabricated by the _stacking method_ using a laser cutter.

Because my research thinks about how makers can better understand the constraints of various fabrication machines and workflows, I was interested in understanding my own thought process here.
My first priority was thinking _how can I fabricate this really quicky?_ The fastest machine to iterate on is the laser cutter, and geta seemed like a good choice for that.
This is interesting: rather than think about what I want to make, I proritize how to make it—the machine influences the product.
The next problem I faced is that it would be difficult to create boxes via fabricating the sides, because then I would have think about joinery and material thicknesses from multiple angles.
Because I also needed the shoes to be sturdy, I decided to create volumes by stacking sheet materials via vertical slicing.
Once I had figured out this approach, only then did I go to CAD software, and to the makerspace.

# CAD

<img width="1552" alt="rhino_top" src="https://user-images.githubusercontent.com/4927336/136448331-f262a8f2-2f71-44b6-b171-ae4f8ab2531f.png">
<img width="1552" alt="rhino_persp" src="https://user-images.githubusercontent.com/4927336/136448351-810396a6-3160-4f71-8fdd-70f304e8050d.png">

# Fabrication

![cutting](https://user-images.githubusercontent.com/4927336/136448503-6717502d-920e-4d8a-bd61-92085a3ecdc3.JPG)

# Lesson Learned

- It would have been easier _not_ to design the holes for the thong in CAD, and rather fabricate the top piece first, glue the sheets, and then make holes with a drill press. It's far easier to reason about appropriate hole sizes and placement once the piece is in one's hand (or if only there were some way to formalize hole placement logic programatically...).
