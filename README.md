# CCMS-Authorit-Learning  
A beginner-friendly, foundation-level walkthrough of the Author-it CCMS interface and core concepts.

## About This Project
This project was created as part of my effort to learn new tools and expand my technical writing skill set. Since Author-it does not provide an easily accessible demo version, and many of their tutorial sites are inactive, I relied on alternative sources.

As such, all content in this guide was sourced from the company’s official YouTube channel:  
https://www.youtube.com/@authoritsoftwareco

More specifically, every topic in this project is based on notes taken from their 21-lesson tutorial playlist, starting from this video:  
https://youtu.be/jurg2TpoX7Y

All images included throughout the guide were taken directly from those videos.

Because these videos are quite old, some features, UI elements, or workflows described in this guide may differ from the modern Author-it product. Please treat this guide as an introductory learning resource rather than an up-to-date reference.

This project primarily exists for my own learning and documentation purposes. I have not used Author-it firsthand, so none of the information here should be taken as absolute.

## What This Guide Covers
This repository provides a structured, DITA-based walkthrough of the initial interface, object model, and functional concepts in Author-it.  

- Topics are primarily **concept topics**, with one **reference topic** for help resources.
- The guide is meant to introduce how the tool works, how objects relate to each other, and what authors can expect in the UI.
- Because the YouTube videos are demonstrations rather than step-by-step tutorials, the project follows a conceptual structure rather than a task-heavy one.

## DITA Structure and Elements Used
Since this is a simple walkthrough-style project, most topics use straightforward DITA structure and common elements.  
Key elements used throughout include:

- **Conceptual structure elements:**  
  - `conbody`  
  - `section`  
  - `sectiondiv`  
  - `note`

- **List and inline elements:**  
  - `li`  
  - `ol`  
  - `ul`  
  - `codeph`  

- **Media elements:**  
  - `image`  

- **Tabular content:**  
  - `table`  
  - `tgroup`  
  - `thead`  
  - `tbody`  
  - `row`  
  - `entry`  

## Styling and CSS
For styling, a custom CSS file was created separately and applied manually to the generated HTML output.  
- A single, clean `custom.css` file was used.  
- Styling is intentionally minimal so readers can focus on the content rather than formatting.  
- File paths for CSS links were corrected manually in each topic’s HTML output after the initial GitHub Pages build failed due to invalid paths.

## GitHub and Publishing Notes
The project is hosted in this GitHub repository using the standard Git workflow:

```c#
{
git init
git add .
git commit -m "Initial commit"
git push -u origin main
}
```

## For GitHub Pages:
- The first deployment failed because of incorrect internal file paths in the `docs` folder.
- Paths were fixed manually in each generated topic and in `index.html`.
- After updating the paths, the site was successfully republished through GitHub Pages.
- Visit page here: https://nenas97.github.io/CCMS_Authorit_Learning/ 

## Final Thoughts
This repository exists for learners like me who struggled to find current resources and needed a clean, structured starting point. If you find this helpful or want to build your own Author-it practice project, feel free to fork or extend it.
