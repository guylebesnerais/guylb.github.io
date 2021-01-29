---
layout: "single"
title: ""
permalink: "/research/"
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

Most of my research contributions are now related to the work of PhD students I co-advise.

# Projects

![disca](/images/disca.png){: style="float: left; margin-right: 1em;height: 100px; margin-top: 1.5em;width: 130px"} 
### Interactive Learning for Semantic Segmentation in Earth Observation
*G. Lenczner, A. Chan Hon Tong, N. Luminari, B. Le Saux, G. Le Besnerais*  
ECML-PKDD 2020, MACLEAN Workshop.
<span style="color:#e49b0f">*Best Student Paper Award.*</span>
<!-- <normal> -->
<!-- <p style="text-align: right;"> -->
<br />
    <a href="http://ceur-ws.org/Vol-2766/paper1.pdf" style="color:page.header.overlay_color">[PDF]</a>
    <a href="https://github.com/delair-ai/DISCA" style="color:page.header.overlay_color">[GitHub]</a>
    <a style="color:page.header.overlay_color; cursor: pointer; cursor: hand;" onclick="toggleVisibility('bibtex_disca');">[BibTeX]</a>
<!-- </p> -->
<!-- </normal> -->
<div id="bibtex_disca" style="display:none;">
<small>
<a class="btn"  onclick="copyToClip('bib_disca');">copy to clipboard</a>
<div class="highlighter-rouge"><pre id="bib_disca" class="highlight">
@inproceedings{lenczner2020interactive,
author = {Lenczner, G. and Chan-Hon-Tong, A. and Luminari, N. and Le Saux, B. and Le Besnerais, G.},
title = {Interactive Learning for Semantic Segmentation in Earth Observation},
booktitle = {ECML-PKDD MACLEAN Workshop},
year = {2020},
}
</pre></div></small>
</div>


![MFOF](/images/SF.png){: style="float: left; margin-right: 1em;height: 100px; margin-top: 1.5em;width: 130px"} 
### Learning methods for multiframe Optical Flow Estimation
###### This work is conducted by Pierre Godet, who defended its PhD on friday, 22th january 2021, in collaboration with [Alexandre Boulc'h](https://www.boulch.eu/)) at Valeo.ai and [Aurélien Plyer](https://github.com/aplyer) ONERA.
<!-- <normal> -->
<!-- <p style="text-align: right;"> -->
<br />
    <a href="https://arxiv.org/pdf/2007.05481" style="color:page.header.overlay_color">[PDF]</a>
    <a href="https://github.com/pgodet/star_flow" style="color:page.header.overlay_color">[GitHub]</a>
<!-- </p> -->
<!-- </normal> -->


# Students

### Gaston Lenczner


<!-- ------
