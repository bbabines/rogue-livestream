<template>
	<footer>
		<div class="footer-top">
			<div class="footer-left">
				<div class="footer-link-container">
					<p class="footer-title">ABOUT US</p>
					<p class="footer-links">The Rogue Way</p>
					<p class="footer-links">Jobs</p>
					<p class="footer-links">#yourrogue</p>

					<p class="footer-title">SHOPPING</p>
					<p class="footer-links">Retail Store</p>
					<p class="footer-links">Brands</p>
					<p class="footer-links">Gift Registry</p>
				</div>

				<div class="footer-link-container">
					<p class="footer-title">CUSTOMER SERVICE</p>
					<p class="footer-links">Customer Quotes</p>
					<p class="footer-links">Checkout FAQ</p>
					<p class="footer-links">Track Your Order</p>
					<p class="footer-links">Returns & Cancellations</p>
					<p class="footer-links">Shipping</p>
					<p class="footer-links">Product Policies</p>
					<p class="footer-links">Warranty Information</p>
					<p class="footer-links">Suggestion Box</p>
					<p class="footer-links">Report Website Issue</p>
					<p class="footer-links">Customer Survey</p>
					<p class="footer-links">Contact Us</p>
				</div>

				<div class="footer-link-container">
					<p class="footer-title">POLICIES & NOTICES</p>
					<p class="footer-links">Recall Information</p>
					<p class="footer-links">Privacy Policy</p>
					<p class="footer-links">Terms of Use</p>
					<p class="footer-links">Accessibility</p>

					<p class="footer-title">OTHER INFO</p>
					<p class="footer-links">Affiliates</p>
					<p class="footer-links">Rogue Financing</p>
					<p class="footer-links">GSA Contract Info</p>
					<p class="footer-links">Distribution</p>
				</div>

				<div class="footer-link-container">
					<p class="footer-title">OTHER WEBSITES</p>
					<p class="footer-links">Rogue Invitational</p>
					<p class="footer-links">Rogue Challenges</p>
					<p class="footer-links">Rogue Athletes</p>
					<p class="footer-links">The Rogue Blog</p>
					<p class="footer-links">The Rogue Gym</p>
					<p class="footer-links">Rogue Equipped Events</p>
					<p class="footer-links">Garage Gyms</p>
					<p class="footer-links">The index</p>
					<p class="footer-links">ZEUS</p>

					<p class="footer-title">CONTACT US</p>
					<p class="footer-links">(614) 358-6190</p>
					<p class="footer-links">Fax: (614) 340-7206</p>
					<div class="footer-link-addy">
						<p class="footer-links"><strong> Rogue Fitness HQ </strong></p>
						<p class="footer-links">545 E 5th Ave.</p>

						<p class="footer-links">Columbus, OH 43201</p>
					</div>
				</div>
			</div>

			<div class="footer-right">
				<div class="connect-app-container">
					<div>CONNECT</div>
					<div>APP</div>
				</div>
				<div>
					<img src="/socials.png" alt="social icons" class="social-icons" />
				</div>
				<div class="newsletter-container">
					<p class="newsletter-title">NEWSLETTER SIGNUP</p>
					<p class="newsletter-desc">
						Sign up for our Newsletter with Rogue News and Product Releases.
					</p>
					<input type="text" placeholder="Email" class="newsletter-input" />
					<p class="newsletter-terms">
						By singing up, you agree to Rogue's
						<span class="underline-terms">Privacy Policy </span>,
						<span class="underline-terms">Terms of Use</span>, and
						<span class="underline-terms">Return Policy</span>
					</p>
				</div>
			</div>
		</div>

		<div class="footer-bottom">
			<p class="footer-logo"><span class="red-logo-text">Rogue</span>Fitness</p>
			<p class="copyright">@ 2010-2023 Rogue Fitness. All Rights Reserved</p>
		</div>
	</footer>
</template>

<style scoped>
footer {
	color: white;
	background-color: black;

	display: flex;
	flex-direction: column;
	justify-content: center;
	align-items: center;
}

.footer-top {
	display: flex;
	align-items: start;
	margin: 2em 0;
}

.footer-left {
	margin-right: 1em;
	gap: 2em;
	display: flex;
	.footer-title {
		font-weight: 800;
		margin-bottom: 1em;
		margin-top: 1em;
	}

	.footer-links {
		font-size: 0.85rem;
		font-weight: 100;
		color: #849393;
		margin: 0.5em 0;
		cursor: pointer;
		margin-top: 1em;
	}

	.footer-links:hover {
		color: white;
	}

	.footer-link-addy {
		margin-top: 1em;
	}
}

.footer-right {
	width: 35%;
	margin-left: 1em;

	.connect-app-container {
		width: 15.5em;
		margin-left: 1em;
		display: flex;
		justify-content: space-between;
	}

	.social-icons {
		width: 68%;
		cursor: pointer;
	}

	.newsletter-container {
		margin-left: 1em;
	}

	.newsletter-title {
		margin-bottom: 1em;
	}

	.newsletter-desc {
		color: #849393;
		font-size: 0.85rem;
		margin-bottom: 1em;
	}

	.newsletter-input {
		height: 3em;
		width: 100%;
		padding-left: 1em;
		margin-bottom: 1em;
	}

	.newsletter-terms {
		font-size: 0.85rem;
	}

	.underline-terms {
		color: lightgray;
		text-decoration: underline;
		cursor: pointer;
	}

	.underline-terms:hover {
		color: grey;
	}
}

.footer-bottom {
	width: 100%;
	display: flex;
	flex-direction: column;
	justify-content: center;
	align-items: center;
	margin-top: 0;
	margin-bottom: 2em;

	.footer-logo {
		letter-spacing: 1px;
		font-weight: bold;
		font-size: 1.25rem;
		margin-bottom: 1.5em;

		.red-logo-text {
			color: red;
		}
	}

	.copyright {
		color: grey;
	}
}

@media (max-width: 1000px) {
	.footer-top {
		flex-wrap: wrap;
		margin: 0 1em;
	}
	.footer-right {
		margin: 0 2em;
		width: 100%;

		.connect-app-container {
			margin-left: 2em;
		}
	}
}
</style>
