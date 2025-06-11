# cs590-project-1-solved
**TO GET THIS SOLUTION VISIT:** [CS590 Project-1 Solved](https://mantutor.com/product/cs590-project-1-solved/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115164&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS590  Project-1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
As discussed in the class you project has the following description:

1. Download the data from the encode website. Only use DNase-seq data. Search for DNase and there will be thousands of experiments. On the search result page, on the left side there is a filter- choose the following parameters:

Assay type -&gt;DNase-seq,

Biosample -&gt; Homo sapiens,

Organ-&gt; blood, brain, bodily fluid (any one),

Cell -&gt; choose with the highest number of experiments associated with it.

Analysis -&gt; GRCh38.

Read length (nt) -&gt;101 OR 151 (choose any one).

That’s enough filter. If you have to, you can change the cell/organ to find out a read length that has a higher number of experiments associated with it. Download at least 10 different files bed narrowPeak file type from 10 different experiments.

2. Convert the narrowPeak file into a nucleotide (ATGCs) file, using the bedtools. Let’s say these files are atgc_file just an example.

3. Extract all the nucleotides from this file and store the data into a different file containing only the nucleotide sequences and nothing else. So the file will contain many many rows of nucleotides each of them having different lengths.

4. The length of each sequence in the above file is of variable length. Come up with a number that optimally crops the sequences in such a manner that all the sequences are of the same length. If you have to discard sequences that are smaller than the number that you come up with, discard them. And trim the sequence which is longer than the number that you come up with.

5. Now you should have a file containing N_1 number of sequences each having length of X. For example 500 sequences, each of length 120. This is the positive file, Or the file containing all the accessible regions in the DNA.

6. Now we need a negative file Or a file containing all the regions that do not contain accessible regions.

7. To create this file use the narrowpeak file and subtract the distance of two consecutive accessible regions. That is to find the middle region between two accessible regions.

8. Go through the same process as described above and finally you are going to have a file containing N_1 number of sequences each having length of X. This

9. This file contains all the negative values or the sequences (ATGC) that do not represent accessible regions in the DNA.

10.Now you have two files, each having a different number (row) of DNA sequences but all having the same sequence length.

11. Now repeat this for the 10 different narrowPeak files from 10 different experiments.

If you have any questions, happy to discuss during class, since this will help other students too. Most of the time I have to repeat the same solution to each individual which is not optimum. So I encourage you to ask those questions during the class time, I am more than happy to explain.
