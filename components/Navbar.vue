<template>
	<header>
		<div class="white-top-container">
			<div class="white-left-links">
				<NuxtLink to="/">
					<img src="/grey-logo.svg" alt="rogue logo" class="grey-logo" />
				</NuxtLink>
				<p class="left-top-links">USA</p>
				<p class="left-top-links">APO Store</p>
			</div>
			<div class="white-right-links">
				<p class="right-top-links">Gift Cards</p>
				<p class="right-top-links">Contact Us</p>
				<p class="right-top-links">Order Status</p>
				<p class="right-top-links">Live Chat</p>
			</div>
		</div>
		<div class="black-top-container">
			<NuxtLink to="/">
				<img src="/white-logo.svg" alt="rogue logo" class="white-icon" />
			</NuxtLink>
			<div class="middle-black-container">
				<div class="input-container">
					<input type="text" class="navbar-input" placeholder="Search" />
					<img src="/search-icon.png" alt="search icon" class="search-icon" />
				</div>
				<div class="ad-container">
					<div class="red-ad">DAILY SHIPPING DEALS ></div>
					<div>
						<span class="free-shipping">FREE SHIPPING</span> ON SELECT ITEMS
						<div class="shop-now">Shop Now</div>
					</div>
				</div>
			</div>
			<div class="login-cart-container">
				<div class="login-container">
					<img src="/profile-icon.png" alt="login icon" class="profile-icon" />
					<div>Login</div>
				</div>
				<div class="cart-container">
					<img src="/cart.png" alt="cart icons" class="cart-icon" />
					<div class="cart-state">0</div>
				</div>
			</div>
		</div>
		<div class="grey-strip-container">
			<div class="shop-link">
				SHOP
				<span class="carrot">^</span>
			</div>
			<div class="gear-link-container">
				<p class="gear-links">Crossfit Equipment</p>
				<p class="gear-links">New Gear</p>
				<p class="gear-links">BARBELLS</p>
				<p class="gear-links">PLATES</p>
				<p class="gear-links">RIGS & RACKS</p>
				<p class="gear-links">SHOES</p>
				<p class="gear-links">APPAREL</p>
				<p class="gear-links">3 SHIPS FREE</p>
				<p class="gear-links">ZEUS</p>
				<p class="gear-links">FEATURED GEAR</p>
			</div>
			<div class="deal-link">Deals</div>
		</div>
		<div class="black-bottom-container">
			<img src="/inv-logo.png" alt="invitational logo" />
			<NuxtLink to="/livestream" class="link">
				<div class="ticket-container">
					<div class="ticket-sale">TICKETS ON SALE NOW</div>
					<div class="date">October 27 - 28, 2023</div>
				</div>
			</NuxtLink>
			<div class="ticket-btn">Buy Tickets</div>
		</div>
	</header>
</template>

<style scoped>
.white-top-container {
	margin: 0.75em 0;
	background-color: white;
	display: flex;
	flex-wrap: wrap;
	justify-content: space-between;

	.white-left-links {
		display: flex;
		justify-content: center;
		align-items: center;
		margin-left: 9.5em;
	}

	.left-top-links:hover,
	.right-top-links:hover {
		text-decoration: underline;
		cursor: pointer;
	}
	.white-right-links {
		display: flex;
		justify-content: center;
		align-items: center;
		margin-right: 9.5em;
	}

	.right-top-links {
		margin: 0 1em;
	}

	.left-top-links {
		margin: 0 1em;
	}

	.grey-logo {
		height: 0.85em;
		cursor: pointer;
	}
}

.black-top-container {
	height: 7em;
	display: flex;
	align-items: center;
	justify-content: space-around;
	flex-wrap: wrap;
	background-color: black;
	color: white;

	.login-cart-container {
		display: flex;
	}

	.middle-black-container {
		width: 50em;

		display: flex;
		justify-content: center;
		align-items: center;

		.input-container {
			position: relative;
			min-height: 2.5em;
			width: 100%;
			margin-right: 3em;
			.search-icon {
				position: absolute;
				bottom: 35%;
				left: 95%;
				height: 1em;
			}
			.navbar-input {
				height: 2.5em;
				width: 100%;
				min-width: 300px;
				padding-left: 1em;
				font-size: 1rem;
			}
		}

		.ad-container {
			min-width: 17em;
		}

		.red-ad {
			width: 13em;
			background-color: red;
			font-weight: 100;
			cursor: pointer;
		}

		.free-shipping {
			color: red;
		}

		.shop-now {
			text-decoration: underline;
			cursor: pointer;
		}
	}

	.white-icon {
		cursor: pointer;
	}

	.login-container {
		display: flex;
		align-items: center;
		justify-content: center;
		margin-right: 0.5em;
		cursor: pointer;

		.profile-icon {
			height: 1.25em;
			margin-right: 0.25em;
		}
	}
	.cart-container {
		display: flex;
		justify-content: center;
		align-items: center;
		margin-left: 0.55em;
		cursor: pointer;

		.cart-icon {
			height: 1.5em;
		}

		.cart-state {
			display: flex;
			justify-content: center;
			align-items: center;
			margin-left: 0.25em;
		}
	}
}

.grey-strip-container {
	height: 3em;
	background-color: #333333;
	color: white;

	display: flex;
	align-items: center;
	justify-content: center;

	.shop-link {
		padding: 1em;
		font-weight: 900;
		background-color: #e30000;
		border-radius: 5%;
		cursor: pointer;
	}

	.carrot {
		display: inline-block;
		transform: rotate(180deg);
	}
	.gear-link-container {
		display: flex;
	}

	.gear-links {
		margin: 0px 1.5em;
		cursor: pointer;
		font-weight: bold;
	}

	.gear-links:hover {
		font-weight: bold;
		color: red;
	}

	.deal-link {
		padding: 1em;
		font-weight: 900;
		background-color: #e30000;
		border-radius: 5%;
		cursor: pointer;
	}
}

.black-bottom-container {
	background-color: black;
	color: white;

	display: flex;
	align-items: center;
	justify-content: space-around;

	.link {
		text-decoration: none;
		color: inherit;
	}

	.ticket-container {
		display: flex;
		justify-content: center;
		align-items: center;
		cursor: pointer;

		.ticket-sale {
			font-size: 2.5rem;
			font-weight: 800;
		}

		.date {
			margin: 0 1.5em;
			font-weight: 800;
		}
	}

	.ticket-btn {
		padding: 1em;
		font-weight: 900;
		background-color: #e30000;
		border-radius: 5%;
		cursor: pointer;
	}

	.ticket-btn:hover {
		background-color: #ff0202;
	}
}

@media (max-width: 1000px) {
	.white-top-container {
		justify-content: center;

		.white-left-links {
			/* margin-left: 0; */
			margin: 1em 0;
		}

		.white-right-links {
			margin-right: 0;
		}
	}

	.black-top-container {
		height: 100%;
		padding-top: 1em;
		flex-wrap: wrap;
		.middle-black-container {
			flex-wrap: wrap;
			margin: 1em 0;
		}

		.input-container {
			margin: 0 1em;
			flex-wrap: wrap;
		}

		.ad-container {
			flex-wrap: wrap;
			padding: 1em 0;
		}

		.login-cart-container {
			margin-bottom: 1em;
		}
	}

	.grey-strip-container {
		display: none;
		/* height: 100%;
		flex-wrap: wrap;

		.gear-link-container {
			flex-wrap: wrap;
			justify-content: center;
			align-items: center;
			gap: 1em;
			margin: 1em 0;
		}

		.shop-link {
			order: 1;
			margin: 1em 1em;
		} */
	}

	.black-bottom-container {
		display: none;
		/* flex-wrap: wrap;
		justify-content: center;
		padding: 1em 1em; */
	}
	/* .ticket-btn {
		margin: 1em;
	} */
}

@media (max-width: 1800px) {
	.grey-strip-container {
		height: 100%;
		flex-wrap: wrap;

		.gear-link-container {
			flex-wrap: wrap;
			justify-content: center;
			align-items: center;
			gap: 1em;
			margin: 1em 0;
		}

		.shop-link {
			order: 1;
			margin: 1em 1em;
		}
	}
}
</style>
