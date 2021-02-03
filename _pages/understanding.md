---
layout: "single"
title: "Understanding"
permalink: "/understanding/"
author_profile: true

---

<script type="text/javascript">
   function toggleVisibility(block_id) {
       var e = document.getElementById(block_id);
       if(e.style.display == 'block')
          e.style.display = 'none';
       else
          e.style.display = 'block';
   }
    function copyToClip(element) {
        var str = document.getElementById(element).innerHTML;
        function listener(e) {
            e.clipboardData.setData("text/html", str);
            e.clipboardData.setData("text/plain", str);
            e.preventDefault();
        }
        document.addEventListener("copy", listener);
        document.execCommand("copy");
        document.removeEventListener("copy", listener);
};
</script>

## Remote Sensing

### MiniFrance: a database for semi-supervised learning in remote sensing
#### Javiera Castillo Navarro, Bertrand Le Saux (ESA), Sébastien Lefèvre (UBS/INRIA)

![MiniF](/images/miniF.png){: style="float: left; margin-right: 1em;height: 150px; margin-top: 1.5em;width: 320px"} 
We introduce a novel large-scale dataset for semi-supervised semantic segmentation in Earth Observation, the MiniFrance suite. MiniFrance has several unprecedented properties: it is large-scale, containing over 2000 very high resolution aerial images, accounting for more than 200 billions samples (pixels); it is varied, covering 16 conurbations in France, with various climates, different landscapes, and urban as well as countryside scenes; and it is challenging, considering land use classes with high-level semantics. Nevertheless, the most distinctive quality of MiniFrance is being the only dataset in the field especially designed for semi-supervised learning: it contains labeled and unlabeled images in its training partition, which reproduces a life-like scenario.  
<!-- <normal> -->
<!-- <p style="text-align: right;"> -->
<br />
    <a href="https://arxiv.org/abs/2010.07830" style="color:page.header.overlay_color">[PDF]</a>
    <a href="https://www.ieee-dataport.org/open-access/minifrance" style="color:page.header.overlay_color">[Data]</a>
<!-- </normal> -->


## Video Interpretation

### Visual tracking 

