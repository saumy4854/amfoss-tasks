# Task - 02 **Begin your journey with Linux and Git**

This task was easy and a li'l bit tough at the same time because i was new to linux and was searching for commands, but after knowing commands it became very easy:

~~~
cd Desktop
mkdir Coordinates-Location
~~~

For North Coordinate : 

~~~
cd Coordinates-Location
> NDegree.txt
echo "9°" > NDegree.txt
> NMinutes.txt
echo "5'" > NMinutes.txt
> NSeconds.txt
echo "38.1''" > NSeconds.txt
cat NDegree.txt NMinutes.txt NSeconds.txt > NorthCoordinate.txt
mv NorthCoordinate.txt North.txt
~~~

For East Coordinate :

~~~
cd Coordinates-Location
> EDegree.txt
echo "76°" > EDegree.txt
> EMinutes.txt
echo "29'" > EMinutes.txt
> ESeconds.txt
echo "30.8''" > ESeconds.txt
cat EDegree.txt EMinutes.txt ESeconds.txt > EastCoordinate.txt
mv EastCoordinate.txt East.txt
~~~

Collecting all the coordinates :

~~~
cd Coordinates-Location
cat ./North/North.txt ./East/East.txt > Location-Coordinate.txt
~~~
Finally i got these as coordinates - 
9° 5' 38.1'' N 76° 29' 30.8'' E
