<template>
  <main class="product">
		<div class="product-card">
			<div class="image">
				<div class="buttons">
					<div class="next"><button></button></div>
					<div class="prev"><button></button></div>
				</div>	
				<div class='zoom img' id='ex1'>
					<img src='../images/8.png' />
				</div>
			</div>
			<div class="container">
				<div class="product-name">Ave classic sweatshirt</div>
				<div class="reviews">
					<span class="stars">
						<img src="../images/icons/star_on.png" alt="">
						<img src="../images/icons/star_on.png" alt="">
						<img src="../images/icons/star_on.png" alt="">
						<img src="../images/icons/star_on.png" alt="">
						<img src="../images/icons/star_off.png" alt="">	
					</span>
					<span class="description">3 Review(s)</span>
					<div class="link">
						<a href="#">Add a Review</a>
					</div>
					<div class="share">
						<div>Share:</div>
						<div><a href="#"><img src="../images/icons/fc.png" alt=""></a></div>
						<div><a href="#"><img src="../images/icons/tw.png" alt=""></a></div>
						<div><a href="#"><img src="../images/icons/g+.png" alt=""></a></div>
						<div><a href="#"><img src="../images/icons/in.png" alt=""></a></div>
						<div><a href="#"><img src="../images/icons/e-mail.png" alt=""></a></div>
					</div>
				</div>	
				<div class="price">
					<div class="old-price"><div class="currency">£</div>107</div>
					<div class="new-price"><div class="currency">£</div>89.99</div>
				</div>
				<div class="about">
					<div class="">
						<span>Availability:</span> In stock
					</div>
					<div class="">
						<span>Product Code:</span> #499577
					</div>
					<div class="">
						<span>Tags:</span> 
						<a href="#">Classic,</a>
						<a href="#">Casual,</a>
						<a href="#">V-neck,</a>
						<a href="#">Loose</a>
					</div>
				</div>
				<div class="text">
					Donec sem lorem laoreet tempor un risus vitae, rutrum sodales nibh suspendisse est congue metus nunc, id viverra elit loreti rhoncus quis consecteur es. Donec pulvinar tempor lorem a pretium justo interdum.
					<li>Elasticated cuffs</li>
					<li>Casual fit</li>
					<li>100% Cotton</li>
					<li>Free shipping with 4 days delivery</li>
				</div>
				<div class="form">					
					<form action="#" method="post">
						<div class="block">							
							<div class="name">Colour</div>
							<select class="colors" id="selecttheme">
								<option value="0">Select Colour</option>
								<option value="1">Maroon</option>
								<option value="2">Green</option>
								<option value="3">Yellow</option>
								<option value="4">Blue</option>
								<option value="5">Red</option>
							</select>
						</div>
						<div class="block">							
							<div class="name">Size</div>
							<select id="selectvalue">
								<option value="0">Select Size</option>
								<option value="1">5</option>
								<option value="2">10</option>
								<option value="3">15</option>
								<option value="4">20</option>
								<option value="5">25</option>
							</select>
						</div>
						<div class="block">							
							<div class="name">QTY</div>
							<input type="number" id="tentacles" name="tentacles" placeholder="1" min="1" max="10">
						</div>
					</form>
				</div>	
				<div class="buttons">
					<button class="buy">Add to cart</button>
					<button class="like">add to lookbook</button>
					<button class="compare">Add to Compare</button>
				</div>	
			</div>
		</div>
		<div class="produt-item">
			<div class="menu">
				<ul>
					<li><a href="#">Description</a></li>
					<li><a href="#">Video</a></li>
					<li><a href="#">Size & Specs</a></li>
					<li><a href="#">Delivery & Returns</a></li>
					<li><a href="#">Reviews</a></li>
				</ul>
			</div>
			<section>
				<div class="title">Nunc egestas posuere enim, eu maximus erat posuere eget</div>
				<div class="text">Sed ut mi mollis, consequat nulla lacinia, hendrerit turpis. Nulla sapien magna, interdum quis pretium nec, pharetra at felis. Curabitur dictum sapien est, eget ultricies turpis porta vel. Nam suscipit nec lacus sed imperdiet. Vestibulum a purus risus. Nulla et dictum augue, nec efficitur mi. Nam sit amet pretium elit. Aliquam congue, ligula id vehicula vestibulum, orci ex vulputate lacus, ac malesuada elit dolor eget ex. Sed quis aliquet risus, ut cursus lectus. In eget lorem tellus.</div>
				<div class="text">Quisque eleifend varius nisi nec sagittis. Nulla ullamcorper imperdiet justo, ut venenatis purus lobortis ut. Nunc sagittis urna et hendrerit sodales. Nunc molestie risus nec fringilla lacinia. Nulla facilisi. Etiam neque velit, tristique eget sollicitudin eget, placerat at metus. Proin dictum lobortis velit, id suscipit orci faucibus ut. Aliquam erat volutpat. Vivamus feugiat justo in diam placerat, id dignissim elit auctor. Vestibulum scelerisque sem et lobortis ultricies. Morbi suscipit nulla urna. Suspendisse potenti. Nullam varius quam sed nisl dignissim, vel faucibus ipsum blandit. Vivamus at suscipit augue. Nam finibus gravida lorem eu viverra. Praesent rhoncus imperdiet ultricies. Nullam pretium cursus augue auctor vulputate. Quisque a convallis diam commodo eget diam id, eleifend dictum libero. Etiam varius, nisi vel dignissim sodales, enim dui posuere mauris, in aliquet lorem eros eget neque.</div>
			</section>
		</div>
	</main>
</template>
