# Beijing-THU-blog
2019 兩岸清華暑期交流------平行程式與當地旅遊
為了記錄到北京清華交流，另外也想練習一下最近學的html/css 而架設的部落格
第一次網頁架設經驗。
## Probelm Solving
### Image Wrong Orientation
Photos  appear correctly on the computer but appear in the wrong rotation when you upload them to a website.
The reason is the photos were from another phone, if he or she rotates on his or her phone, 
it seems to be on correct side, but actually it isn't.
#### Solving:
```
jhead file.jpg
```
There maybe a line --- Orientation: 90 degree
```
jhead -norot file.jpg
```
此時照片就會顯示原本的樣子，再用小畫家等等轉正就完成了
### Responsive Website 
In bootstrap's grid system, I should use 
```
<img src="images/file.jpg" "class="col col-md-6">
```
or
```
<p class="col col-md-6">
```
for small screen users
### Git
When I new a repository for the github page, I pull the remote from the local in order to push it
but there is an error saying " refusing to merge unrelated histories ". 
#### Solving
```
git pull --allow-unrelated-histories
```

