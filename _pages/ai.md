---
layout: "single"
title: "AI"
permalink: "/ai/"
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


## Semi-supervised learning

### Semi-supervised Class Incremental Learning 
#### Alexis Lechat, Stéphane Herbin and Frédéric Jurie
![MFOF](/images/incrementalL.png){: style="float: left; margin-right: 1em;height: 150px; margin-top: 1.5em;width: 200px"}
Incremental class learning is a sequential process where batches of samples annotated with new classes are introduced during the learning phase. The main objective of our work is to reduce the so-called “catastrophic forgetting”, i.e. a dramatic drop in classification performance on old classes as new ones are included. We propose to regularize the classifier and give the feature space a more stable structure using non-annotated images in addition to the annotated batches. Indeed, in several applied contexts, such as web image classification or remote sensing data interpretation, large amounts of unlabelled images are available. We demonstrate on two image data sets, MNIST and STL-10, that our approach is able to improve the global performance of classifiers learned using an incremental learning protocol, even with annotated batches of small size. 
<!-- <normal> -->
<!-- <p style="text-align: right;"> -->
<br />
    <a href="https://youtu.be/bhlO1BAbrdA" style="color:page.header.overlay_color">[Video]</a>
<!-- </normal> -->

