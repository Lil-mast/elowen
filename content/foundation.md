---
title: "Foundation"
date: 2026-11-09
tags:
  - reflection
  - tech
  - garden
  - concept/ownership
draft: false
---

*(Or: What a Rust Binary Taught Me About Building to Last)*

**Nobody photographs a foundation.**

No one stands in front of a finished building and admires the
concrete poured months earlier, now buried under floors and walls and
paint. The part that carries everything is the part no one will ever
see. It is dug in the dust, in the heat, in the unglamorous weeks
before anything impressive exists. And it is precisely there, in the
work no one applauds, that the verdict on the whole structure is
already being written.

I learned this the expensive way. Two years ago I built something in
Rust. It was slow going. The compiler argued with me about things I
was certain were fine, rejected my code line after line, and made me
justify every borrowed reference and every scrap of memory I touched.
I remember resenting it. Months later, I remember being grateful.
That program still runs today, untouched, unbothered, as if the
two years were a single afternoon.

Then there was the app I built quickly in another stack. It came
together fast, it looked impressive, and it lasted two months. Two
months, and then the cracks arrived: a memory leak here, a fragile
dependency there, a bug that only showed itself under real load. It
had been built to be admired on the first day, not to survive the
hundredth.

That contrast has been following me around ever since, because it is
not really about programming languages.

Rust asks you to do the hidden work first. Before it lets anything
ship, it forces you to answer the hard questions: who owns this
value, how long does it live, who is allowed to change it and when.
There is a name for that idea, ownership, and its quiet genius is
independence. Every piece of data has exactly one responsible owner.
Nothing depends on a garbage collector sweeping up behind it later,
nothing leans on someone else to clean up its mess. It answers for
itself. It stands on what it was built from, not on what might
rescue it.

Fast, secure, strong. People describe Rust that way, and they are
right, but I have come to believe those qualities are not features
bolted on at the end. They are the fruit of the unseen discipline at
the beginning. Strength is never added afterward. It is poured in
early, in the dark, where no one is clapping.

And storms come. They always come, in code and in life. A traffic
spike nobody planned for. A season of loss. A morning when the thing
you assumed would always hold gives way beneath you. Storms are not
cruel so much as honest. They are the one moment the truth about a
foundation gets told out loud. Whatever was built from something
light, from shortcuts, from borrowed confidence, from the wish to
look finished before being finished, shifts and splits and comes
down. And whatever was built from patient, hidden, unglamorous work
simply stands there, wet and quiet, still holding.

I have watched both kinds fall and stand. It is a sobering thing to
realise which one you have been building.

So here is what I am choosing to do. Dig deeper than anyone will ever
see. Let the compiler, the mentor, the hard season argue with me now
rather than the storm later. Build the kind of independence that
answers for itself. And then, only then, come into the light and let
the world see what has been standing underneath the whole time.

The work no one sees is the work that holds everything up.

We Learn in the digital garden.

~ Taz