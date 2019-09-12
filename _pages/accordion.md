---
layout: accordion
title: "Galaxy South Green"
permalink: /accordion
tags: [ galaxy  southgreen]
description: Galaxy South Green welcome page
---


<link rel="stylesheet" type="text/css" href="{{ site.url }}/css/slider.css" />
<ul id="slider" style="display: block; height: 270px; width: 915px; padding: 0px;margin:0px;top:0px; position: relative; overflow: hidden; list-style: outsidenone none;">

<li class="click click-previous click-closed" style="top: 0px; z-index: 40; margin: 0px; padding: 0px; float: left; display: block; position: absolute; overflow: hidden; width: 750px; height: 270px; text-indent: 0px; left: 132px; cursor: pointer;">
            <div class="textref textref5">NGS analyses</div>
            <div>
                <img srcset="http://galaxy.southgreen.fr/galaxy/static/style/ngs.jpg 362w, http://galaxy.southgreen.fr/galaxy/static/style/ngs.jpg 300w" />
                <div>
                    <p>
                        <strong><a href="">NGS analyses</a></strong><br />
                    </p>
                    <p>We propose several workflows for NGS analyses in different scenarii (transcriptome vs
                        transcriptome, transcriptome vs genome
                        ...)
                        <br />It includes cleaning and mapping steps using commonly used softwares.
                        <br />
                        <br />
                        <b>Input</b>: Fastq files + FASTA for reference<br />
                        <b>Output</b>: BAM alignment files<br />
                    </p>
                    <a class="readmore1" href="http://galaxy.southgreen.fr/galaxy/u/marilyne/p/cleaning--mapping"
                        target="_blank">Access workflow</a><br /><br />
                </div>
            </div>
        </li>
        <!--End NGS Analyses-->
        <!--Start SNP Calling-->
        <li class="click click-closed" style="top: 0px; z-index: 0; margin: 0px; padding: 0px; float: left; display: block; position: absolute; overflow: hidden; width: 750px; height: 270px; text-indent: 0px; left: 0px; cursor: pointer;">
            <div class="textref">SNP calling</div>
            <div>
                <img srcset="{{ site.url }}/images/snp_visu_galaxy.PNG 362w, {{ site.url }}/images/snp_visu_galaxy.PNG 300w" />
                <div>
                    <p>
                        <strong><a href="">SNP calling</a></strong><br />
                    </p>
                    <p>
                        The SNP Calling is based on the <b>GATK toolkit</b>, using either UnifiedGenotyper or
                        HaplotypeCaller module.<br /><br />
                        <b>Input</b>: BAM alignment files + FASTA for reference<br />
                        <b>Output</b>: VCF (Variant call Format) file<br />
                    </p>
                    <a class="readmore1" href="http://galaxy.southgreen.fr/galaxy/u/dereeper/p/snp-calling"
                        target="_blank">Access workflow</a><br><br>
                    <p></p>
                </div>
            </div>
        </li>
    </ul>





