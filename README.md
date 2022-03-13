# Mission to Mars
The purpose of this repository is to create a web app that will scrape several websites for information about Mars and present that information.

### Resources
Several websites were utilized for obtaining Mars data:
- https://redplanetscience.com/
- https://spaceimages-mars.com/
- https://galaxyfacts-mars.com/
- https://astrogeology.usgs.gov/

Files:
- Web app file: [app.py](https://github.com/MDHetrick/Mission-to-Mars/blob/main/app.py)
- Scraping file: [scraping.py](https://github.com/MDHetrick/Mission-to-Mars/blob/main/scraping.py)
- HTML index file: [index_v3.html](https://github.com/MDHetrick/Mission-to-Mars/blob/main/templates/index_v3.html)


### HTML File Edits
Once the information in the web app was populated, the styling was modified. The final styled page is shown below.

![Image](https://github.com/MDHetrick/Mission-to-Mars/blob/main/resources/mars_full_page.png)

#### Mobile Responsiveness
Additional column sizes were added to the mars facts section for mobile responsiveness. Several mobile dimension options were evaluated. The iPhone SE dimension output is shown below.

![Image](https://github.com/MDHetrick/Mission-to-Mars/blob/main/resources/mars_iPhoneSE_page.png)

*Note: the images are discontinuous due to the screen capture program. The real-time webpage displays correctly*

#### Styling with Additional Bootstrap 3 components
Modifications to "Scrape New Data" button
- Modified style from "primary" to "success"
- Changed size from large to block-level
Modification to Mars News block
- The "Mars News" row was formatted as a basic panel with the title in a "heading" class, and the text in a "body" class.
