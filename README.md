# bookToScrape
## Data Extration:

### Objective:

The objective of this web scraping project is to gather a diverse dataset of images from an online source (www.books.toscrape.com) for creating a custom image dataset.

### Project Idea: 
Web Scraping Images for learning purpose from a website that permits image scraping.

### Description:

Create a Python script to scrape images from website, collecting a variety of images to build a dataset for image-related analysis. 
This project can be tailored for specific purposes, such as training a machine learning model to classify different image genres, creating a 
portfolio of images for a website, or analyzing trends in photography styles.

## Key Steps:

### Identify the Website:

I choose a website that allows scraping for educational or non-commercial purposes. Ensuring compliance with the website's terms of service.

### Inspect the Website Structure:

Analyzing the HTML structure of the website to identify the tags and attributes containing image URLs was accessed. Tools like chrome devTools or firefox 
developer tools can assist in inspecting web elements. However, chrome devtool was accessible to me

### Python Libraries:

Utilize the requests, BeautifulSoup and os library to make HTTP requests to the website, BeautifulSoup library for HTML parsing and os to manage downloaded files.

### Scrape Image URLs:

Extract image URLs from the website's HTML. Depending on the website, this may involve navigating through multiple pages or categories.

### Download Images:

Use the extracted image URLs to download images. Ensuring proper handling of image formats (JPEG, PNG, etc.) and resolution.

### Project Applications:

The collected dataset can be used for various purposes:
Machine Learning Classification: Train a model to classify images into different photography genres (e.g., landscape, portrait, macro).
Portfolio Generation: Create a personalized portfolio by scraping images relevant to your photography style or interests.
Trend Analysis: Analyze trends in photography styles, colors, or subject matters.

### Ethical Considerations:

Ensure that the scraping activities align with the website's terms of service. Be respectful of copyright and usage policies.
