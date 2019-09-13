---
layout: slideshow
title: "Galaxy South Green"
permalink: /slideshow/
tags: [ galaxy  southgreen]
description: Galaxy South Green welcome page
---
<link rel="stylesheet" type="text/css" href="{{ site.url }}/css/slideshow.css" />
<!-- Container for the image gallery -->
<div class="container">

  <!-- Full-width images with number text -->
  <div class="mySlides">
    <div class="numbertext">1 / 6</div>
    <div class="slidecontainer">
        <img class="slideimg" src="http://galaxy.southgreen.fr/galaxy/static/style/ngs.jpg">
        <div class="slidetext">
            <p><strong><a href="">NGS analyses</a></strong><br /></p>
            <p>We propose several workflows for NGS analyses in different scenarii (transcriptome vs transcriptome, transcriptome vs genome...)
            <br />
            It includes cleaning and mapping steps using commonly used softwares.
            <br />
            <br />
            <b>Input</b>: Fastq files + FASTA for reference<br />
            <b>Output</b>: BAM alignment files<br />
            <a class="readmore1" href="http://galaxy.southgreen.fr/galaxy/u/marilyne/p/cleaning--mapping" target="_blank">Access workflow</a>
            </p>
        </div> 
    </div>    
  </div>

  <div class="mySlides">
    <div class="numbertext">1 / 6</div>
    <div class="slidecontainer">
        <img class="slideimg" src="{{ site.url }}/images/snp_visu_galaxy.PNG">
        <div class="slidetext">
            <p><strong><a href="">SNP calling</a></strong><br /></p>
            <p>
            The SNP Calling is based on the <b>GATK toolkit</b>, using either UnifiedGenotyper or HaplotypeCaller module.<br /><br />
            <b>Input</b>: BAM alignment files + FASTA for reference<br />
            <b>Output</b>: VCF (Variant call Format) file<br />
            <a class="readmore1" href="http://galaxy.southgreen.fr/galaxy/u/dereeper/p/snp-calling" target="_blank">Access workflow</a>
            </p><br><br>
            <p></p>
        </div> 
    </div>    
  </div>

<div class="mySlides">
    <div class="numbertext">1 / 6</div>
    <div class="slidecontainer">
        <img class="slideimg" src="http://galaxy.southgreen.fr/galaxy/static/style/mdsplot.PNG">
        <div class="slidetext">
            <p><strong><a href="http://galaxy.southgreen.fr/galaxy/u/dereeper/p/sniplay-workflow" target="_blank">SNP analysis</a></strong><br></p>
			<p><b>SNiPlay3</b> complete workflow: a package for exploration and large scale analyses of SNP polymorphisms (filtering, SNP density, diversity, linkagedisequilibrium) (Dereeper et al, 2015) <br/><br/>
            <b>Input</b>: VCF<br/>
            <a class="readmore1" href="http://galaxy.southgreen.fr/galaxy/u/dereeper/p/sniplay-statistics-diversity-filtering" target="_blank">Access workflow</a>
            </p><br><br>
            <p></p>
        </div> 
    </div>    
  </div>

  <div class="mySlides">
    <div class="numbertext">1 / 6</div>
    <div class="slidecontainer">
        <img class="slideimg" src="http://galaxy.southgreen.fr/galaxy/static/style/Manhattan_Plot.png">
        <div class="slidetext">
            <p><strong><a href="">GWAS</a></strong><br /></p>
			<p><b>SNiPlay3 GWAS workflow</b>: Tassel-based GWAS workflow (GLM model) including population structure and correction for structure (Dereeper et al, 2015) <br/><br/>
            <b>Input</b>: VCF + Phenotypic tabulated file<br/>
            <a class="readmore1" href="http://galaxy.southgreen.fr/galaxy/u/dereeper/p/sniplay-gwas-analysis" target="_blank">Access workflow</a><br /><br />
            </p>
            <p></p>
        </div> 
    </div>    
  </div>

  <div class="mySlides">
    <div class="numbertext">1 / 6</div>
    <div class="slidecontainer">
        <img class="slideimg" src="http://galaxy.southgreen.fr/galaxy/static/style/scaffremodeler.png">
        <div class="slidetext">
            <p><strong>Structural variations</strong><br></p>
			<p><b>Scaffremodeler</b> can be used to detect large structural variations between a reference sequence and a resequenced genome (Martin et al, 2016) <br/><br/>
            <b>Input</b>: Fastq + FASTA<br/>
            <a class="readmore1" href="http://galaxy.southgreen.fr/galaxy/u/droc/p/scaffremodler--structural-variation" target="_blank">Access workflow</a><br><br>
            </p>
            <p></p>
        </div> 
    </div>    
  </div>

<div class="mySlides">
    <div class="numbertext">1 / 6</div>
    <div class="slidecontainer">
        <img class="slideimg" src="http://galaxy.southgreen.fr/galaxy/static/style/chrom_reconstruction.png">
        <div class="slidetext">
            <p><strong>Chromosome reconstruction</strong><br></p>
            <p><b>Scaffrehunter</b> tools assemble scaffolds into pseudomolecules using markers genotyped in a population (Martin et al, 2016) <br/><br/>
            <b>Input</b>: Fastq + FASTA<br/>
            <a class="readmore1" href="http://galaxy.southgreen.fr/galaxy/u/droc/p/scaffhunter--chromosome-reconstruction" target="_blank">Access workflow</a></p><br><br>
            <p></p>
        </div> 
    </div>    
  </div>
  
  <div class="mySlides">
    <div class="numbertext">1 / 6</div>
    <div class="slidecontainer">
        <img class="slideimg" src="{{ site.url }}/images/metagenomics.PNG">
        <div class="slidetext">
            <p><strong>Metagenomics</strong><br></p>
            <p><b>FROGS</b>: Find Rapidly OTU with Galaxy Solution (Pascal et al, 2015) <br/><br/>
            <b>Input</b>: Fastq files<br/>
            <a class="readmore1" href="http://galaxy.southgreen.fr/galaxy/u/dereeper/p/frogs" target="_blank">Access workflow</a><br><br>
            </p>
            <p></p>
        </div> 
    </div>    
  </div>

<div class="mySlides">
    <div class="numbertext">1 / 6</div>
    <div class="slidecontainer">
        <img class="slideimg" src="http://galaxy.southgreen.fr/galaxy/static/style/tree.jpg">
        <div class="slidetext">
            <p><strong>Gene families</strong><br></p>
            <p><b>Greenphyl / GenFam</b>: comparative and functional genomics in plants (Rouard et al, 2011).<br/><br/>
            <b>Input</b>: FASTA file, Species tree file<br/><br/>
            <a class="readmore1" href="http://galaxy.southgreen.fr/galaxy/u/jfdufayard/p/phylogeny-workflows-1" target="_blank">Access workflow</a><br><br>
            </p>
            <p></p>
        </div> 
    </div>    
  </div>

  <div class="mySlides">
    <div class="numbertext">1 / 6</div>
    <div class="slidecontainer">
        <img class="slideimg" src="{{ site.url }}/images/circos.jpg">
        <div class="slidetext">
            <p><strong>Mosaic genome reconstruction</strong><br></p>
            <p><b>TraceAncestor / KDE_Classifier</b>: Two approaches to analyze the mosaic structure of plant genomes<br/><br/>
            <b>Input</b>: VCF file + structure file<br/><br/>
            <a class="readmore1" href="http://galaxy.southgreen.fr/galaxy/u/acomte/p/reconstruction-of-mosaic-genomes" target="_blank">Access workflow</a><br><br>
            </p>
            <p></p>
        </div> 
    </div>    
  </div>

  <!-- Next and previous buttons -->
  <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
  <a class="next" onclick="plusSlides(1)">&#10095;</a>

  <!-- Image text -->
  <div class="caption-container">
    <p id="caption"></p>
  </div>

  <!-- Thumbnail images -->
  <div class="row">
    <div class="column">
      <img class="demo cursor" src="http://galaxy.southgreen.fr/galaxy/static/style/ngs.jpg" style="width:100%" onclick="currentSlide(1)" alt="NGS Analysis">
    </div>
    <div class="column">
      <img class="demo cursor" src="{{ site.url }}/images/snp_visu_galaxy.PNG" style="width:100%" onclick="currentSlide(2)" alt="SNP calling">
    </div>
    <div class="column">
      <img class="demo cursor" src="http://galaxy.southgreen.fr/galaxy/static/style/mdsplot.PNG" style="width:100%" onclick="currentSlide(3)" alt="SNP analysis">
    </div>
    <div class="column">
      <img class="demo cursor" src="http://galaxy.southgreen.fr/galaxy/static/style/Manhattan_Plot.png" style="width:100%" onclick="currentSlide(4)" alt="GWAS">
    </div>
    <div class="column">
      <img class="demo cursor" src="http://galaxy.southgreen.fr/galaxy/static/style/scaffremodeler.png" style="width:100%" onclick="currentSlide(5)" alt="Structural variations">
    </div>
    <div class="column">
      <img class="demo cursor" src="http://galaxy.southgreen.fr/galaxy/static/style/chrom_reconstruction.png" style="width:100%" onclick="currentSlide(6)" alt="Chromosome reconstruction">
    </div>
    <div class="column">
      <img class="demo cursor" src="{{ site.url }}/images/metagenomics.PNG" style="width:100%" onclick="currentSlide(7)" alt="Metagenomics">
    </div>
    <div class="column">
      <img class="demo cursor" src="http://galaxy.southgreen.fr/galaxy/static/style/tree.jpg" style="width:100%" onclick="currentSlide(8)" alt="Gene families">
    </div>
    <div class="column">
      <img class="demo cursor" src="{{ site.url }}/images/circos.jpg" style="width:100%" onclick="currentSlide(9)" alt="Mosaic genome reconstruction">
    </div>


    
    
  </div>
</div>