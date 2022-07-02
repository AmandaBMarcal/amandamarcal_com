################################################################################################

Documentation for Zarius Theme Multipurpose One Page Template 

## AUTHOR ##

   "Zarius Theme Multipurpose One Page Template"  by Z99

   Demo: http://zariustheme.comlu.com/


################################################################################################

   Thank you for downloading this theme! I hope you enjoy it!

################################################################################################

## CSS ##

   The theme stylesheet is css/style.css. 
   If you want to make any changes, you can do it here or better to override it in custom.css so you can update the original theme stylesheet if an updated is released. 
   If you want to change colour theme, change the CSS path in the <head> to e.g. css/style.custom.css. 
   We have created Style.custom.css with explanation through code for further editing, if you need to change font size, color, background, photos...etc.

## JAVASCRIPT ##

   Apart from Bootstrap JS components majority of JS is located in /js/main.js. 
   If you want to make any js settings change, you can do it here.

## CREDITS ##

   - Botstrap 3.3.2 (http://getbootstrap.com)
   - Google Fonts - Lato, Raleway and Open Sans
   - Owl Carousel  (www.owlcarousel.owlgraphic.com)
   - Font Awesome  by @davegandy - http://fontawesome.io - @fontawesome
   - Animate.css (http://daneden.me/animate)
   - JQuery Count To (https://github.com/mhuggins/jquery-countTo)
   - Modernizr  ( http://modernizr.com)
   - Retina.js (Imulus, LLC)
   - Smooth-scroll by Chris Ferdinandi (http://github.com/cferdinandi/smooth-scroll)
   - WOW by Matthieu Aussaguel (http://mynameismatthieu.com/WOW/)
   - Photos - https://pixabay.com  and www.pexels.com (photos are free for commercial use)
   
## ABOUT THEME ##

   Zarius is a modern, simple, professional, responsive and easy to customize template built with Bootstrap framework.
   With Zarius - Multipurpose One Page Template you can create many unique style websites for different purposes. You can use this template for Business, Photography Studio,
   Portfolio, Personal presentation, Freelancers, Agency, Corporate, Product page, etc.

   Template is divided into section that can be easily edited/or removed from template if its not fit your needs. 

################################################################

######## This is step by step tutorial for you if you need to modificate template. ########

   ######### - Header/Home Section : ########
   
   	Open index.html and style.css file in text editor.
    
	## Edit text and icon ##
	<div class="content">
        <h1><strong><span class="color animated infinite fadeInUp">Welcome on Zarius Theme</span></strong></h1>
	    <h2>New and fresh design brought by our team.</h2>
		<a href="#text-intro" class="fa fa-angle-down data-scroll faa-pulse animated"></a>
    </div> 

    Instead of text between <h1> tags: "Welcome on Zarius Theme" write your own welcome message.   
	Instead of text between <h2> tags: "New and fresh design brought by our team" write your own sub-message. 
	The <a> tag is used to link from Header Section to Text Intro. If you want to change fa-angle-down icon choose another one from Font awesome icon set. 
	Also change the name of icon in style.css file:  
	    a.fa.fa-angle-down (a.fa.fa-new-icon)
	    a.fa.fa-angle-down:hover (a.fa.fa-new-icon:hover)
		
###################################################################

   ######## - Short Intro Text Section : ########

   	Open index.html and style.css file in text editor.
	
	## Edit text ##
	<div class="section-title text-center">
        <h1>We are Zarius Theme. </h1>
		<div class="line">
            <hr>
		</div>	
        <div class="clearfix"></div>
	</div>
	<div class="intro-text text-center">
	    <h3>We love designing and creating web themes, brands and all design you need. With specific skills and passion we bring you our best works.</h3>
    </div>
	
    Instead of text between <h1> tags: "We are Zarius Theme." write your own welcome message.   
	Instead of text between <h3> tags: "We love designing and creating web themes, brands..." write short text about your business.	
	
	## Edit image ##
    <div class="container">
	    <div class="row">
			<div class="col-md-12 team-photo">
				<img class="img-responsive" src="img/team.png" alt="">
			</div>
		</div>
	</div>
	
	In folder named Img add photo in .png format. Change image you want here: src="img/team.png" . - Example src="img/new-image.png"

###############################################################
	
   ######### - Call To Action Section : ########
    
	Open index.html and style.css file in text editor.
	
	## Edit text ##
    <div class="action-text">
        <h2>Do you want something new in everyday market? Stand out with us.</h2>
	</div>   
	
	Instead of text between <h2> tags: "Do you want something new in..." write your own message.   
	
	## Edit Button ##
	<div class="action-button">
		<a href="#contact" class="btn btn-custom btn-light pull-left">Hire Us</a>
    </div>
	
	This button is linked to contact section. If you want to link it to something else, for example Portfolio Section change href="#contact" to href="#works"
	Change text Hire Us into something else.

##############################################################
	
   ######## - Main Company Mission Section ########
    
	Open index.html and style.css file in text editor.
	
	## Edit text and icon ##
    <div class="feature-info">
	    <div class="feature-icon">
		    <i class="fa fa-bell-o faa-tada animated-hover"></i>
		</div>
		<div class="feature-content">
			<h2>Multi-Purpose</h2>
			<p>Et harum quidem rerum facilis est et expedita distinctio. Nam libero tempore, cum soluta nobis est eligen.</p>
		</div>
	</div>
	
    If you want to change feature-icon named fa-bell-o choose another one from Font awesome icon set. 
    Instead of text between <h2> tags: "Multi-Purpose" write your own text.  
	Instead of text between <p> tags: "Et harum quidem rerum facilis...." write your own text.  
	
	## Edit text and icon ##
	<div class="feature-info">
		<div class="feature-icon">
		    <i class="fa fa-comments-o faa-tada animated-hover"></i>
		</div>
		<div class="feature-content">
		    <h2>Creative Work</h2>
		    <p>Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numq.</p>
		</div>
	</div>
	
	If you want to change feature-icon named fa-comments-o choose another one from Font awesome icon set. 
    Instead of text between <h2> tags: "Creative Work" write your own text.  
	Instead of text between <p> tags: "Neque porro quisquam est...." write your own text.
	
	## Edit text and icon ##	
	<div class="feature-info">
		<div class="feature-icon">
		    <i class="fa fa-heart-o faa-tada animated-hover"></i>
		</div>
		<div class="feature-content">
		    <h2>Responsive Design</h2>
		    <p>Temporibus autem quibusdam et aut officiis debitis aut rerum necessitatibus saepe eveniet.</p>
		</div>
	</div>
	
	If you want to change feature-icon named fa-heart-o choose another one from Font awesome icon set. 
    Instead of text between <h2> tags: "Responsive Design" write your own text.  
	Instead of text between <p> tags: "Temporibus autem quibusdam et aut...." write your own text.

##############################################################
	
   ######## - Why Choose Us Section : ########

   Open index.html and style.css file in text editor.
   
   ## Edit image ##
    <div class="col-sm-6 col-md-6 nopadding">
		<div class="features-img">
			<img class="img-responsive" src="img/photo.png" alt="">
		</div>
	</div>
    
	In folder named Img add photo in .png format. Change image you want here: src="img/photo.png" . - Example src="img/new-image.png"
	
   ## Edit tabs name and icons ##
    <li class="active"><a class="icon-tab" data-toggle="tab" href="#wecare">WE CARE<i class="fa fa-heart"></i></a></li>
    <li><a class="icon-tab" data-toggle="tab" href="#webuild">WE BUILD<i class="fa fa-gavel"></i></a></li>
    <li><a class="icon-tab" data-toggle="tab" href="#wetake">WE TAKE<i class="fa fa-trophy"></i></a></li>
   
   Change text WE CARE into something else. If you want to change feature-icon named fa-heart choose another one from Font awesome icon set. 
   Change text WE BUILD into something else. If you want to change feature-icon named fa-gavel choose another one from Font awesome icon set. 
   Change text WE TAKE into something else. If you want to change feature-icon named fa-trophy choose another one from Font awesome icon set. 
   
   ## Edit tabs name and icons ##
    <div class="text-about">
	    <h2>Featured work</h2>
        <p>Creative project of Green design concept, specially made for our outstanding client.</p>
        <div class="featured-box one">
            <div class="box-1">
                <i class="fa fa-star-o faa-tada animated-hover"></i>
            </div>	
            <div class="box-2">
                <p>Proin iaculis purus consequat sem cure digni ssim. Donec porttitora entum suscipit aenean rhoncus.</p>                                
			</div>    
        </div>
        <div class="featured-box two">
            <div class="box-1">
                <i class="fa fa-star-o faa-tada animated-hover"></i>
            </div>	
            <div class="box-2">
                <p>Purus consequat sem cure digni ssim. Donec entum suscipit aenean rhoncus posuere odio in tincidunt. </p>
            </div>    
        </div>
        <div class="featured-box three">
            <div class="box-1">
                <i class="fa fa-star-o faa-tada animated-hover"></i>
            </div>	
            <div class="box-2">
                <p>Iaculis purus consequat sem cure digni ssim. Suscipit aenean rhoncus posuere odio in tincidunt. </p>
            </div>    
        </div>
	</div>
   
    Instead of text between <h2> tags: "Featured work" write your own text. 
    Instead of text between <p> tags: "Creative project of Green design conceps...." write your own text.	
    If you want to change feature-icon named fa-star-o choose another one from Font awesome icon set.
    Instead of text between <p> tags: "Proin iaculis purus consequat sem...." write your own text.
	
	<div class="actn-btn">
		<a href="#" class="btn btn-custom">Hire Us</a>
	</div>
	This button is linked to contact section. If you want to link it to something else, for example Portfolio Section change href="#contact" to href="#works"
	Change text Hire Us into something else.
	
	Do the same thing above for the following: <div id="webuild" class="tab-pane fade">
	                                           <div id="wetake" class="tab-pane fade">

	## Edit image ##
	<div class="text-img">
		<img class="img-responsive" src="img/screens.png" alt="">
	</div>
    
	In folder named Img add photo in .png format. Change image you want here: src="img/screens.png" . - Example src="img/new-image.png"
   
###########################################################   
   
   ######## - Top News Section ########
    
	Open index.html and style.css file in text editor.
	
	## Edit Text ##
    <div class="section-text text-center">
	    <h3><strong class="color">WE LOVE BUILDING</strong> -  Donec pharetra at tempus auctor. Morbi consectetur, quam rutrum rhoncus suscipit, mauris ligula vulputate ante, eget auctor quam felis at turpis. In rhoncus non nibh id pellentesque. Sed eu libero nibh. Aliquam accumsan diam ac nulla suscipit mattis.
	    <a href="#" class="arrow-link"><em>Read More</em><i class="fa fa-long-arrow-right"></i></a></h3>
    </div>
	
    Instead of text between <h3> tags: "WE LOVE BUILDING" write your own text.
	Instead of text between <h3> tags: "-  Donec pharetra at tempus...." write your own text.
	If you have external link for your company news enter here <a href="www.mynews.com" class="arrow-link">
	
	If you don't have external link simply delete following: <a href="#" class="arrow-link"><em>Read More</em><i class="fa fa-long-arrow-right"></i></a>
    Also from Style.css delete: .arrow-link {
                                    padding: 0 3px;
                                }
                                .arrow-link em {
                                    padding: 0 5px;
                                }
                                .arrow-link i{
                                    padding: 0 5px 0 0;
                                }
								
##########################################################
	
   ######## - Services Section : ########

   Open index.html and style.css file in text editor.
   
   ## Edit Text ##
   <div class="section-title text-center wow fadeIn" data-wow-duration="1000ms" data-wow-delay="300ms">
		<h1>Services we can offer to you</h1>
        <div class="line">				
            <hr>
        </div>
        <div class="clearfix"></div>
    </div>

    Instead of text between <h1> tags: "Services we can offer to you" write your own text.
	
	## Edit Text and icon ##
	<div class="col-xs-12 col-sm-6 col-md-4 service-box wow fadeInDown" data-wow-duration="1000ms" data-wow-delay="300ms">
        <div class="box service-icon">
            <i class="fa fa-eye faa-tada animated-hover"></i>
        </div>
        <div class="service-info">
            <h2>Brand Identity</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore</p>
        </div>
    </div>
   
   If you want to change service-icon named fa-eye choose another one from Font awesome icon set.
   Instead of text between <h2> tags: "Brand Identity" write your own text. 
   Instead of text between <p> tags: "Lorem ipsum dolor sit amet, consectetur...." write your own text.
   
   Do the same for the other service boxes as in example above.
   
###########################################################
   
   ######## - Features Counter Section : ########

   Open index.html and style.css file in text editor.
   
    ## Edit Text and icon ##
    <div class="col-sm-3 counter-content wow fadeIn" data-wow-duration="1000ms" data-wow-delay="500ms">
        <i class="fa fa-user"></i>
        <div><span class="timer" data-from="0" data-to="2344" data-speed="12000" data-refresh-interval="50"></span></div>
        <h2>Satisfied Clients</h2>
    </div>
    <div class="col-sm-3 counter-content wow fadeIn" data-wow-duration="1000ms" data-wow-delay="700ms">
        <i class="fa fa-desktop"></i>
        <div><span class="timer" data-from="0" data-to="200" data-speed="12000" data-refresh-interval="50"></span></div>                  
        <h2>Developed Projects</h2>
    </div> 
	<div class="col-sm-3 counter-content wow fadeIn" data-wow-duration="1000ms" data-wow-delay="900ms">
        <i class="fa fa-thumb-tack"></i>
        <div><span class="timer" data-from="0" data-to="6" data-speed="12000" data-refresh-interval="50"></span></div>                 
        <h2>Social Actions</h2>
    </div> 
	<div class="col-sm-3 counter-content wow fadeIn" data-wow-duration="1000ms" data-wow-delay="1100ms">
        <i class="fa fa-comment-o"></i>                    
        <div><span class="timer" data-from="0" data-to="52" data-speed="12000" data-refresh-interval="50"></span></div>
        <h2>Question Answered</h2>
    </div> 
	
	If you want to change counter icons named: fa-user
	                                           fa-desktop
											   fa-thumb-tack
											   fa-comment-o     choose another from Font awesome icon set.
    
	Instead of text between <h2> tags: "Satisfied Clients"
                                       "Developed Projects"
									   "Social Actions"
									   "Question Answered"	write your own text. 

############################################################									   
	
   ######## - About Team Section : ########
   
   Open index.html and style.css file in text editor.
   
   ## Edit Text ##
   <div class="section-title text-center wow fadeIn" data-wow-duration="1000ms" data-wow-delay="300ms">
        <h1>Our Winning Team</h1>
		<div class="line">
            <hr>
	    </div>	
        <div class="clearfix"></div>
	</div>
    
	Instead of text between <h1> tags: "Our Winning Team" write your own text.
   
   ## Edit Text, Images and icon ##
    <div class="about-member wow fadeInLeft" data-wow-duration="1000ms" data-wow-delay="300ms">
		<div class="member-image">
			<img src="img/team/1.jpg" alt="" class="img-responsive">
		</div>
		<div class="member-info">
		    <div class="member-name">
		       <h3>John Bourew</h3>
		       <h5>- lead manager -</h5>
		    </div>
		    <div class="social-icons">
			    <ul>
				   <li><a href="#" class="facebook"><i class="fa fa-facebook"></i></a></li>
				   <li><a href="#" class="twitter"><i class="fa fa-twitter"></i></a></li>
				   <li><a href="#" class="linkedin"><i class="fa fa-linkedin"></i></a></li>
			    </ul>
		    </div>
		</div>
    </div>
   
   In folder named Img find subfolder Team and add photo in .jpg format. Change image you want here: src="img/team/1.jpg" . - Example src="img/team/new-image.jpg"
   Instead of text between <h3> tags: "John Bourew" write your own text. 
   Instead of text between <h5> tags: "- lead manager -" write your own text.
   Enter your social networks address: <a href="facebook.com/mycompany" class="facebook"> (example).
   If you want to change social icons named: fa-facebook
	                                         fa-twitter
											 fa-linkedin   choose another from Font awesome icon set.
   
   Do the same for theother team members as in example above.
 
##########################################################
 
   ######## - Portfolio Section : ########
  
   Open index.html and style.css file in text editor.
   
   ## Edit Text ##
    <div class="quote-text">
        <h2><span class="color-text">Crafted with passion, made with love, brought by Zarius </span></h2>
	</div>
   
   Instead of text between <h2> tags: "Crafted with passion, made with love, brought by Zarius" write your own text. 
   
   ## Edit Images and Text ##
   <figure class="wow fadeInUp" data-wow-duration="1000ms" data-wow-delay="300ms">
		<img src="img/portfolio/img1.jpg" alt="">
	   	<figcaption>
	    	<div class="caption-content">
		    	<a href="#portfolioModal1" class="portfolio-link" data-toggle="modal">
                    <h2>Green Design</h2>
				    <h5>Find out more</h5>
			    </a>
	        </div>
		</figcaption>
	</figure>
	
	In folder named Img find subfolder Portfolio and add photo in .jpg format. Change image you want here: src="img/portfolio/img1.jpg" . - Example src="img/portfolio/new-image.jpg"
	Instead of text between <h2> tags: "Green Design" write your own text. 
    
    Do the same for the other portfolio content as in example above. 
	
#############################################################	

   ######## - Portfolio Modal : ########
   
   Open index.html and style.css file in text editor. Portfolio Modal Section is at the end of the index file.
   
   ## Edit Text and Images ##
    <div class="col-md-6">
		<div class="modal-body">
	        <h1>Project Name</h1>
            <div class="line">
                <hr>
            </div>
		    <p>Use this area to describe your project. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Est blanditiis dolorem culpa incidunt minus dignissimos deserunt repellat aperiam quasi sunt officia expedita beatae cupiditate, maiores repudiandae, nostrum, reiciendis facere nemo! Lorem ipsum dolor sit amet, consectetur adipisicing elit. Est blanditiis dolorem culpa incidunt minus dignissimos deserunt repellat aperiam quasi sunt officia expedita beatae cupiditate, maiores repudiandae, nostrum, reiciendis facere nemo!</p>
 		    <p>Use this area to describe your project. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Est blanditiis dolorem culpa incidunt minus dignissimos deserunt repellat aperiam quasi sunt officia expedita beatae cupiditate, maiores repudiandae, nostrum, reiciendis facere nemo! Lorem ipsum dolor sit amet, consectetur adipisicing elit. Est blanditiis dolorem culpa incidunt minus dignissimos deserunt repellat aperiam quasi sunt officia expedita beatae cupiditate, maiores repudiandae, nostrum, reiciendis facere nemo!</p>
		</div>
		<ul class="list-inline text-left">
            <li><strong>Date:</strong> January 2016</li>
            <li><strong>Client:</strong> RTD Company</li>
            <li><strong>Category:</strong> Graphic Design</li>
        </ul>
	</div>
	<div class="col-md-6">
        <img class="img-responsive" src="img/portfolio/img1-large.jpg" alt="">
	    <button type="button" class="btn btn-custom pull-right" data-dismiss="modal"><i class="fa fa-times"></i> Close Project</button>
	</div>
   
   Instead of text between <h1> tags: "Project Name" write your own text.
   Instead of text between <p> tags: "Use this area to describe your project..." write your own text.
   Instead of text between <li> tags: "January"
                                      "RTD Company"
                                      "Graphic Design"  write your own text.
   In folder named Img find subfolder Portfolio and add photo in .jpg format. Change image you want here: src="img/portfolio/img1-large.jpg" . - Example src="img/portfolio/new-image.jpg"
   
   Do the same for the other Portfolio Modals as in example above. 

################################################################   
   
   ######## - Testimonials Section : ########

   Open index.html and style.css file in text editor.

    ## Edit Text ##
    <div class="section-title text-center wow fadeIn" data-wow-duration="1000ms" data-wow-delay="300ms">
        <h1>Our clients’ testimonials</h1>
        <div class="line">
            <hr>
        </div>
    </div>

	Instead of text between <h1> tags: "Our clients’ testimonials" write your own text.

	## Edit Text and Images ##
	<div class="item client-box">   
        <div class="client-image col-xs-2">
		    <img alt="portfolio" src="img/team/2.jpg" width="100" class="img-circle img-responsive">
	    </div>
        <div class="client-text col-xs-10">
            <p>Maecenas scelerisque, eros nec consectetur molestie, metus dolor dapibus augue, sed fringilla dolor lacus sed ante. Aenean et lectus orci. Praesent eu ornare neque, nec luctus neque. Sed malesuada ligula quis est pharetra, sed sollicitudin sapien venenatisess.</p>      
            <span class="client-name"><strong>Pauline Heart</strong> - <em>Social ATR</em></span>
        </div>
	</div>

	In folder named Img find subfolder Team and add photo in .jpg format. Change image you want here: src="img/team/2.jpg" . - Example src="img/team/new-image.jpg"
	Instead of text between <p> tags: "Maecenas scelerisque, eros nec..." write your own text.
	Instead of text between <span> : "Pauline Heart"  and  "Social ATR" write your own text.
	
	Do the same for the other Client's testimonials as in example above.
	
################################################################	
   
   ######## - Price Section : ########

   Open index.html and style.css file in text editor.

   ## Edit Text ##
    <div class="section-title text-left color wow fadeInLeft" data-wow-duration="1000ms" data-wow-delay="300ms">
	    <h1>Suitable Price Plans</h1>
        <div class="line">
            <hr>
        </div>
	</div>
	<div class="section-text text-left wow fadeInUp" data-wow-duration="1000ms" data-wow-delay="300ms">
        <p>Donec pharetra turpis at tempus auctor. Morbi consectetur, quam rutrum rhoncus suscipit, mauris ligula vulputate ante, eget auctor quam felis at turpis. In rhoncus non nibh id pellentesque. Sed eu libero nibh. Aliquam accumsan diam ac nulla suscipit mattis. Phasellus id interdum neque</p>
        <p>Sellus nec pulvinar purus, vitae elementum velit. Integer felis mauris, efficitur id lectus et, feugiat pulvinar ipsum. Mauris a tellus.</p>
	</div>

	Instead of text between <h1> tags: "Suitable Price Plans" write your own text.
	Instead of text between <p> tags: "Donec pharetra turpis at tempus a...." write your own text.

	## Edit Price tabs ##
	<div class="panel-heading" role="tab">
        <a data-toggle="collapse" data-parent="#accordion" href="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
            <h2><i class="fa fa-home"></i> Basic Plan</h2><h4> - Perfect for small business</h4>
        </a>
    </div>
    <div id="collapseOne" class="panel-collapse collapse" role="tabpanel">
        <div class="panel-body">
            <div class="clearfix price"><div class="pull-left">Service One</div><span class="pull-right">$ 10.00</span></div>
            <div class="clearfix price"><div class="pull-left">Service Two</div><span class="pull-right">$ 10.00</span></div>
            <div class="clearfix price"><div class="pull-left">Service Three</div><span class="pull-right">$ 10.00</span></div>
            <div class="clearfix price"><div class="pull-left"><strong>Total Price</strong></div><span class="pull-right">$ 30.00</span></div>
			<div class="clearfix price"><div class="pull-right"><a href="#"><strong>BUY PLAN</strong></a></div></div>
		</div>
    </div>

	Instead of text between <h2> tags: "Basic Plan" and "Perfect for small business" write your own text.
	If you want to change social icons named: fa-home choose another from Font awesome icon set.
	Instead of text : "Service One"   and  "$ 10.00"
	                  "Service Two"   and  "$ 10.00"
					  "Service Three" and  "$ 10.00"
	                  "Total Price"   and  "$ 30.00"
					                      "BUY PLAN"   	write your own text.
	
	Do the same for the other Panels as in example above.

#########################################################	
   
   ######## - Top Clients Section : ########

   Open index.html and style.css file in text editor.
   
   ## Edit Images ##
    <div class="item">
        <img src="img/client/01.png" alt="">
    </div>

    In folder named Img find subfolder Client and add photo in .png format. Change image you want here: src="img/client/01.png" . - Example src="img/client/new-image.png"
    
	Do the same for the other Clients images as in example above.

##########################################################
   
   ######## - New On Blog/News Posts Section : ########
   
   Open index.html and style.css file in text editor.
   
   ## Edit Text ##
   <div class="section-title text-center wow fadeIn" data-wow-duration="1000ms" data-wow-delay="300ms">
        <h1>New Blog Posts</h1>
        <div class="line">
            <hr>
        </div>
        <div class="clearfix"></div>
    </div>
   
   Instead of text between <h1> tags: "New Blog Posts" write your own text.
   
   ## Edit Text and Images ##
    <div class="blog-box wow fadeInLeft" data-wow-duration="1000ms" data-wow-delay="300ms">
        <img src="img/blog1.jpg" alt="">
        <h2>Broker advices</h2>
		<h6><span class="pull-left"></span>23.01.2016 <strong><span class="name pull-right">by Daren F.</span> </strong> </h6>
        <p>Rea in omnes sententiae repudiandae, ius cu oratio voluptatum. Cu sonet vocent delicata his. Id quo liber feugiat adipisci case...</p>
        <a href="#home" class="btn btn-custom">READ</a>
	</div>
	
   In folder named Img and add photo in .jpg format. Change image you want here: src="img/blog1.jpg" . - Example src="img/new-image.jpg"
   Instead of text between <h2> tags: "Broker advices" write your own text.
   Instead of text between <h6> tags: "23.01.2016" and "by Daren F." write your own text.
   Instead of text between <p> tags: "Rea in omnes sententiae repudiandae....." write your own text.
   If you have external link for your company blog enter it here <a href="www.myblog.com" class="btn btn-custom">READ</a>
   
   Do the same for the other Blog Posts as in example above.
 
#############################################################

   ######## - Motivation Quote Section : ########

   Open index.html and style.css file in text editor.

   ## Edit Text ##
    <div class="quote-text">
       <h2>Small opportunities are often the beginning of great enterprises !</h2>
    </div>
 
    Instead of text between <h2> tags: "mall opportunities are often the beginning of great enterprises !" write your own text

#############################################################
   
   ######## - Footer Section : ########
   
   Open index.html and style.css file in text editor.
   
   ## Edit Text and Images ##
   
   <div class="footer-widget contact-widget">
        <h2><img src="img/zarius.png" class="img-responsive" alt="ZARIUS" /></h2>
		<div class="contact-info">
            <ul class="list-unstyled">
				<li><span class="fa fa-home"></span> 2400 South Avenue A, 765365 San Antonio</li>
                <li><span class="fa fa-phone"></span> +928 336 2000 / +742 524 24 525 </li>
                <li><span class="fa fa-envelope"></span> someone@yoursite.com</li>
                <li><span class="fa fa-globe"></span> www.sitename.com</li>
            </ul>
		</div>	
	</div>
   
   In folder named Img and add photo in .png format. Change image you want here: src="img/zarius.png" . - Example src="img/new-image.png"
   If you want to change social icons named: fa-home
	                                         fa-phone
											 fa-envelope
											 fa-globe    choose another from Font awesome icon set.
   
   Instead of text : "S2400 South Avenue A, 765365 San Antonio"
	                 "+928 336 2000 / +742 524 24 525"
					 "someone@yoursite.com"
	                 "www.sitename.com"   	write your own text.
					 
	## Edit Icons ##				 
	<div class="footer-widget social-widget">
        <ul class="social-icons">
            <li>
                <a class="facebook" href="#"><i class="fa fa-facebook"></i></a>
            </li>
            <li>
                <a class="twitter" href="#"><i class="fa fa-twitter"></i></a>
            </li>
            <li>
                <a class="google" href="#"><i class="fa fa-google-plus"></i></a>
            </li>
            <li>
                <a class="linkdin" href="#"><i class="fa fa-linkedin"></i></a>
            </li>
            <li>
                <a class="tumblr" href="#"><i class="fa fa-tumblr"></i></a>
            </li>
            <li>
                <a class="instgram" href="#"><i class="fa fa-instagram"></i></a>
            </li>
        </ul>
    </div>			
    
	Enter your social networks address: <a class="facebook" href="facebook.com/mycompany"> (example).
    If you want to change social icons named: fa-facebook
	                                          fa-twitter
											  fa-google-plus
											  fa-linkedin   
											  fa-tumblr
											  fa-instagram  choose another from Font awesome icon set.	
	
	## Edit Text ##
    <div class="footer-widget mail">
        <h2>Get in touch</h2>
		<p>Please join our mailing list to stay informed about our company news and products. We would happily share big news with our customers.</p>
        <p>Leave us your e-mail adress. Stay up with fresh news!</p>
		<form class="subscribe">
            <input type="text" placeholder="mail@example.com">
            <input type="submit" class="btn btn-footer" value="Send">
        </form>
    </div>
    	
	Instead of text between <h2> tags: "Get in touch" write your own text.
    Instead of text between <p> tags: "Please join our mailing list to...." write your own text.	
   
   ## Edit Text ##
   <div class="footer-widget twitter-widget">
       <h2>Twitter Feed</h2>
       <ul>
           <li>
                <p><a href="#">@ZRSTheme</a> Lorem ipsum dolor et, consectetur adipiscing eli.<span>28 February 2014</span></p>
           </li>
           <li>
                <p><a href="#">@ZRSTheme</a> Lorem ipsum dolor et, consectetur adipiscing eli.An Fusce eleifend aliquet nis application.<span>26 February 2014</span></p>
           </li>
           <li>
                <p><a href="#">@ZRSTheme</a> Lorem ipsum dolor et, consectetur adipiscing eli.<span>26 February 2014</span></p>
           </li>
        </ul>
    </div>
	
	Instead of text between <h2> tags: "Twitter Feed" write your own text.
    Instead of text between <p> tags: "@ZRSTheme"  and  "Lorem ipsum dolor et, consectetur...."  and  "28 February 2014" write your own text.
	
   ## Edit Text ##
    <div class="col-md-12 text-center">
        <p>&copy; 2016 Zarius - All Rights Reserved <a href="http://www.yourcompany.com">YourCompany</a> </p>
    </div>
   
   Instead of text between <p> tags: "2016 Zarius - All Rights Reserved" write your own text.
   Instead of link between <a> tags: "http://www.yourcompany.com" write your own text.
   Instead of text between <a> tags: "YourCompany" write your own text.


