# Lab 10



## Part 1: Snack Tracker

Students are carrying snacks in their backpacks. Each line of an input file is an integer representing the number of calories in their snack. Blank lines separate students. Read in the file and find the largest total calories that a student is carrying. 

### Example 
`calories.txt`
```
1000
2000
3000

4000

5000
6000
```

Output
```
The maxiumum total is 11000.
```
### Program Input 
`calories.txt`
```
459
4398
2899
4342
3721
1291
2096
4913
1440
3553

3275
4182
1802
2317

3070
976
1492
1990
2038
3744
1164
434
635
3946
4278
2444

3830
4085
2067
1760
4621
2914
1223
2228
4652
967
3655
2485

2349
4495
2143
1649
4719
2922
2036

736
3660
2690
923
1746
3954
3814
3216

844
4168
4697
1660
4969
3218
158
143
845

4509
3838
2665
2862
2284
4232
1215
2519
1842
4936

1294
1650
2933
3125
3450
846
273
4945
1132
4887
2266

2480
3466
4581
4619

713
4831
3424
3449
372
967
755
884
3580

1983
1948
3586
228
4642
4305
932
3451

4293
4347
2393
962
3280

559
581
4020
231
3390

4875
1497
4927
2463
2994
1069
2172
3891
1869
```

---

## Part 2: Guard Shift Logs

A guard in front of the castle keeps falling asleep during shifts. The log records events in chronological order. Read in the file and determine which guard spends the most total minutes asleep.  

### Example 

Each line is a timestamped event, e.g.:
```
[1518-11-01 00:00] Guard #10 begins shift
[1518-11-01 00:05] falls asleep
[1518-11-01 00:25] wakes up
```

Output
```
Guard 10 was asleep the longest with 20 minutes total asleep.
```

## Program Input

`guardlogs.txt`
```
[1518-11-01 00:00] Guard #23 begins shift
[1518-11-01 00:55] falls asleep
[1518-11-01 01:04] wakes up
[1518-11-01 01:23] falls asleep
[1518-11-01 01:36] wakes up
[1518-11-02 00:00] Guard #56 begins shift
[1518-11-02 00:56] falls asleep
[1518-11-02 01:19] wakes up
[1518-11-02 01:36] falls asleep
[1518-11-02 01:46] wakes up
[1518-11-03 00:00] Guard #10 begins shift
[1518-11-03 00:47] falls asleep
[1518-11-03 01:14] wakes up
[1518-11-04 00:00] Guard #56 begins shift
[1518-11-04 00:39] falls asleep
[1518-11-04 00:56] wakes up
[1518-11-04 01:16] falls asleep
[1518-11-04 01:41] wakes up
[1518-11-04 01:58] falls asleep
[1518-11-04 02:11] wakes up
[1518-11-05 00:00] Guard #10 begins shift
[1518-11-05 00:48] falls asleep
[1518-11-05 00:53] wakes up
[1518-11-06 00:00] Guard #42 begins shift
[1518-11-06 00:51] falls asleep
[1518-11-06 01:03] wakes up
[1518-11-06 01:08] falls asleep
[1518-11-06 01:31] wakes up
[1518-11-07 00:00] Guard #10 begins shift
[1518-11-07 00:44] falls asleep
[1518-11-07 01:03] wakes up
[1518-11-07 01:09] falls asleep
[1518-11-07 01:32] wakes up
[1518-11-07 01:42] falls asleep
[1518-11-07 01:52] wakes up
[1518-11-08 00:00] Guard #23 begins shift
[1518-11-08 01:00] falls asleep
[1518-11-08 01:13] wakes up
[1518-11-09 00:00] Guard #23 begins shift
[1518-11-09 00:39] falls asleep
[1518-11-09 01:07] wakes up
[1518-11-09 01:20] falls asleep
[1518-11-09 01:37] wakes up
[1518-11-10 00:00] Guard #10 begins shift
[1518-11-10 00:53] falls asleep
[1518-11-10 01:07] wakes up
[1518-11-10 01:26] falls asleep
[1518-11-10 01:36] wakes up
[1518-11-11 00:00] Guard #23 begins shift
[1518-11-11 00:38] falls asleep
[1518-11-11 00:57] wakes up
[1518-11-11 01:05] falls asleep
[1518-11-11 01:27] wakes up
[1518-11-12 00:00] Guard #23 begins shift
[1518-11-12 00:44] falls asleep
[1518-11-12 00:50] wakes up
[1518-11-12 01:00] falls asleep
[1518-11-12 01:16] wakes up
[1518-11-12 01:21] falls asleep
[1518-11-12 01:45] wakes up
[1518-11-13 00:00] Guard #99 begins shift
[1518-11-13 00:40] falls asleep
[1518-11-13 01:06] wakes up
[1518-11-14 00:00] Guard #23 begins shift
[1518-11-14 00:50] falls asleep
[1518-11-14 01:20] wakes up
[1518-11-14 01:39] falls asleep
[1518-11-14 01:53] wakes up
[1518-11-15 00:00] Guard #23 begins shift
[1518-11-15 00:30] falls asleep
[1518-11-15 00:47] wakes up
[1518-11-15 00:54] falls asleep
[1518-11-15 01:16] wakes up
[1518-11-16 00:00] Guard #23 begins shift
[1518-11-16 00:37] falls asleep
[1518-11-16 00:58] wakes up
[1518-11-17 00:00] Guard #99 begins shift
[1518-11-17 00:31] falls asleep
[1518-11-17 01:00] wakes up
[1518-11-18 00:00] Guard #42 begins shift
[1518-11-18 00:58] falls asleep
[1518-11-18 01:24] wakes up
[1518-11-18 01:33] falls asleep
[1518-11-18 01:49] wakes up
[1518-11-19 00:00] Guard #10 begins shift
[1518-11-19 00:44] falls asleep
[1518-11-19 01:01] wakes up
[1518-11-19 01:16] falls asleep
[1518-11-19 01:44] wakes up
[1518-11-20 00:00] Guard #23 begins shift
[1518-11-20 01:00] falls asleep
[1518-11-20 01:26] wakes up
[1518-11-20 01:40] falls asleep
[1518-11-20 01:51] wakes up
[1518-11-20 02:02] falls asleep
[1518-11-20 02:29] wakes up
[1518-11-21 00:00] Guard #10 begins shift
[1518-11-21 00:46] falls asleep
[1518-11-21 01:15] wakes up
[1518-11-21 01:32] falls asleep
[1518-11-21 01:45] wakes up
[1518-11-21 01:58] falls asleep
[1518-11-21 02:06] wakes up
[1518-11-22 00:00] Guard #99 begins shift
[1518-11-22 00:36] falls asleep
[1518-11-22 00:55] wakes up
[1518-11-23 00:00] Guard #56 begins shift
[1518-11-23 00:42] falls asleep
[1518-11-23 01:09] wakes up
[1518-11-23 01:19] falls asleep
[1518-11-23 01:34] wakes up
[1518-11-23 01:53] falls asleep
[1518-11-23 02:02] wakes up
[1518-11-24 00:00] Guard #99 begins shift
[1518-11-24 00:32] falls asleep
[1518-11-24 00:55] wakes up
[1518-11-25 00:00] Guard #56 begins shift
[1518-11-25 00:38] falls asleep
[1518-11-25 00:58] wakes up
[1518-11-26 00:00] Guard #23 begins shift
[1518-11-26 00:41] falls asleep
[1518-11-26 00:50] wakes up
[1518-11-26 01:09] falls asleep
[1518-11-26 01:21] wakes up
[1518-11-26 01:32] falls asleep
[1518-11-26 02:00] wakes up
```

## Part 3: Wordle

Design a program to play Wordle in the terminal. You must use at least **two classes**. 
## Example

```
Welcome to Wordle!

In this game you will guess a secret 5 letter word. Each turn you will guess a 5 letter word and I will tell you if a letter is correct and in the correct location with a "*", if a letter is correct but in the wrong location with a "!", and if a letter is incorrect with a "?". 

Guess the secret word: _ _ _ _ _
Your guess: magic 
_ * _ _ !

Guess the secret word: _ A _ _ _
Your guess: caret
* * _ _ _
  
...
```


`words.txt`

```
apple
grape
table
chair
plant
brick
light
sound
sweet
bread
stone
flame
water
earth
metal
glass
sword
scale
cloud
storm
smile
laugh
dream
magic
spice
sugar
honey
wheat
sheep
zebra
tiger
eagle
shark
whale
otter
camel
lemur
rhino
panda
koala
peace
trust
faith
honor
pride
glory
unity
brave
smart
quick
candy
lemon
mango
peach
berry
melon
onion
chili
spoon
knife
plate
bowl
couch
stool
sofa
shelf
clock
radio
piano
drums
viola
flute
harps
cello
organ
banjo
trump
gongs
bells
ocean
river
creek
brook
beach
shore
coast
dunes
grass
woods
field
desks
books
notes
paper
penal
ruler
chalk
board
class
teach
learn
study
tests
quizs
marks
grade
score
point
award
medal
crown
spear
arrow
armor
boots
cloak
rings
gems
mines
oreos
steel
copper
brass
alums
fiber
leath
wools
white
black
green
brown
beige
ivory
amber
blues
pearl
coral
smoke
dusty
foggy
clear
sunny
rainy
frost
winds
north
south
eastn
wests
upper
lower
inner
outer
front
backs
happy
sadly
angry
scary
crazy
funny
silly
sleep
awake
tired
brisk
haste
swift
slows
crawl
jumps
hopes
walks
rides
drives
train
plane
truck
carve
boats
ships
canoe
ferry
metro
cabin
house
tower
villa
lodge
hutsy
barns
rooms
doors
gates
fence
```
