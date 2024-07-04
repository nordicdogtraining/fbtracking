# fbtracking
FB tracking code

# Main Pixel Code - Add to All Pages.
<!-- Meta Pixel Code -->
<script>
!function(f,b,e,v,n,t,s)
{if(f.fbq)return;n=f.fbq=function(){n.callMethod?
n.callMethod.apply(n,arguments):n.queue.push(arguments)};
if(!f._fbq)f._fbq=n;n.push=n;n.loaded=!0;n.version='2.0';
n.queue=[];t=b.createElement(e);t.async=!0;
t.src=v;s=b.getElementsByTagName(e)[0];
s.parentNode.insertBefore(t,s)}(window, document,'script',
'https://connect.facebook.net/en_US/fbevents.js');
fbq('init', '237988050632795');
fbq('track', 'PageView');
</script>
<noscript><img height="1" width="1" style="display:none"
src="https://www.facebook.com/tr?id=237988050632795&ev=PageView&noscript=1"
/></noscript>
<!-- End Meta Pixel Code -->

# Add To Cart.
# Add to these pages:
https://members.nordicdogtrainer.com/membership-account/membership-checkout/?level=6
https://members.nordicdogtrainer.com/membership-account/membership-checkout/?level=2
<script>
fbq('track', 'AddToCart');
</script>

# Purchase Event.
This one is a little trickier but... If we can add it to the thank you pages after purchase that would be great.
The amount can be changed based the the related purchas if the thank you pages are different for each option. If there is only one thank you page for all purchase options then we can leave the amount as shown below.
<script>
fbq('track', 'Purchase', {currency: "USD", value: 295.00});
</script>
