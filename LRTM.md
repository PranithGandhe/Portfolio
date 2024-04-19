# LIP READING TECH FOR MUTE

Lip reading is the most effective way of visual “listening” to somebody speaking. We humans tend to visually try to understand when someone is speaking in a noisy environment. Our brain processes everything with the help of neurons and it looks easy. But when it comes to technology, it is not that easy to read the lips of the person.

In our project, the surface area of the lip is taken as the key element or the key feature of the lip movement. The horizontal distance and the vertical distance of the lips are used to calculate the surface area. This surface area is then used to estimate some parameters and store them in the database. Based on the results, the accuracy we obtain is more than 85%. Therefore, our project is more effective and more efficient than other traditional projects out there.


#### Proposed System
- Our proposed system first localizes the position of the lips. It then extracts the point available on our lips with the help of the dlib package. 
- This package contains a matrix which is used to convert the position of the lips to some points. 
- Based on these points, the surface area is calculated. 
- This surface area is the key element of the pattern extraction.
- Based on this area value, the commands are given.

#### Advantages
- A mute person can drive an autonomous vehicle without uttering a word.
- The mute person need not move their lips to pronounce a particular word but instead, he/she can just move their lips so that they form an area to calculate.
- Does not need any translator for future enhancements.


<b>Output for “Go Straight” Command</b>
If the surface area value is more than 16, then go straight is displayed and said.


![GoStraight](assets/img/gostraight.png)

<b>Output for “Take a right” Command</b>
If the surface area value is 14 or nearby, then take a right is displayed and said.


![TakeARight](assets/img/takearight.png)

<b>Output for “Take a left” Command</b>
If the surface area value is 9 or nearby, then take a left is displayed and said.


![TakeALeft](assets/img/takealeft.png)

<b>Output for “Hit the breaks” Command</b>
If the surface area value is 5 or nearby, then hit the breaks is displayed and said.


![hitthebreaks](assets/img/hitthebreaks.png)

