---
layout: "single"
title: "Projects"
permalink: "/projects/"
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

## Geometric Vision and Learning

### Learning methods for multiframe Optical Flow Estimation
#### Work by Pierre Godet, who defended its PhD on friday, 22th january 2021, in collaboration with [Alexandre Boulc'h](https://www.boulch.eu/) at Valeo.ai and [Aurélien Plyer](https://github.com/aplyer) ONERA.

![MFOF](/images/SF.png){: style="float: left; margin-right: 1em;height: 150px; margin-top: 1.5em;width: 200px"} 
Pierre first derived a multiframe Lucas-Kanade method based on temporal models identified by PCA for PIV application. Turning towards deep learning approaches, he proposed "STaRFlow" a multiframe optical flow estimation relying on a spatio-temporal recurrent cell with occultation handling. STaRFlow is among state-of-the-art methods on Kitti and Sintel benchmark and shows remarkable generalization capabilities to videos in real contexts. 
<!-- <normal> -->
<!-- <p style="text-align: right;"> -->
<br />
    <a href="https://arxiv.org/pdf/2007.05481" style="color:page.header.overlay_color">[PDF]</a>
    <a href="https://github.com/pgodet/star_flow" style="color:page.header.overlay_color">[GitHub]</a>
</p>
<!-- </normal> -->

## Learning and beyond

### Semi-supervised Class Incremental Learning 
#### Alexis Lechat, Stéphane Herbin and Frédéric Jurie
![MFOF](/images/incrementalL.png){: style="float: left; margin-right: 1em;height: 150px; margin-top: 1.5em;width: 200px"}
Incremental class learning is a sequential process where batches of samples annotated with new classes are introduced during the learning phase. The main objective of our work is to reduce the so-called “catastrophic forgetting”, i.e. a dramatic drop in classification performance on old classes as new ones are included. We propose to regularize the classifier and give the feature space a more stable structure using non-annotated images in addition to the annotated batches. Indeed, in several applied contexts, such as web image classification of remote sensing data interpretation, large amounts of unlabelled images are available. We demonstrate on two image data sets, MNIST and STL-10, that our approach is able to improve the global performance of classifiers learned using an incremental learning protocol, even with annotated batches of small size. 
