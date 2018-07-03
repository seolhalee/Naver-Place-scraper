# Naver-Place-scraper
This is for web scraping of the search result in Naver Place service

1) coord_converter: it converts the coordinates of grid points from UTM-K to WGS84 system (which is the coordinate system that Naver Map uses). The result of conversion is saved as a csv file.  

2) web_scraper: this will extract the list of ID of the searched places on Naver Place for each boxes using url queries. The result of scraping is saved as a json file.

3) correlation: this is for calculating the number of overlapped items and correlation coef.(Spearman's) between a default list of items and each age group's list. The result of calculation is saved as a csv file. 
