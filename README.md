<!--![My image](https://github.com/Sharwin24/Resume/blob/master/main.pdf!-->

<!--
<object data="https://github.com/Sharwin24/Resume/blob/master/main.pdf" type="application/pdf" width="595px" height="842px">
    <embed src="https://github.com/Sharwin24/Resume/blob/master/main.pdf" type="application/pdf">
        <p>This browser does not support PDFs. Please download the PDF to view it: <a href="https://github.com/Sharwin24/Resume/blob/master/main.pdf">Download PDF</a>.</p>
    </embed>
</object>
!-->

<?php
  $dir = "C:/Users/Sharwin/Documents/Github/Resume";
  $name = 'main.pdf';
  exec("/bin/convert $dir$name $dir$name.png");
  print '<img src="$dir$name.png" />';
?>

