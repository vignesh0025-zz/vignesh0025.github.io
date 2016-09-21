---
layout: post
title:  "Architecture"
date:   2016-09-21 05:41:39 +0000
categories: jekyll update
---

<div class="section">
    <h5>Architecture</h5>
    <p>
    The processor we use in our system comes in various architectures as listed below. Only the most prevalent ones are given here. 
    <ul class="collection">
        <li class="collection-item">i386   / i686          - x86 (32 Bit processors)</li>
        <li class="collection-item">x86_64 / AMD64 / EMT64 - x64 (64 Bit Extensions added to 32Bit processors)      </li>
        <li class="collection-item">ia64                   (64Bit only - Itanium - Not used anymore)       </li>
        <li class="collection-item">ARM </li>
    </ul>
                                                                                                                                                         The above information is presented in terms of developer point of view. For eg. __i386__ instruction set is the decade older version of __i686__ instruction set which also becomes obselute. This instruction sets are used in x86 line of processors which is typically 32Bit Processors.
<br />
    i386 is compatible with i686 completely and I am using it as its very simple when compared to amd64 or arm instruction set. Later the same concepts can be applied for the newer line x64 line of processors.  
<br />

{% highlight objdump-nasm %}
mov byte  ah,  2    ;   8  Bit Processors like 8085 mov instruction
mov word  ax,  2    ;   16 Bit Processors like 8066 mov instruction  
mov dword eax, 2    ;   32 Bit Processors like 80386, 80486, Pentium mov instruction   
mov qword rax, 2    ;   64 Bit processors like i3/i5/i7/Core 2 Duo mov instruction
{% endhighlight %}

</p>

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
