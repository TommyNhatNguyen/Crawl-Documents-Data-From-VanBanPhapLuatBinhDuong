# Crawl data from Văn bản Chỉ đạo Điều hành tỉnh Bình Dương

![image](https://github.com/TommyNhatNguyen/Crawl-Documents-Data-From-VanBanPhapLuatBinhDuong/assets/86128966/bad77291-8f9b-4c25-ae92-8a52a085ed1d)

Crawl document's pdf links, issued date, title, ... to sort items more easily than using sorting tool on website. 

**Source code:** ![My code file](https://github.com/TommyNhatNguyen/Crawl-Documents-Data-From-VanBanPhapLuatBinhDuong/blob/main/Crawl_data_from_vanbanphapluatBinhDuong.ipynb)

### 1. Problems:
- I need to find information about “transfer of land use rights”. However, webpage was too slow for me to search information and the search bar didn't function well. Webpage:

![image](https://github.com/TommyNhatNguyen/Crawl-Documents-Data-From-VanBanPhapLuatBinhDuong/assets/86128966/4a5c4e57-a096-4563-a411-111673c66788)
### 2. Solutions:
- I use **Selenium** to crawl data from ![this web page](https://www.binhduong.gov.vn/chinh-quyen/van-ban-chi-dao-dieu-hanh). Finally, I find the information I want by quickly search values in "trich_yeu" column. Data after crawl: 
![image](https://github.com/TommyNhatNguyen/Crawl-Documents-Data-From-VanBanPhapLuatBinhDuong/assets/86128966/bb70968b-c2f8-41a7-9329-b44ae65c2c74)
