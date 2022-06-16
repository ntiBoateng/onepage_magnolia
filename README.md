# onepaper-light-module
## Assignment: Single-page website

Now that you have completed the course, it is time to apply what you have learned by completing this assignment

## Goal
The goal is to be able to reproduce this single-page website:
![Image for Assignment](/images/1585725466_shutterbugs-assignment-goal.png)
## Task
Your task is to create a Magnolia light module based on the provided prototype.
To get you started we provide you with correct page definition:
```
title: FE One-Pager
templateScript: /onepager-light-module/templates/pages/onepager.ftl
renderType: freemarker
dialog: onepager-light-module:pages/onepager
visible: true
areas:
  main:
    availableComponents:
      section:
        id: onepager-light-module:components/section
      banner:
        id: onepager-light-module:components/banner
  footer:
    availableComponents:
      mtkTextImage:
        id: mtk:components/textImage
    templateScript: /onepager-light-module/templates/pages/areas/footerArea.ftl
    maxComponents: 3
```

## Information on Magnolia CMS

This directory is a Magnolia 'light module'.
https://docs.magnolia-cms.com


## License


## Contributors
