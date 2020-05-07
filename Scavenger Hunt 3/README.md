# Scavenger Hunt 3 - write up

Hello and welcome to yet another write up :)

**Tools Used:**

dCode online decoding tool

PimEyes online face recognition tool

<hr>

**Lets Begin!**

We are given the following link, which is reversed: https://pastebin.com/khGCq7XY
and we are then redirected to a page with the following text:

>..... ..... ..... ..... !?!!. ?.... ..... ..... ..... .?.?! .?... .....
!.?.. ..... !?!!. ?.... ..?.? !.?.. ....! .!.!! !!!!! !!.?. ..... .....
....! ?!!.? !!!!! !!!!! !!!!? .?!.? !!!!! !!!!! !.?.. ..... !?!!. ?!!!!
!!?.? !.?!! !!!.! .?... ..... ..... ....! ?!!.? ..... ..... ..... .?.?!
.?... ..... ..... ...!. !.!.? ..... ..... ..... ..!?! !.?!! !!!!! !!!!!
!!!!? .?!.? !!!!! !!!!! !!!!! !!!!. ?.... ..... ..... .!?!! .?... .....
..... .?.?! .?... ..... ....! .?... ....! ?!!.? ..... .?.?! .?... .!...
..... ...!. ..... ..... !.!.? ..... ..!?! !.?!! !!!!? .?!.? !!!!! !!!!!
!.!!! !!!!! !!!!! !!.?. ..... ..... ....! ?!!.? !!!!! !!!!! !!!!? .?!.?
!!!!! !!!!! !!!.? ..... ..... ..... !?!!. ?.... ..... ..... ?.?!. ?....
..... ..... ..... .!... ..... ...!. !!!!! !!!!! !!!!! !!... ..... .....
..... .!.?. ..... ..... ..... .!?!! .?!!! !!!!! !!!!! !!!?. ?!.?! .?...
..... ..... ....! ?!!.? ..... ..... ..... .?.?! .?..! ..... ..... .!...
..... ...!. !.?.. ..... !?!!. ?!!!! !!?.? !.?!! !!!!! !!!!. !!!!! !!!!!
!!!!! ..... !.?.. ..... !?!!. ?.... ..?.? !.?.. ..!.? ..... ....! ?!!.?
!!!!! !!!?. ?!.?! !!... ..... ..... ..... .!.?. ..... ..... ....! ?!!.?
!!!!! !!!!! !!!!? .?!.? !!!!! !!!!. !!!!! !!!!! !!!!! .?... ..... .....
....! ?!!.? ..... ..... ..... .?.?! .?... .!.!! !!!!! !!!!! !!!!! .....
..... ..... ..!.? ..... ..... ..... !?!!. ?!!!! !!!!! !!!!! ?.?!. ?!.?.
..... ..... ....! ?!!.? ..... ..... ....? .?!.? !.... .!.?. ..... .!?!!
.?!!! !!!?. ?!.?! !!!!! !!!.. .!.?. ..... .!?!! .?... ...?. ?!.?. .....
..!.? ..... ..... ..... !?!!. ?!!!! !!!!! !!!!! ?.?!. ?!!!! !!!!! !!.?.
..... .!?!! .?!!! !!!?. ?!.?! !!.?. ..... .!?!! .?!!! !!!?. ?!.?! !!!!!
!!!.? ..... ..... ..... ..!?! !.?.. ..... ..... ....? .?!.? ..... .....
..... ...!. ?.... ...!? !!.?! !!!!! ?.?!. ?!!!! !!!!! .?... ..... .!?!!
.?... ..... ?.?!. ?!.?. ..... ...!? !!.?! !!!!! !!?.? !.?!! !.?.. .....
....! ?!!.? ..... ..... ?.?!. ?!.?. ..... ...!? !!.?! !!!!! !!?.? !.?!!
!!!!! !!!!. ..... ..... ..!.? ..... ..... ...!? !!.?! !!!!! !!!!! !?.?!
.?!!! !!!!! !!!!! !!!!! !!!.? ..... ..!?! !.?!! !!!!? .?!.? !!!!! .!!!.
..... .!... ....! .!!!! !!!!! !!!!. ....! .?... ....! ?!!.? !!!!! !?.?!
.?!!! !!!!! !.?.. ..... ..... ..... !?!!. ?.... ..... ..... ..?.? !.?..
..... ..... ..... ..... ....! ..... ..... ..... !.?.. ..... ..!?! !.?!!
!!!!! !?.?! .?!!! !!!!! !!!.? ..... ..!?! !.?.. ....? .?!.? ..... ...!.
?.... ..... ..... .!?!! .?!!! !!!!! !!!!! !?.?! .?!!! !!!!! !.!!! !!!!!
!.!!! !!!!! !!!!! ..... ..!.? ..... ....! ?!!.? !!!!! !!!?. ?!.?! .?...
..... ..... ..... .!?!! .?... ..... ..... ..... ?.?!. ?!... ..!.! !!!!!
!!!!! !!.?. ..... ..... ....! ?!!.? !!!!! !!!!! !!!!? .?!.? !!!!! !!!!!
!.!!! !!!!! !!!!! !!!!. !!!!! !!... ....! .?.

From the encoding we understand it is a case of *esoteric programming* encoding.
Thus, if we search for:
>esoteric programming dots question mark

We will be given the option of **Ook! Programming Language**.

Thus, if we decode the text (tool: https://www.dcode.fr/ook-language), we will be given the following link (patience, it takes some time..):
http://www.epuzzle.info/puzzlegraj5.php?prefs=3&obrazek=214713&szer=936&wys=525

If we follow the link and play the puzzle, we will be given the following puzzle:
<center><img src = "https://github.com/John-Athanasopoulos/CTFLearn-Write-ups/blob/master/Scavenger%20Hunt%203/Pictures/cipher.png"></center>

This puzzle is actually pretty hard, especially if you don't see the number of correct tiles you have (like me..).
After some time though you will solve the puzzle and get the following picture:

<center><img src = "https://github.com/John-Athanasopoulos/CTFLearn-Write-ups/blob/master/Scavenger%20Hunt%203/Pictures/plain.png"></center>

So, the link given to us is:
https://goo.gl/4fEuSJ

This link leads to a text file, that we can see is ascii art, and actually a picture of a woman.
Right now, the only thing left is to find this person. We can use a facial recognition online app,
like https://pimeyes.com

Through the text we can't find anything, however you can screenshot the text and use the picture
as input for the facial recognition. Beware, though, as the screenshot needs to be zoomed out, so that the face is recognised.
Personally, I used the following screenshot:

<center><img src = "https://github.com/John-Athanasopoulos/CTFLearn-Write-ups/blob/master/Scavenger%20Hunt%203/Pictures/face.png"></center>

We get multiple results, among which there is the following picture.

<center><img src = "https://github.com/John-Athanasopoulos/CTFLearn-Write-ups/blob/master/Scavenger%20Hunt%203/Pictures/flag.png"></center>

So, the person (and our flag) is Grace Hopper!

-------------------
FLAG: grace hopper
-------------------

