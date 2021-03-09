# Fashion Colors Prediction

Letty Wu

## Problem Statement

The United States apparel market was valued at approximately 368 billion US dollars as of 2019. Top clothing companies lead the global fashion industry, fast fashion and smaller brands usually follow the style and color trends from those high-end brands, and they use data to predict the rise and fall of trends. Fashion show is one of the way leading brand showcase their new products, therefore fashion show pictures is a good way to predict the upcoming trends. 

## Data Collection

Vogue is an American monthly fashion and lifestyle magazine covering many topics, including fashion, beauty, culture, living and runway. Vogue Runway has up-to the minute fashion show coverage at New York, London, Milan and Paris Fashion Weeks, including photos, videos, reviews. Many Fashion houses used to create eight collections a year. The new shift in fashion is to two collections a year: spring/summer and fall/winter. The simplified approach puts customers at the center by creating pieces when people will actually be shopping for them.

So I scraped my image data from Vogue runway, 50 leading brands with fall and spring season in 2021, I ended up collected around 2,000 fashion show pictures. While scraping, I annotated the file name with brand name, year, season and picture id for each image.

## Preprocessing

First, I used YOLO v5 to conduct the object detection. YOLO v5 is a family of compound-scaled object detection models trained on the COCO dataset. YOLO stands for *you only look once*,  it’s a convolutional networks. YOLO originally come out around 2016 and YOLO v5 come out in July 2020, it’s know for its speed and easy to use. 
<p align = 'center'>
    <img src="./plots/chanel_2019_fall_71.jpg"/>

















