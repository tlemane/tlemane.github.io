---
layout: post
title: "<code>Logan Search</code>: A k-mer search for all Sequence Read public accessions"
date: 2024-11-07
inline: false
related_posts: false
---

[`Logan Search`](https://logan-search.org) is a k-mer search engine for all Sequence Read Archive public accessions (as of dec 2023). Given a DNA sequence, the service replies in a few minutes in which SRA accession(s) it is likely to occur. The service also enables to recover metadata associated to target accessions, and to perform some visualizations.

In more technical depth, the search engine uses [kmindex](https://tlemane.github.io/kmindex). It was applied to construct an index over all genome assemblies of all of SRA, more specifically over the unitigs of [Logan](https://github.com/IndexThePlanet/Logan). The website relies on [kmviz](https://tlemane.github.io/kmviz).

---

<center>
    <blockquote class="twitter-tweet"><p lang="en" dir="ltr">🧬🔍There are 50 petabases of freely-available DNA sequencing data. We introduce &quot;Logan Search&quot; which allows you to search for any DNA sequence in minutes, bringing Earth’s largest genomic resource to your fingertips.<br>🏔️ <a href="https://t.co/hmlNE8ZMl3">https://t.co/hmlNE8ZMl3</a> 🏔️<a href="https://twitter.com/hashtag/Genomics?src=hash&amp;ref_src=twsrc%5Etfw">#Genomics</a> <a href="https://twitter.com/hashtag/Bioinformatics?src=hash&amp;ref_src=twsrc%5Etfw">#Bioinformatics</a> 🧵👇 <a href="https://t.co/ms4eiNB8fA">pic.twitter.com/ms4eiNB8fA</a></p>&mdash; Pierre Peterlongo (@p_peterlongo) <a href="https://twitter.com/p_peterlongo/status/1855889588604031105?ref_src=twsrc%5Etfw">November 11, 2024</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
</center>