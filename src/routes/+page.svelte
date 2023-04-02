<script>
</script>

<div class="title">404 Not Found</div>

<div class="body">
	<img class="img" src="Scarecrow.png" alt="scarecrow" />
	<div class="content">
		<div class="upper">
			<div class="heading">I have bad news for you</div>
			<div class="description">
				The page you are looking for might be removed or is temporarily unavailable
			</div>
		</div>

		<button class="button">Back to homepage</button>
	</div>
</div>

<div class="footer">
	created by <span style="font-weight: 700;text-decoration: underline;">DarkTXYZ</span> - devChallenges.io
</div>

<style>
	@import url('https://fonts.googleapis.com/css2?family=Space+Mono:wght@400;700&display=swap');
	@import url('https://fonts.googleapis.com/css2?family=Inconsolata:wght@700&display=swap');
	@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@500;700&display=swap');

	.title {
		position: absolute;
		width: 133px;
		height: 25px;
		left: 77px;
		top: 40px;

		font-family: Inconsolata;
		font-size: 24px;
		font-weight: 700;
		line-height: 25px;
		letter-spacing: -0.08em;
		text-align: left;
	}

	.body {
		height: calc(100vh - 40px - 24px - 14px);
		width: calc(100vw - 77px - 77px);

		padding-left: 77px;
		padding-right: 77px;
		padding-top: 40px;

		display: flex;
		flex-direction: row;
		justify-content: center;
		align-items: center;

		gap: 120px;
	}

	.img {
		height: 447.42px;
		width: 539.22px;
	}

	.content {
		display: flex;
		flex-direction: column;
		justify-content: start;
		gap: 64px;
	}

	.upper {
		display: flex;
		flex-direction: column;
		gap: 36px;
	}

	.heading {
		width: 586px;
		height: 190px;

		font-family: 'Space Mono';
		font-style: normal;
		font-weight: 700;
		font-size: 64px;
		line-height: 95px;
		letter-spacing: -0.035em;

		color: #333333;
	}

	.description {
		height: 108px;
		width: 381px;

		font-family: 'Space Mono';
		font-style: normal;
		font-weight: 400;
		font-size: 24px;
		line-height: 36px;
		letter-spacing: -0.035em;

		color: #4f4f4f;
	}

	.button {
		width: 216px;
		height: 68px;

		font-family: 'Space Mono';
		font-style: normal;
		font-weight: 700;
		font-size: 14px;
		line-height: 21px;

		letter-spacing: -0.035em;
		text-transform: uppercase;
		color: #ffffff;
		background: #333333;
	}

	.footer {
		position: absolute;

        width: 287px;
        height: 17px;
        left: calc(50% - 287px/2);
        bottom: 24px;

		text-align: center;


		font-family: 'Montserrat';
		font-style: normal;
		font-weight: 500;
		font-size: 14px;
		line-height: 17px;

		color: #bdbdbd;
	}

	@media only screen and (max-width: 1270px) {
		/* .page {
			display: flex;
			flex-direction: column;
			justify-content: center;
			align-items: center;
		} */

		.title {
			left: 24px;
			top: 20px;
		}

		.body {
			margin: 0px;
			padding: 0px;

            width: 100vw;
            height: calc(100vh - 24px - 7px - 20px - 12px);

			display: flex;
			flex-direction: column;
			justify-content: center;
			align-items: center;

			gap: 60px;
		}

		.img {
			height: 238px;
			width: 286px;
		}

		.content {
			display: flex;
			flex-direction: column;
			justify-content: start;
			gap: 66px;
		}

		.upper {
			display: flex;
			flex-direction: column;
			gap: 30px;
		}

		.heading {
			width: 350px;
			height: 142px;
			font-size: 48px;
			line-height: 71px;
		}

		.description {
			width: 328px;
			height: 81px;

			font-size: 18px;
			line-height: 27px;
		}
	}
</style>
