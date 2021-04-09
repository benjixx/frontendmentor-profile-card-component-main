<div class="profile">
	<img class="avatar" src="/image-victor.jpg" alt="Victor Crest" />
	<div class="person">
		<span class="person-name">Victor Crest</span> <span class="person-age">26</span>
	</div>
	<div class="location">London</div>
	<div class="stats">
		<div class="stat">
			<div class="stat-count">80K</div>
			<div class="stat-name">Followers</div>
		</div>
		<div class="stat">
			<div class="stat-count">803K</div>
			<div class="stat-name">Likes</div>
		</div>
		<div class="stat">
			<div class="stat-count">1.4K</div>
			<div class="stat-name">Photos</div>
		</div>
	</div>
</div>

<style>
	.profile {
		font-size: 18px;

		width: 350px;
		margin: 0 auto;
		background: url(/bg-pattern-card.svg) no-repeat, white;

		border-radius: 8px;

		text-align: center;

		box-shadow: 0 2px 4px rgba(0, 0, 0, 0.05);
	}

	.avatar {
		margin-top: 86px;
		border: 6px solid white;
		border-radius: 50%;
	}

	.person {
		padding-top: 20px;
		padding-bottom: 10px;
	}

	.person-age {
		margin-left: 0.3em;
	}

	.location {
		font-size: 16px;
		padding-bottom: 25px;
	}

	.stats {
		padding: 25px;
	}

	.stats {
		border-top: 0.2px solid hsl(0, 0%, 90%);
		display: flex;
		justify-content: space-around;
	}

	.person-age,
	.location,
	.stat-name {
		color: hsl(0, 0%, 59%);
	}

	.stat-name {
		margin-top: 5px;
		font-size: 11px;
		letter-spacing: 0.08rem;
	}

	.person-name,
	.stat-count {
		font-weight: bold;
	}
</style>
