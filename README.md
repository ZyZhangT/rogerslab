## Link

[Rogers Lab](https://hyejinim.github.io/rogerslab)

## Get Started

### How to Update Content
1. Add your project information to data.json
```javascript
        {
            "id": "projectid",
            "title": "Project Title",
            "subtitle": "Briefly explain what this project is",
            "authors": "First Last, First Last",
            "teaser": "assets/projectid/teaser.png",
            "tags":["Engineering", "System"],
            "materials": [
                { 
                    "label": "Paper",
                    "path": "assets/projectid/paper.pdf"
                },
                { 
                    "label": "Video",
                    "path": "assets/projectid/video.mp4""
                },
                { 
                    "label": "Website",
                    "path": "https://hyejinim.github.io/draw2code"
                }
            ],
            "desc": "An integrated educational learning development web-based environment intended for learning and teaching through robotics. CORP combines the potential of the Google web-based platform with the educational robot technology of the LEGO Mindstorms EV3 Kit. Designed for students in primary and high school, CORP allows students from different locations to interact collaboratively through sharing a Google Slide document with a custom add-on developed to talk to the EV3 robot."
        }
```
* Create a unique project ID for `id`. It will be used for the filename to create a project detail page.
  * Make it concise and meaningful
  * Use all lowercase
  * Don't use spaces in the project ID
  * A hyphen is OK for a word separator
* Choose 2 tags among below that represent your project
  * `Robotics, Engineering, Computatioanl Thinking, System, Educational Tool`
* Update path for materials
3. Add a folder that includes all the materials for the project
* Use the project ID for the folder name
* Use the name below for file names
  * `teaser.png`: A teaser image is necessary for each project
  * `paper.pdf`: Add if you have a relevant paper
  * `video.mp4`: Add if you have a relevant video

## Acknowledgement
This website is built and managed by Hyejin Im and Milan Dahal.

Thanks to Nam Wook Kim for the original website templates.
