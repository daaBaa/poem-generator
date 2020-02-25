# poem-generator
Generates rhyming poetry using Huggingface GPT-2

requires torch, transformers, pickle, and copy

To get started quickly, replace the line 

model = GPT2LMHeadModel.from_pretrained("poetry")

with

model = GPT2LMHeadModel.from_pretrained("gpt2")

If you use Gwern's finetuned poetry GPT-2 model, the results are better, though.

-----------------------------------------------------------

Here is an example of a poem generated by this program:

 For the earth looks barren; while,
 
A breath, a moment, and awhile,

My heart is the rich soil where those,

The fair ones, grow; while rose,

In the close, transparent green of these

Dimpled and gleaming hills -- sees,

Shines through her forest, in each

Nook and corner, most mysterious reach,

In her deep caves and shady valley,

Her bright emerald stream and rally,

So rich, so radiant and so young.

Yet I know well, for her tongue,

When she speaks, holds all secret truth.

When she speaks, as all things youth,

Mingled with age, can make,

A glory spreads through her words -- take,

Take heed! -- her word to this,

My love for thee is so complete bliss,

As heaven is to the soul; full,

Then, fear! these feet shall pull.

---------------------------------------

Another example:

 Many warriors died attempting to cross this,
 
The first two realms are the Garden abyss,

The Underworld, which is where mortals never,

The World Tree or Yggdr however,

The World's Heart, where the other,

Folk lived and slept and were mother.

All things have five faces. The first,

I can see, the Garden is worst,

The Underworld or the Underworld, this part,

My friend, is not the worst heart,

But the world's heart of the life;

Or life and death and heart and wife.
