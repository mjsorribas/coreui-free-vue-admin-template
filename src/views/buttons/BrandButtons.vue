<template>
  <div class="animated fadeIn">
    <b-row>
      <b-col cols="12">
        <b-card>
          <div slot="header">
            <strong>Brand Button</strong>
          </div>
          <small>Usage </small><code style="text-transform:lowercase">&lt;b-button variant="facebook"&gt;&lt;span&gt;Facebook&lt;/span&gt;&lt;/b-button&gt;</code>
          <hr/>
          <h6>Size Small <small>Add <code>size="sm"</code></small></h6>
          <p>
            <BrandButton v-bind:size="'sm'" v-bind:variant="'facebook'" v-bind:icon="'fa fa-facebook'" v-bind:title="'Facebook'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'twitter'" v-bind:icon="'fa fa-twitter'" v-bind:title="'Twitter'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'linkedin'" v-bind:icon="'fa fa-linkedin'" v-bind:title="'LinkedIn'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'flickr'" v-bind:icon="'fa fa-flickr'" v-bind:title="'Flickr'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'tumblr'" v-bind:icon="'fa fa-tumblr'" v-bind:title="'Tumblr'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'xing'" v-bind:icon="'fa fa-xing'" v-bind:title="'Xing'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'github'" v-bind:icon="'fa fa-github'" v-bind:title="'Github'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'html5'" v-bind:icon="'fa fa-html5'" v-bind:title="'HTML5'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'openid'" v-bind:icon="'fa fa-openid'" v-bind:title="'OpenID'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'stack-overflow'" v-bind:icon="'fa fa-stack-overflow'" v-bind:title="'StackOverflow'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'css3'" v-bind:icon="'fa fa-css3'" v-bind:title="'CSS3'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'youtube'" v-bind:icon="'fa fa-youtube'" v-bind:title="'YouTube'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'dribbble'" v-bind:icon="'fa fa-dribbble'" v-bind:title="'Dribbble'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'google-plus'" v-bind:icon="'fa fa-google-plus'" v-bind:title="'Google+'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'instagram'" v-bind:icon="'fa fa-instagram'" v-bind:title="'Instagram'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'pinterest'" v-bind:icon="'fa fa-pinterest'" v-bind:title="'Pinterest'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'vk'" v-bind:icon="'fa fa-vk'" v-bind:title="'VK'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'yahoo'" v-bind:icon="'fa fa-yahoo'" v-bind:title="'Yahoo'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'behance'" v-bind:icon="'fa fa-behance'" v-bind:title="'Behance'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'dropbox'" v-bind:icon="'fa fa-dropbox'" v-bind:title="'Dropbox'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'reddit'" v-bind:icon="'fa fa-reddit'" v-bind:title="'Reddit'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'spotify'" v-bind:icon="'fa fa-spotify'" v-bind:title="'Spotify'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'vine'" v-bind:icon="'fa fa-vine'" v-bind:title="'Vine'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'foursquare'" v-bind:icon="'fa fa-foursquare'" v-bind:title="'Forsquare'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'vimeo'" v-bind:icon="'fa fa-vimeo'" v-bind:title="'Vimeo'" />
          </p>
          <h6>Size Normal</h6>
          <p>
            <BrandButton v-bind:variant="'facebook'" v-bind:icon="'fa fa-facebook'" v-bind:title="'Facebook'" />
            <BrandButton v-bind:variant="'twitter'" v-bind:icon="'fa fa-twitter'" v-bind:title="'Twitter'" />
            <BrandButton v-bind:variant="'linkedin'" v-bind:icon="'fa fa-linkedin'" v-bind:title="'LinkedIn'" />
            <BrandButton v-bind:variant="'flickr'" v-bind:icon="'fa fa-flickr'" v-bind:title="'Flickr'" />
            <BrandButton v-bind:variant="'tumblr'" v-bind:icon="'fa fa-tumblr'" v-bind:title="'Tumblr'" />
            <BrandButton v-bind:variant="'xing'" v-bind:icon="'fa fa-xing'" v-bind:title="'Xing'" />
            <BrandButton v-bind:variant="'github'" v-bind:icon="'fa fa-github'" v-bind:title="'Github'" />
            <BrandButton v-bind:variant="'html5'" v-bind:icon="'fa fa-html5'" v-bind:title="'HTML5'" />
            <BrandButton v-bind:variant="'openid'" v-bind:icon="'fa fa-openid'" v-bind:title="'OpenID'" />
            <BrandButton v-bind:variant="'stack-overflow'" v-bind:icon="'fa fa-stack-overflow'" v-bind:title="'StackOverflow'" />
            <BrandButton v-bind:variant="'css3'" v-bind:icon="'fa fa-css3'" v-bind:title="'CSS3'" />
            <BrandButton v-bind:variant="'youtube'" v-bind:icon="'fa fa-youtube'" v-bind:title="'YouTube'" />
            <BrandButton v-bind:variant="'dribbble'" v-bind:icon="'fa fa-dribbble'" v-bind:title="'Dribbble'" />
            <BrandButton v-bind:variant="'google-plus'" v-bind:icon="'fa fa-google-plus'" v-bind:title="'Google+'" />
            <BrandButton v-bind:variant="'instagram'" v-bind:icon="'fa fa-instagram'" v-bind:title="'Instagram'" />
            <BrandButton v-bind:variant="'pinterest'" v-bind:icon="'fa fa-pinterest'" v-bind:title="'Pinterest'" />
            <BrandButton v-bind:variant="'vk'" v-bind:icon="'fa fa-vk'" v-bind:title="'VK'" />
            <BrandButton v-bind:variant="'yahoo'" v-bind:icon="'fa fa-yahoo'" v-bind:title="'Yahoo'" />
            <BrandButton v-bind:variant="'behance'" v-bind:icon="'fa fa-behance'" v-bind:title="'Behance'" />
            <BrandButton v-bind:variant="'dropbox'" v-bind:icon="'fa fa-dropbox'" v-bind:title="'Dropbox'" />
            <BrandButton v-bind:variant="'reddit'" v-bind:icon="'fa fa-reddit'" v-bind:title="'Reddit'" />
            <BrandButton v-bind:variant="'spotify'" v-bind:icon="'fa fa-spotify'" v-bind:title="'Spotify'" />
            <BrandButton v-bind:variant="'vine'" v-bind:icon="'fa fa-vine'" v-bind:title="'Vine'" />
            <BrandButton v-bind:variant="'foursquare'" v-bind:icon="'fa fa-foursquare'" v-bind:title="'Forsquare'" />
            <BrandButton v-bind:variant="'vimeo'" v-bind:icon="'fa fa-vimeo'" v-bind:title="'Vimeo'" />
          </p>
          <h6>Size Large <small>Add <code>size="lg"</code></small></h6>
          <p>
            <BrandButton v-bind:size="'lg'" v-bind:variant="'facebook'" v-bind:icon="'fa fa-facebook'" v-bind:title="'Facebook'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'twitter'" v-bind:icon="'fa fa-twitter'" v-bind:title="'Twitter'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'linkedin'" v-bind:icon="'fa fa-linkedin'" v-bind:title="'LinkedIn'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'flickr'" v-bind:icon="'fa fa-flickr'" v-bind:title="'Flickr'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'tumblr'" v-bind:icon="'fa fa-tumblr'" v-bind:title="'Tumblr'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'xing'" v-bind:icon="'fa fa-xing'" v-bind:title="'Xing'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'github'" v-bind:icon="'fa fa-github'" v-bind:title="'Github'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'html5'" v-bind:icon="'fa fa-html5'" v-bind:title="'HTML5'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'openid'" v-bind:icon="'fa fa-openid'" v-bind:title="'OpenID'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'stack-overflow'" v-bind:icon="'fa fa-stack-overflow'" v-bind:title="'StackOverflow'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'css3'" v-bind:icon="'fa fa-css3'" v-bind:title="'CSS3'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'youtube'" v-bind:icon="'fa fa-youtube'" v-bind:title="'YouTube'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'dribbble'" v-bind:icon="'fa fa-dribbble'" v-bind:title="'Dribbble'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'google-plus'" v-bind:icon="'fa fa-google-plus'" v-bind:title="'Google+'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'instagram'" v-bind:icon="'fa fa-instagram'" v-bind:title="'Instagram'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'pinterest'" v-bind:icon="'fa fa-pinterest'" v-bind:title="'Pinterest'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'vk'" v-bind:icon="'fa fa-vk'" v-bind:title="'VK'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'yahoo'" v-bind:icon="'fa fa-yahoo'" v-bind:title="'Yahoo'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'behance'" v-bind:icon="'fa fa-behance'" v-bind:title="'Behance'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'dropbox'" v-bind:icon="'fa fa-dropbox'" v-bind:title="'Dropbox'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'reddit'" v-bind:icon="'fa fa-reddit'" v-bind:title="'Reddit'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'spotify'" v-bind:icon="'fa fa-spotify'" v-bind:title="'Spotify'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'vine'" v-bind:icon="'fa fa-vine'" v-bind:title="'Vine'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'foursquare'" v-bind:icon="'fa fa-foursquare'" v-bind:title="'Forsquare'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'vimeo'" v-bind:icon="'fa fa-vimeo'" v-bind:title="'Vimeo'" />
          </p>
        </b-card>
      </b-col><!--/.col-->
      <b-col cols="12">
        <b-card>
          <div slot="header">
            <strong>Brand Button </strong> <small>Icons only</small>
          </div>
          <small>Usage </small> <code style="text-transform:lowercase">&lt;b-button variant="facebook icon"&gt;&lt;span&gt;Facebook&lt;/span&gt;&lt;/b-button&gt;</code>
          <hr/>
          <h6>Size Small <small>Add <code>size="sm"</code></small></h6>
          <p>
            <BrandButton v-bind:size="'sm'" v-bind:variant="'facebook icon'" v-bind:icon="'fa fa-facebook'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'twitter  icon'" v-bind:icon="'fa fa-twitter'"  />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'linkedin icon'" v-bind:icon="'fa fa-linkedin'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'flickr icon'" v-bind:icon="'fa fa-flickr'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'tumblr icon'" v-bind:icon="'fa fa-tumblr'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'xing icon'" v-bind:icon="'fa fa-xing'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'github icon'" v-bind:icon="'fa fa-github'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'html5 icon'" v-bind:icon="'fa fa-html5'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'openid icon'" v-bind:icon="'fa fa-openid'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'stack-overflow icon'" v-bind:icon="'fa fa-stack-overflow'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'css3 icon'" v-bind:icon="'fa fa-css3'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'youtube icon'" v-bind:icon="'fa fa-youtube'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'dribbble icon'" v-bind:icon="'fa fa-dribbble'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'google-plus icon'" v-bind:icon="'fa fa-google-plus'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'instagram icon'" v-bind:icon="'fa fa-instagram'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'pinterest icon'" v-bind:icon="'fa fa-pinterest'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'vk icon'" v-bind:icon="'fa fa-vk'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'yahoo icon'" v-bind:icon="'fa fa-yahoo'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'behance icon'" v-bind:icon="'fa fa-behance'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'dropbox icon'" v-bind:icon="'fa fa-dropbox'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'reddit icon'" v-bind:icon="'fa fa-reddit'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'spotify icon'" v-bind:icon="'fa fa-spotify'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'vine icon'" v-bind:icon="'fa fa-vine'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'foursquare icon'" v-bind:icon="'fa fa-foursquare'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'vimeo icon'" v-bind:icon="'fa fa-vimeo'" />
          </p>
          <h6>Size Normal</h6>
          <p>
            <BrandButton v-bind:variant="'facebook icon'" v-bind:icon="'fa fa-facebook'" />
            <BrandButton v-bind:variant="'twitter  icon'" v-bind:icon="'fa fa-twitter'"  />
            <BrandButton v-bind:variant="'linkedin icon'" v-bind:icon="'fa fa-linkedin'" />
            <BrandButton v-bind:variant="'flickr icon'" v-bind:icon="'fa fa-flickr'" />
            <BrandButton v-bind:variant="'tumblr icon'" v-bind:icon="'fa fa-tumblr'" />
            <BrandButton v-bind:variant="'xing icon'" v-bind:icon="'fa fa-xing'" />
            <BrandButton v-bind:variant="'github icon'" v-bind:icon="'fa fa-github'" />
            <BrandButton v-bind:variant="'html5 icon'" v-bind:icon="'fa fa-html5'" />
            <BrandButton v-bind:variant="'openid icon'" v-bind:icon="'fa fa-openid'" />
            <BrandButton v-bind:variant="'stack-overflow icon'" v-bind:icon="'fa fa-stack-overflow'" />
            <BrandButton v-bind:variant="'css3 icon'" v-bind:icon="'fa fa-css3'" />
            <BrandButton v-bind:variant="'youtube icon'" v-bind:icon="'fa fa-youtube'" />
            <BrandButton v-bind:variant="'dribbble icon'" v-bind:icon="'fa fa-dribbble'" />
            <BrandButton v-bind:variant="'google-plus icon'" v-bind:icon="'fa fa-google-plus'" />
            <BrandButton v-bind:variant="'instagram icon'" v-bind:icon="'fa fa-instagram'" />
            <BrandButton v-bind:variant="'pinterest icon'" v-bind:icon="'fa fa-pinterest'" />
            <BrandButton v-bind:variant="'vk icon'" v-bind:icon="'fa fa-vk'" />
            <BrandButton v-bind:variant="'yahoo icon'" v-bind:icon="'fa fa-yahoo'" />
            <BrandButton v-bind:variant="'behance icon'" v-bind:icon="'fa fa-behance'" />
            <BrandButton v-bind:variant="'dropbox icon'" v-bind:icon="'fa fa-dropbox'" />
            <BrandButton v-bind:variant="'reddit icon'" v-bind:icon="'fa fa-reddit'" />
            <BrandButton v-bind:variant="'spotify icon'" v-bind:icon="'fa fa-spotify'" />
            <BrandButton v-bind:variant="'vine icon'" v-bind:icon="'fa fa-vine'" />
            <BrandButton v-bind:variant="'foursquare icon'" v-bind:icon="'fa fa-foursquare'" />
            <BrandButton v-bind:variant="'vimeo icon'" v-bind:icon="'fa fa-vimeo'" />
          </p>
          <h6>Size Large <small>Add <code>size="lg"</code></small></h6>
          <p>
            <BrandButton v-bind:size="'lg'" v-bind:variant="'facebook icon'" v-bind:icon="'fa fa-facebook'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'twitter  icon'" v-bind:icon="'fa fa-twitter'"  />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'linkedin icon'" v-bind:icon="'fa fa-linkedin'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'flickr icon'" v-bind:icon="'fa fa-flickr'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'tumblr icon'" v-bind:icon="'fa fa-tumblr'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'xing icon'" v-bind:icon="'fa fa-xing'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'github icon'" v-bind:icon="'fa fa-github'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'html5 icon'" v-bind:icon="'fa fa-html5'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'openid icon'" v-bind:icon="'fa fa-openid'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'stack-overflow icon'" v-bind:icon="'fa fa-stack-overflow'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'css3 icon'" v-bind:icon="'fa fa-css3'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'youtube icon'" v-bind:icon="'fa fa-youtube'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'dribbble icon'" v-bind:icon="'fa fa-dribbble'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'google-plus icon'" v-bind:icon="'fa fa-google-plus'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'instagram icon'" v-bind:icon="'fa fa-instagram'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'pinterest icon'" v-bind:icon="'fa fa-pinterest'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'vk icon'" v-bind:icon="'fa fa-vk'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'yahoo icon'" v-bind:icon="'fa fa-yahoo'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'behance icon'" v-bind:icon="'fa fa-behance'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'dropbox icon'" v-bind:icon="'fa fa-dropbox'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'reddit icon'" v-bind:icon="'fa fa-reddit'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'spotify icon'" v-bind:icon="'fa fa-spotify'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'vine icon'" v-bind:icon="'fa fa-vine'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'foursquare icon'" v-bind:icon="'fa fa-foursquare'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'vimeo icon'" v-bind:icon="'fa fa-vimeo'" />
          </p>
        </b-card>
      </b-col><!--/.col-->

      <b-col cols="12">
        <b-card>
          <div slot="header">
            <strong>Brand Button </strong> <small>Text only</small>
          </div>
          <small>Usage </small> <code style="text-transform:lowercase">&lt;b-button variant="facebook text"&gt;&lt;span&gt;Facebook&lt;/span&gt;&lt;/b-button&gt;</code>
          <hr/>
          <h6>Size Small <small>Add <code>size="sm"</code></small></h6>
          <p>
            <BrandButton v-bind:size="'sm'" v-bind:variant="'facebook text'" v-bind:title="'Facebook'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'twitter text'" v-bind:title="'Twitter'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'linkedin text'" v-bind:title="'LinkedIn'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'flickr text'" v-bind:title="'Flickr'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'tumblr text'" v-bind:title="'Tumblr'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'xing text'" v-bind:title="'Xing'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'github text'" v-bind:title="'Github'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'html5 text'"  v-bind:title="'HTML5'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'openid text'" v-bind:title="'OpenID'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'stack-overflow text'" v-bind:title="'StackOverflow'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'css3 text'" v-bind:title="'CSS3'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'youtube text'" v-bind:title="'YouTube'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'dribbble text'" v-bind:title="'Dribbble'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'google-plus text'" v-bind:title="'Google+'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'instagram text'" v-bind:title="'Instagram'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'pinterest text'" v-bind:title="'Pinterest'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'vk text'" v-bind:title="'VK'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'yahoo text'" v-bind:title="'Yahoo'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'behance text'" v-bind:title="'Behance'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'dropbox text'" v-bind:title="'Dropbox'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'reddit text'" v-bind:title="'Reddit'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'spotify text'" v-bind:title="'Spotify'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'vine text'" v-bind:title="'Vine'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'foursquare text'" v-bind:title="'Forsquare'" />
            <BrandButton v-bind:size="'sm'" v-bind:variant="'vimeo text'" v-bind:title="'Vimeo'" />
          </p>
          <h6>Size Normal</h6>
          <p>
            <BrandButton v-bind:variant="'facebook text'" v-bind:title="'Facebook'" />
            <BrandButton v-bind:variant="'twitter text'" v-bind:title="'Twitter'" />
            <BrandButton v-bind:variant="'linkedin text'" v-bind:title="'LinkedIn'" />
            <BrandButton v-bind:variant="'flickr text'" v-bind:title="'Flickr'" />
            <BrandButton v-bind:variant="'tumblr text'" v-bind:title="'Tumblr'" />
            <BrandButton v-bind:variant="'xing text'" v-bind:title="'Xing'" />
            <BrandButton v-bind:variant="'github text'" v-bind:title="'Github'" />
            <BrandButton v-bind:variant="'html5 text'"  v-bind:title="'HTML5'" />
            <BrandButton v-bind:variant="'openid text'" v-bind:title="'OpenID'" />
            <BrandButton v-bind:variant="'stack-overflow text'" v-bind:title="'StackOverflow'" />
            <BrandButton v-bind:variant="'css3 text'" v-bind:title="'CSS3'" />
            <BrandButton v-bind:variant="'youtube text'" v-bind:title="'YouTube'" />
            <BrandButton v-bind:variant="'dribbble text'" v-bind:title="'Dribbble'" />
            <BrandButton v-bind:variant="'google-plus text'" v-bind:title="'Google+'" />
            <BrandButton v-bind:variant="'instagram text'" v-bind:title="'Instagram'" />
            <BrandButton v-bind:variant="'pinterest text'" v-bind:title="'Pinterest'" />
            <BrandButton v-bind:variant="'vk text'" v-bind:title="'VK'" />
            <BrandButton v-bind:variant="'yahoo text'" v-bind:title="'Yahoo'" />
            <BrandButton v-bind:variant="'behance text'" v-bind:title="'Behance'" />
            <BrandButton v-bind:variant="'dropbox text'" v-bind:title="'Dropbox'" />
            <BrandButton v-bind:variant="'reddit text'" v-bind:title="'Reddit'" />
            <BrandButton v-bind:variant="'spotify text'" v-bind:title="'Spotify'" />
            <BrandButton v-bind:variant="'vine text'" v-bind:title="'Vine'" />
            <BrandButton v-bind:variant="'foursquare text'" v-bind:title="'Forsquare'" />
            <BrandButton v-bind:variant="'vimeo text'" v-bind:title="'Vimeo'" />
          </p>
          <h6>Size Large <small>Add <code>size="lg"</code></small></h6>
          <p>
            <BrandButton v-bind:size="'lg'" v-bind:variant="'facebook text'" v-bind:title="'Facebook'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'twitter text'" v-bind:title="'Twitter'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'linkedin text'" v-bind:title="'LinkedIn'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'flickr text'" v-bind:title="'Flickr'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'tumblr text'" v-bind:title="'Tumblr'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'xing text'" v-bind:title="'Xing'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'github text'" v-bind:title="'Github'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'html5 text'"  v-bind:title="'HTML5'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'openid text'" v-bind:title="'OpenID'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'stack-overflow text'" v-bind:title="'StackOverflow'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'css3 text'" v-bind:title="'CSS3'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'youtube text'" v-bind:title="'YouTube'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'dribbble text'" v-bind:title="'Dribbble'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'google-plus text'" v-bind:title="'Google+'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'instagram text'" v-bind:title="'Instagram'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'pinterest text'" v-bind:title="'Pinterest'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'vk text'" v-bind:title="'VK'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'yahoo text'" v-bind:title="'Yahoo'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'behance text'" v-bind:title="'Behance'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'dropbox text'" v-bind:title="'Dropbox'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'reddit text'" v-bind:title="'Reddit'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'spotify text'" v-bind:title="'Spotify'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'vine text'" v-bind:title="'Vine'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'foursquare text'" v-bind:title="'Forsquare'" />
            <BrandButton v-bind:size="'lg'" v-bind:variant="'vimeo text'" v-bind:title="'Vimeo'" />

          </p>
        </b-card>
      </b-col><!--/.col-->
    </b-row><!--/.row-->
  </div>
</template>

<script>
import BrandButton from '../../components/BrandButton'
export default {
  name: 'brand-buttons',
  components: {
    BrandButton,
  }
}
</script>

<style scoped lang="css">
.btn {
  margin-bottom: 4px;
}
</style>
