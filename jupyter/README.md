This file itself is a markdown file.
The markdown syntaxes in this folder comes from [this website](https://guides.github.com/features/mastering-markdown/)

bold: **bold** <br />
italic: *italic*
italic2 _italic2_
emphasis __emphasis__
--------------------

We have `6` different sizes of headings:
# This is a <h1> tag
## This is a <h2> tag
### This is a <h3> tag
#### This is a <h4> tag
##### This is a <h5> tag
###### This is a <h6> tag
Or if you want to input `#`

For quoting, it goes like this:
> Every day I remind myself that my inner and outer life are based on the labors of other men, living and dead, and that I must exert myself in order to give in the same measure as I have received and am still receiving.
> -- Albert Einstein

Let's make some lists:

Enumerate people in my lounge and their features:
1. Joe
  * music
    * guitar
    * piano
  * sports
    * iceskating
      * ice hockey
      * ref 
        * `this is just a test`
2. Johnny
3. Quint
4. Yun
  * music
    * piano
    * violin
5. Anthony
6. David
7. Kevin

Today's Christmas, let's insert a portrait of mine:
<p align="center">
<img src="./pic/christmas.jpg" width="200"/>
</p>

Inline code: `int i = 1;` . Or indent with four space:  

    if (i == 0)
    {
      printf("%d",i);
    }

Or code fencing (wothout indentation):

```
int i = 1;
float j = 1.0;
double k = 3.1415926;
double f = i+j+k;
```

We can even use syntax highlighting! This is cool:

```C++
class People()
{
public:
void study(int hour);
void eat(food f);
void merry(people p);

private:
struct sex;
int age;
float height;
float weight;
}
```

We can also @ somebody, like @MFarejowicz, @AngelAlvie

Tasks lists:

* [x] learn to make pancake
* [ ] cook one kind of meat

And Emoji!! :joy: :sparkles: :camel: :boom:
Check out Emoji Cheat sheet [here](https://www.webpagefx.com/tools/emoji-cheat-sheet/).

Tables！

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column
