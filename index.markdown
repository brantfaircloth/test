---
title: Home
layout: default
---

# test #

This is a test.

{% highlight pycon %}

>>> import fasta
>>> seq = fasta.FastaSequence()
>>> seq.identifier = 'chr5_6255117_6255601_0:0:0_1:0:0_13'
>>> seq.sequence = 'CTTGGATCAGATGAAAATGCAGC'
>>> q = "5 5 17 17 3 17 17 17 17 17 17 17 17 17 17 17 17 17 17 17 17 17 17"
>>> seq.set_quality(q)
>>> seq.sequence
'CTTGGATCAGATGAAAATGCAGC'
>>> seq.quality
array([ 5,  5, 17, 17,  3, 17, 17, 17, 17, 17, 17, 17, 17, 17, 17, 17, 17,
       17, 17, 17, 17, 17, 17], dtype=uint8)


{% endhighlight %}

