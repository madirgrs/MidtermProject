# Majoring in IT
IT was not what I originally planned on doing at all until last semester. Throughout high school as well as the beginning of last semester, I planned on majoring in Art and focusing on graphic design. It wasn't until I really struggled with the idea of being stuck with only one form of media. I really enjoyed audio production, video editing, and special effects and I feel like I would've lost all that with just graphic design. IT however was a clear choice for me and provided me with everything I was looking for!

## Coding
Before starting this major I had never done any code before. I have learned a lot already so here are some examples of different code I've done so far.

### List Loops Python
```python
#total of numbers
list = ["6","5","3","8","4","2","5","4","11","43","1","17","27","90","77","62","51","47","82","86","20"]

number_of_elements = len(list)
print("How many numbers are in this list:", number_of_elements)


#sum
numbers = [6, 5, 3, 8, 4, 2, 5, 4, 11, 43, 1, 17, 27, 90, 77, 62, 51, 47, 82, 86, 20]

sum = 0

for value in numbers:
 sum = sum + value

print("The sum of these numbers is",sum)


#average
list = ["6","5","3","8","4","2","5","4","11","43","1","17","27","90","77","62","51","47","82","86","20"]

average = sum / len(list)

for value in numbers:
 sum = sum + value

print("The average of these numbers is", average)


#print all numbers in list
print()
print("Printing all list items:")

list = ["6","5","3","8","4","2","5","4","11","43","1","17","27","90","77","62","51","47","82","86","20"]
x = 0
while x < len(list):
 print("Item", x, "is -", list[x])
 x = x + 1
 

#print every other number in list
print()
print("Printing every other list item:")


list = ["6","5","3","8","4","2","5","4","11","43","1","17","27","90","77","62","51","47","82","86","20"]

x = 0
for index, element in enumerate(list):
 if index % 2 == 0:
  print("Item", x, "is -", element)
  x = x + 2
  
#bonus even and odd
print()
print("Bonus: Printing even numbered values from the list:")

list = [6, 5, 3, 8, 4, 2, 5, 4, 11, 43, 1, 17, 27, 90, 77, 62, 51, 47, 82, 86, 20]

i = 0

while i < len(list):
 if(list[i] % 2 == 0):
  print("Item", i, "is even -", list[i])
 else:
  print("Item", i, "is odd -", list[i])
 i = i + 1 
```

### Intro to HTML - Codecademy
```html
<body>
  <h1>The Brown Bear</h1>
  <div id="introduction">
    <h2>About Brown Bears</h2>
    <p>The brown bear (<em>Ursus arctos</em>) is native to parts of northern Eurasia and North America. Its conservation status is currently <strong>Least Concern</strong>.<br /><br /> There are many subspecies within the brown bear species, including the Atlas bear and the Himalayan brown bear.</p>
    <h3>Species</h3>
    <ul>
      <li>Arctos</li>
      <li>Collarus</li>
      <li>Horribilis</li>
      <li>Nelsoni (extinct)</li>
    </ul>
    <h3>Features</h3>
    <p>Brown bears are not always completely brown. Some can be reddish or yellowish. They have very large, curved claws and huge paws. Male brown bears are often 30% larger than female brown bears. They can range from 5 feet to 9 feet from head to toe.</p>
  </div>
  <div id="habitat">
    <h2>Habitat</h2>
    <h3>Countries with Large Brown Bear Populations</h3>
    <ol>
      <li>Russia</li>
      <li>United States</li>
      <li>Canada</li>
    </ol>
    <h3>Countries with Small Brown Bear Populations</h3>
    <p>Some countries with smaller brown bear populations include Armenia, Belarus, Bulgaria, China, Finland, France, Greece, India, Japan, Nepal, Poland, Romania, Slovenia, Turkmenistan, and Uzbekistan.</p>
  </div>
  <div id="media">
    <h2>Media</h2>
    <img src="https://content.codecademy.com/courses/web-101/web101-image_brownbear.jpg" alt="A Brown Bear"/>
    <video src="https://content.codecademy.com/courses/freelance-1/unit-1/lesson-2/htmlcss1-vid_brown-bear.mp4" width="320" height="240" controls>
      Video Not Supported
    </video>
  </div>
</body>
```
