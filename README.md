# photo-magnific-popup
Graphics have taken on an increasingly central role to online content and the need for interactive and beautifully designed photo galleries has never been more prevalent. In this article, [Solodev](https://www.solodev.com/) will show you how to add [magnific popup by Dmitry Semenov](http://dimsemenov.com/plugins/magnific-popup/) to your photo gallery turning your photos into a slider of expanded photos with further details.

## Tutorial

View detailed instructions in Solodev's [Adding Magnific Popup to your Photo Gallery](https://www.solodev.com/blog/web-design/adding-magnific-popup-to-your-photo-gallery.stml) article.

## Demo

Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/pcd8qtL8/).

## HTML

The photo gallery has the following basic HTML markup.

```
<div class="container">
<div class="popup-gallery">
   <div class="row">
      <div class="col-md-4">
         <div class="resources-item">
            <div class="resources-category-image">
               <a href="https://www.solodev.com/assets/magnific-popup/3.jpg" title="Environment"><img class="img-responsive" alt="" src="https://www.solodev.com/assets/magnific-popup/3.jpg">
               </a>
            </div>
            <div class="resources-description">
               <p>Published: June 24, 2016</p>
               <h4>Environment</h4>
            </div>
         </div>
      </div>
      <div class="col-md-4">
         <div class="resources-item">
            <div class="resources-category-image">
               <a href="https://www.solodev.com/assets/magnific-popup/1.jpg" title="Architecture"><img class="img-responsive" alt="" src="https://www.solodev.com/assets/magnific-popup/1.jpg">
               </a>
            </div>
            <div class="resources-description">
               <p>Published: July 5, 2016</p>
               <h4>Architecture</h4>
            </div>
         </div>
      </div>
      <div class="col-md-4">
         <div class="resources-item">
            <div class="resources-category-image">
               <a href="https://www.solodev.com/assets/magnific-popup/2.jpg" title="Design"><img class="img-responsive" alt="" src="https://www.solodev.com/assets/magnific-popup/2.jpg">
               </a>
            </div>
            <div class="resources-description">
               <p>Published: August 1, 2016</p>
               <h4>Design</h4>
            </div>
         </div>
      </div>
   </div>
</div>
```
## CSS

All required CSS is in photos-popup.css

## External Includes

```
<link href="https://cdn.jsdelivr.net/jquery.magnific-popup/1.0.0/magnific-popup.css">
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
<link href="photos-popup.css">

<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.4/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
<script src="https://cdn.jsdelivr.net/jquery.magnific-popup/1.0.0/jquery.magnific-popup.js"></script>

```
