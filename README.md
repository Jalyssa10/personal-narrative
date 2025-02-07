# Unit 4 - Personal Narrative

## Introduction

Images are often used to portray our personal experiences and interests. We also use image filters and effects to change or enhance the mood of an image. When combined into collages and presentations, these images tell a story about who we are and what is important to us. Your goal is to create a personal narrative using The Theater that consists of images of your personal experiences and/or interests, incorporates data related to these experiences and/or interests that can be organized in a 2D array, and uses image filters and effects to change or enhance the mood of your images.

## Requirements

Use your knowledge of object-oriented programming, two-dimensional (2D) arrays, and algorithms to create your personal narrative collage or animation:

- **Create at least two 2D arrays** – Create at least two 2D arrays to store the data that will make up your visualization.
- **Implement one or more algorithms** – Implement one or more algorithms that use loops and two-way or multi-selection statements with compound Boolean expressions to analyze the data.
- **Use Image Filters** - Include multiple image filters learned from this unit, and additionally create new ones of your own.
- **Use methods in the String class** – Use one or more methods in the String class in your program, such as to determine whether the name of an image file contains specific characters.
- **Create a visualization** – Create an image or animation that conveys the story of the data by illustrating the patterns or relationships in the data.
- **Document your code** – Use comments to explain the purpose of the methods and code segments and note any preconditions and postconditions.

## UML Diagram

Put and image of your UML Diagram here. Upload the image of your UML Diagram to your repository, then use the Markdown syntax to insert your image here. Make sure your image file name is one work, otherwise it might not properly get display on this README.

![UML Diagram for my project](https://github.com/user-attachments/assets/dc14b4c5-37d2-47a0-ba2d-a648260325e0)

## Video

Record a short video of your story to display here on your README. You can do this by:

- Screen record your project running on Code.org.
- Upload that recording to YouTube.
- Take a thumbnail for your image.
- Upload the thumbnail image to your repo.
- Use the following markdown

[![Thumbnail for my project](https://github.com/user-attachments/assets/b4f7f927-de37-4ca9-b56a-79ae12a6d6c2)](https://youtube.com/shorts/_zDgyFU--c0)

## Story Description

My project is about what makes me, me. I first stary off with the Mexican flag and I overlay a thermal filter on top of it. For the second image I have a cross because I'm Catholic and my religion is a big part of my life and I have a color shift flter on top. The third image is Yogurtland's logo because I LOVE Yogurtland and I want to eat it everyday so I used a shapen filter. Lastly my fourth image is a group of people running Cross Country because that's the sport that I've been doing and I really enjoying competing and I overlayed a motion blurred filter. In one of my 2D array I have all of my png's in order of what I wanted to go from first to last, I also have private String, private ImagePlus, private Pixel, public Pizel, and Pixel.
## Image Filter Analysis

Color Shift Filter: 

In this filter the applycolorShift method loops through every pixel in an image. Each pixel increases the red color value by 30, that way it doesn't pass 255. This modifies the color of the image by shifting the red tones in all the pixels.

Thermal Filter:

The applyThermalFilter method adjusts the colors of each pixel by increasing the red value, while decreasing the green and blue values, to make a warmer image. The adjustContrast method changes the brightness of each color (red, green, and blue) in the pixel by multiplying their values by a factor "m", then limits the values to a max of 255.
