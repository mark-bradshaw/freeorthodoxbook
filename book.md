
<section class="page-header">
<h1 class="project-name"><a href="/">Free Orthodox Book</a></h1>
   <h2 class="project-tagline">Encounter the Ancient Church</h2>
</section>

<section class="main-content">
   <h1>We're really glad that you're interested in learning more about Orthodoxy.  Like we said, this book is completely free, with no strings attached.  Just select one of the books below!</h1>
   
   <ul class="booklist">
    <li>
      <a href="javascript:selectBook('Reclaiming the Atonement')">
        <img src="https://images-na.ssl-images-amazon.com/images/I/51xn7zjW7rL.jpg" />
        <h3>Reclaiming the Atonement</h3>
        <p>Patrick Henry Reardon presents the first of three volumes exploring redemption and salvation through the lens of Scripture, patristics, and liturgics, as well as through history, philosophy, language, literature, and psychology. He brings all these perspectives together to show how the whole of Christ’s work—from Incarnation to Ascension—accomplishes the “at-one-ment” of God with man.</p>
      </a>
    </li>
    
    <li>
      <a href="javascript:selectBook('Welcome to the Orthodox Church')">
        <img src="https://images-na.ssl-images-amazon.com/images/I/514bsgOhm4L.jpg" />
        <h3>Welcome to the Orthodox Church</h3>
        <p>There are other introductory books about Orthodoxy. This one comprehensively covers the history, theology, and practice without talking over your head. Mathewes- Green takes the original approach of bringing you into a typical church for a series of visits. That is how Christians learned the faith for most of history, by coming into a community and keeping their eyes and ears open. Designed primarily for newcomers to come to understand Orthodoxy and Orthodox Christians, this guide to the faith is also a non-threatening and accessible introduction to people already "in the pews.”</p>
      </a>
    </li>
    
    <li>
      <a href="javascript:selectBook('Orthodoxy and Heterodoxy')">
        <img src="https://images-na.ssl-images-amazon.com/images/I/51pOQLMcNgL.jpg" />
        <h3>Orthodoxy and Heterodoxy</h3>
        <p>In Orthodoxy & Heterodoxy, Fr. Andrew Stephen Damick covers the gamut of ancient heresies, modern Christian denominations, fringe groups, and major world religions, highlighting the main points of each faith and how they contrast with Orthodoxy. This book is an invaluable reference for anyone who wants to understand the faiths of those they come in contact with—as well as their own.</p>
      </a>
    </li>
    
    <li>
      <a href="javascript:selectBook('An Introduction to God')">
        <img src="https://images-na.ssl-images-amazon.com/images/I/51Uf0rI0WgL.jpg" />
        <h3>An Introduction to God</h3>
        <p>Speaking to non-believers and believers alike, Fr. Andrew Stephen Damick attempts to create a sacred space in which we can encounter God. In this compact volume, he distills the essence of the traditional Christian faith, addressing the fundamental mysteries of where God is, who God is, why we go to church, and why Christian morality matters. If you’ve only heard about the Protestant or Roman Catholic version of Christianity, what he has to say may surprise you—and make you long to encounter God in Jesus Christ.</p>
      </a>
    </li>
   </ul>
   
   <div id="sendToForm">
      <p>Now all we need to send <span id="bookName"></span> to you is your address.  We promise, no one will bug you!</p>

      <fieldset>
         <legend>Name</legend>
         <input type="text" id="name" />
      </fieldset>
   </div>
</section>
    
<script>
/*
emailjs.send('default_service', "<YOUR TEMPLATE ID>", {name: "James", notes: "Check this out!"})
.then(function(response) {
   console.log("SUCCESS. status=%d, text=%s", response.status, response.text);
}, function(err) {
   console.log("FAILED. error=", err);
});
*/

fbq('track', 'ViewContent', { content_name: 'book picker' });
/* 
fbq('track', 'AddToCart');
fbq('track', 'CompleteRegistration');
*/

function selectBook(name) {
   console.log(name);
   fbq('track', 'AddToCart', { content_name: name });
}
</script>
