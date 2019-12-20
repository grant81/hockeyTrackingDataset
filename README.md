## hockeyTrackingDataset
**steps to contribute to this DB**
1. clone this repo
2. get the annotation tool CVAT from [here](https://github.com/opencv/cvat)
3. go to the cvat directory by 
```
cd pathtoCvat/cvat
```
4. run cvat by running 
```
docker-compose up
```
5. go to cvat interface in this url [localhost:8080](localhost:8080)
6. label one video
\t 6.1 where to get 720p 60fps videos?
https://nhl66.ir/dl
youtube.com
7. download the labels from CVAT by clicking dump annotations and select CVAT xml 1.1 for videos
8. put the annotation file into the correct directory
9. run the following to push to git
```
git add .
git commit -m'I labeled what'
git push
```
10. repeat
   
