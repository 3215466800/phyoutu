#  pornhub spider


## 用法简介

- ```本项目适用于py3```
- ```git clone https://github.com/killmymates/Pornhub ```
- ```cd Pornhub && pip install -r requirements.txt```
- ```python crawler.py webm```
- 待程序运行完毕， 会在webm文件夹下download两页的webm缩略图，对应名称为详细页面的URL后缀
- 把后缀放到download.txt里，运行```python crawler.py mp4```, 在MP4文件夹可看到下载好的MP4文件

因为原来的方法失效了，所有用了新的youtube_dl 虽然慢一点，但是可以用了

导出list的话，windows会比较麻烦，可以先一个脚本或者也可以一键

dir /s/b *.* > list.txt 
就会去除所有格式，然后复制到download里面就可以了

如果是linux，就直接 ls就可以了

现在下载速度只有100多k，具体原因不太清楚，如果需要下载某一个分类，最好的办法是，在py文件里，直接讲所有的文件都写进去，这样，就可以获取所有视频的地址了。






