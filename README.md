# nazca-patched
[Nazca Design](https://nazca-design.org/) is an open source python package used to design photonic ICs. The last official release, [0.5.13](https://nazca-design.org/download/), is dated 2021-04-27 and unfortunately does not work out of the box anymore.

The package distributed in this repo has been patched to simply pin the version of the pandas-dependency to the latest working one. This means that the underlying issue has not been fixed but at least it works after following the official [installation instructions](https://nazca-design.org/installation/) (replacing step 2 with the zip from this repo of course).

I have tried emailing the original authors of Nazca about this issue but have yet to receive any answer.

### How do i install it?
Follow the official [installation instructions](https://nazca-design.org/installation/) but replace Step 2 with downloading [our zip file](https://github.com/UiT-Photonics/nazca-patched/raw/main/nazca-0.5.14.zip) and use that one in the subsequent steps.

### Will there be any further updates to Nazca in this repo?
Almost certainly not. Should there be any updates on the official site I will likely take this repo down or just replace it with a link and a note.

### Why is there just a zip file and no source code?
This is not intended to be a "living" repo but simply a place where we can download a version of Nazca to build legacy designs on new systems with slightly less friction.

