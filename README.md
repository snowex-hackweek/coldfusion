# coldfusion
Thanks to Lindsey Heagey and Joachim Meyer for the README template!

## Project Summary

### `Coldfusion`

A team effort to merge of GPR and LiDAR datasets during SnowEx hackweek 2022.

![Overlapping Pit Locations](jovyan@jupyter-korimooney:~/coldfusion/contributors/korimooney/PitOverlap.jpg)

### `Collaborators on this project`

- Curtis Beutler [CBeutler](https://github.com/CBeutler)
- Peter Marshall [pmarshall24](https://github.com/pmarshall24)
- Tate Meehan [tatemeehan](https://github.com/tatemeehan)
- Kori Mooney [korimooney](https://github.com/korimooney)
- Alicia Pouw [aliciapouw21](https://github.com/aliciapouw21)
- Thomas Van Der Weide [tvanderweide](https://github.com/tvanderweide)
- Megan Verfaillie [Megan-Verf](https://github.com/Megan-Verf)
- Seth Vanderwilt [sethv](https://github.com/sethv)

### `Database information`
SiteData
: snowpit information and metadata

PointData
: GPR data, snow probes

ImageData
: LiDAR ASO data

LayerData 
: snow pit data (density, depth)

### `Game Plan`
1. Find LiDAR area with GPR validation data in western and central Grand Mesa study area and create code to query data from database. 
Validate using:
    - Snow pits (Snow depths & Density)
    - Magnaprobe (snow depth)
    - SNOTEL (snow depth) [Mesa Lakes (622)](https://wcc.sc.egov.usda.gov/nwcc/site?sitenum=622&state=co)
2. Ensure GPR & LiDAR are on like coordinate systems and co-locate GPR points to LiDAR points
3. Calculate snow density using dielectric permittivity and wave speed using LiDAR snow depths.
4. Validate by co-locating in-situ snow density and snow depth

### `Next Steps`
Application of Machine Learning to begin looking at other study sites

### `Application Example`

List one specific application of this work.

### `Sample data`

If you already have some data to explore, briefly describe it here (size, format, how to access).

### `Existing methods`

How would you or others traditionally try to address this problem?

### `Proposed methods/tools`

Building from what you learn at this hackweek, what new approaches would you like to try to implement?

### `Background reading`

Optional: links to manuscripts or technical documents for more in-depth analysis.

## Files

* `.gitignore`
<br> Globally ignored files by `git` for the project.
* `environment.yml`
<br> `conda` environment description needed to run this project.
* `README.md`
<br> Description of the project (see suggested headings below)

## Folders

### `contributors`
Each team member has their own folder under contributors, where they can work on their contribution to the project. Having a dedicated folder for each person prevents conflicts when merging with the main branch.

### `notebooks`
Notebooks that are considered delivered results for the project should go in here.

### `scripts`
Helper utilities that are shared with the team

