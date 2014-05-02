restrict-adblocker
==================

Restrict any ad blocker from your website just add the following code to your website 

insert your ad code in div named  "myAds"  and change url to which user should be redireced...




<!--  Put Ads in div called my Ads as shown below --!>

<div class="myAds" style=" text-align:center;margin:10px">

	<!-- advert code goes here -->
    
</div>

<!-- Include That on every page at the end of </body> tag --!>
<script>
function TestPage() {
    if ($('.myAds').height() == 0)
        window.location.href="http://www.examle.com/restricted.php";
}

$(TestPage);
</script>
