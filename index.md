## Exercise 1:
### Lesson 1:
Writing in Markdown is _not_ that hard!  
I **will** complete these lessons!  
"_Of course_," she whispered. Then, she shouted: "All I need is **a little moxie**!"  
If you're thinking to yourself, **_This is unbelievable_**, you'd probably be right.
### Lesson 2:
# Header one
## Header two
### Header three
#### Header four
##### Header five
###### Header six
#### Colombian Symbolism in _One Hundred Years of Solitude_

Here's some words about the book _One Hundred Years..._.
### Lesson 3:
[Search for it.](www.google.com)  
[You're **really, really** going to want to see this.](www.dailykitten.com)  
#### The Latest News from [the BBC](www.bbc.com/news)  
Do you want to [see something fun][]?

Well, do I have [the website for you][another fun place]!

[see something fun]: www.zombo.com
[another fun place]: www.stumbleupon.com
### Lesson 4:
![A pretty tiger](https://upload.wikimedia.org/wikipedia/commons/5/56/Tiger.50.jpg)  
![Black cat][Black]

![Orange cat][Orange]

[Black]: https://upload.wikimedia.org/wikipedia/commons/a/a3/81_INF_DIV_SSI.jpg
[Orange]: http://icons.iconarchive.com/icons/google/noto-emoji-animals-nature/256/22221-cat-icon.png
### Lesson 5:
I read this interesting quote the other day:

>"Her eyes had called him and his soul had leaped at the call. To live, to err, to fall, to triumph, to recreate life out of life!"  

>Once upon a time and a very good time it was there was a moocow coming down along the road and this moocow that was coming down along the road met a nicens little boy named baby tuckoo...

>His father told him that story: his father looked at him through a glass: he had a hairy face.

>He was baby tuckoo. The moocow came down the road where Betty Byrne lived: she sold lemon platt.

>He left her quickly, fearing that her intimacy might turn to jibing and wishing to be out of the way before she offered her ware to another, a tourist from England or a student of Trinity. Grafton Street, along which he walked, prolonged that moment of discouraged poverty. In the roadway at the head of the street a slab was set to the memory of Wolfe Tone and he remembered having been present with his father at its laying. He remembered with bitterness that scene of tawdry tribute. There were four French delegates in a brake and one, a plump smiling young man, held, wedged on a stick, a card on which were printed the words: _VIVE L'IRLANDE_!  
### Lesson 6
* Flour
* Cheese
* Tomatoes
1. Cut the cheese
2. Slice the tomatoes
3. Rub the tomatoes in flour
* Azalea (_Ericaceae Rhododendron_)
* Chrysanthemum (_Anthemideae Chrysanthemum_)
* Dahlia (_Coreopsideae Dahlia_)
* Calculus
  * A professor
  * Has no hair
  * Often wears green
* Castafiore
  * An opera singer
  * Has white hair
  * Is possibly mentally unwell

1. Cut the cheese  
Make sure that the cheese is cut into little triangles.

2. Slice the tomatoes  
Be careful when holding the knife.  
For more help on tomato slicing, see Thomas Jefferson's seminal essay _Tom Ate Those_.
### Lesson 7:
We pictured the meek mild creatures where  
They dwelt in their strawy pen,  
Nor did it occur to one of us there  
To doubt they were kneeling then.

1. Crack three eggs over a bowl.  
 Now, you're going to want to crack the eggs in such a way that you don't make a mess.  
 If you _do_ make a mess, use a towel to clean it up!

2. Pour a gallon of milk into the bowl.  
 Basically, take the same guidance as above: don't be messy, but if you are, clean it up!

## Exercise 2:
### Gencode
First introduced as **_generic coding_** by [William W. Tunnicliffe](https://en.wikipedia.org/wiki/William_W._Tunnicliffe) in 1967 during a conference at the _Canadian Goverment Printing Office_. The developement of Gencode as a standard for the publishing industry was led by Tunnicliffe in 1970s.
### Scribe
Scribe was designed and developed by Brian Reid in 1980. It was the first language to make a clean distinction between structure and presentation. Using Scribe would involve two phases;
* Typing a manuscript file using any text editor, conforming to the Scribe markup
* Processing this file through the Scribe compiler to generate an associated document file, which can be printed.

In a similar way to HTML, Scribe defined the words, lines, pages, spacing, footings, footnotes, numbering, tables of contents, etc.
In 1979 Reid sold Scribe to software company, Unilogic.
## Exercise 3
<iframe
width="640"
height="480"
src="https://www.youtube.com/watch?v=no1CHcGc64M&ab_channel=RobertEFuller"
frameborder="0"
allow="autoplay; encrypted-media"
allowfullscreen
>
</iframe>



[![Rat](https://external-preview.redd.it/FLLqCkbVjfABoi-kUIJ3l0tsqbrQN3pk0LuRiqbjtHA.jpg?auto=webp&s=bd37b6fdfbc8c8b974411111141ba1f18c332cde)](https://www.youtube.com/watch?v=no1CHcGc64M&ab_channel=RobertEFuller)

Wasnt clear if video was supposed to play straight from the file or if the picture was supposed to link to the video. From googling embedding video to markdown I found that you can embed youtube player with iframe if Markdown processor supports inline HTML. In addition to adding iframe (which most likely will not work) I made the picture to link to the video. :)
## Exercise 4
    public class Person{  
        private string name;  
        private int age;

        public Person(string initialName)  
        {  
            this.age = 0;  
            this.name = initialName;  
        }  
        public void PrintPerson()  
        {  
            Console.WriteLine(this.name + ", age " + this.age + " years");  
        }  
        public void GrowOlder()  
        {  
            this.age = this.age + 1;  
        }  
    }  