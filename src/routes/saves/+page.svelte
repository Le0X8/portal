<script lang="ts">
	function saveUrl(name: string) {
		return `https://cdn.leox.dev/portal/saves/${name}.sav`;
	}
</script>

<svelte:head>
	<title>Savegames</title>
</svelte:head>

<h1>Savegames</h1>

<p class="text-xl font-bold text-red-600 uppercase underline">Major Spoiler alert!</p>

<p>
	If you already have played through both games and want to go back to a specific test chamber or
	area, you can download all savegames here.
</p>

<p>
	It depends on which platform you are playing on where to put the save files, but generally the
	locations are inside the steam folder.
</p>

<ul>
	<li>
		<b>Portal:</b>
		steamapps/common/Portal/portal/save/
	</li>
	<li>
		<b>Portal 2:</b>
		steamapps/common/Portal 2/portal2/SAVE/&lt;SOME ID&gt;/
	</li>
</ul>

<h2>Portal</h2>

<ul>
	<li>
		<b>Chamber 0</b> (Introduction)
		<ul>
			<li><a href={saveUrl('portal/c0')}>Skip introduction cutscene</a></li>
		</ul>
	</li>
	<li><a href={saveUrl('portal/c1')}><b>Chamber 1</b></a> (Multiple Portals)</li>
	<li><a href={saveUrl('portal/c2')}><b>Chamber 2</b></a> (Blue Portal Gun)</li>
	<li><a href={saveUrl('portal/c3')}><b>Chamber 3</b></a></li>
	<li>
		<a href={saveUrl('portal/c4')}><b>Chamber 4</b></a>
	</li>
	<li><a href={saveUrl('portal/c5')}><b>Chamber 5</b></a> (Multiple Cubes)</li>
	<li><a href={saveUrl('portal/c6')}><b>Chamber 6</b></a> (High Energy Pellets)</li>
	<li><a href={saveUrl('portal/c7')}><b>Chamber 7</b></a> (Unstationary Scaffold)</li>
	<li><a href={saveUrl('portal/c8')}><b>Chamber 8</b></a> (Goo)</li>
	<li><a href={saveUrl('portal/c9')}><b>Chamber 9</b></a> ("Impossible" Test)</li>
	<li>
		<b>Chamber 10</b> (Flinging)
		<ul>
			<li><a href={saveUrl('portal/c10')}>Room 1</a></li>
			<li><a href={saveUrl('portal/c10-room2')}>Room 2</a></li>
			<li><a href={saveUrl('portal/c10-room3')}>Room 3</a></li>
		</ul>
	</li>
	<li><a href={saveUrl('portal/c11')}><b>Chamber 11</b></a> (Blue and Orange Portal Gun)</li>
	<li><a href={saveUrl('portal/c12')}><b>Chamber 12</b></a></li>
	<li><a href={saveUrl('portal/c13')}><b>Chamber 13</b></a></li>
	<li><a href={saveUrl('portal/c14')}><b>Chamber 14</b></a> (Long Room)</li>
	<li>
		<b>Chamber 15</b>
		<ul>
			<li><a href={saveUrl('portal/c15')}>Room 1</a></li>
			<li><a href={saveUrl('portal/c15-room2')}>Room 2</a></li>
			<li><a href={saveUrl('portal/c15-room3')}>Room 3</a></li>
			<li><a href={saveUrl('portal/c15-room3-conn')}>Room 3/4 Connector</a></li>
			<li><a href={saveUrl('portal/c15-room4')}>Room 4</a></li>
		</ul>
	</li>
	<li>
		<b>Chamber 16</b> (Turrets)
		<ul>
			<li><a href={saveUrl('portal/c16')}>Turret 1</a></li>
			<li><a href={saveUrl('portal/c16-turr1')}>Turret 2</a></li>
			<li><a href={saveUrl('portal/c16-turr2')}>Turret 3</a></li>
			<li><a href={saveUrl('portal/c16-turr3')}>Turret 4</a></li>
			<li><a href={saveUrl('portal/c16-turr4')}>Turret 5</a></li>
			<li><a href={saveUrl('portal/c16-turr5')}>Turrets 6 and 7</a></li>
			<li><a href={saveUrl('portal/c16-turr7')}>Turrets 8, 9 and 10</a></li>
			<li><a href={saveUrl('portal/c16-turr10')}>Turret 11</a></li>
			<li><a href={saveUrl('portal/c16-turr11')}>Turret 12</a></li>
		</ul>
	</li>
	<li>
		<b>Chamber 17</b> (Companion Cube)
		<ul>
			<li><a href={saveUrl('portal/c17')}>Room 1</a></li>
			<li><a href={saveUrl('portal/c17-room2')}>Room 2</a></li>
			<li><a href={saveUrl('portal/c17-room3')}>Room 3</a> (Murder)</li>
		</ul>
	</li>
	<li>
		<b>Chamber 18</b> (Hardest)
		<ul>
			<li><a href={saveUrl('portal/c18')}>Room 1</a></li>
			<li><a href={saveUrl('portal/c18-room2')}>Room 2</a></li>
			<li><a href={saveUrl('portal/c18-room3')}>Room 3</a></li>
		</ul>
	</li>
	<li>
		<b>Chamber 19</b> (Final)
		<ul>
			<li><a href={saveUrl('portal/c19')}>Start</a></li>
			<li><a href={saveUrl('portal/c19-oven')}>Oven</a></li>
		</ul>
	</li>
	<li>
		<b>Escape</b>
		<ul>
			<li>
				Escape Part 1
				<ul>
					<li><a href={saveUrl('portal/e1')}>Obstacle 1</a></li>
					<li><a href={saveUrl('portal/e1-obst2')}>Obstacle 2</a></li>
					<li><a href={saveUrl('portal/e1-obst3')}>Obstacle 3</a></li>
					<li><a href={saveUrl('portal/e1-obst4')}>Obstacle 4</a></li>
				</ul>
			</li>
			<li>
				Escape Part 2
				<ul>
					<li><a href={saveUrl('portal/e2')}>Obstacle 1</a></li>
					<li><a href={saveUrl('portal/e2-obst2')}>Obstacle 2</a></li>
					<li><a href={saveUrl('portal/e2-obst3')}>Obstacle 3</a></li>
					<li><a href={saveUrl('portal/e2-obst4')}>Obstacle 4</a></li>
				</ul>
			</li>
			<li>
				Escape Part 3
				<ul>
					<li><a href={saveUrl('portal/e3')}>Obstacle 1</a></li>
					<li><a href={saveUrl('portal/e3-obst2')}>Obstacle 2</a></li>
					<li><a href={saveUrl('portal/e3-obst3')}>Obstacle 3</a></li>
					<li><a href={saveUrl('portal/e3-obst4')}>Obstacle 4</a></li>
				</ul>
			</li>
			<li>
				Escape Part 4
				<ul>
					<li><a href={saveUrl('portal/e4')}>Obstacle 1</a></li>
					<li><a href={saveUrl('portal/e4-obst2')}>Obstacle 2</a></li>
					<li><a href={saveUrl('portal/e4-obst3')}>Obstacle 3</a></li>
				</ul>
			</li>
		</ul>
	</li>
	<li>
		<b>GLaDOS Fight</b>
		<ul>
			<li><a href={saveUrl('portal/boss')}>Arrival</a></li>
			<li><a href={saveUrl('portal/boss-core1')}>Core 1 Incineration</a> (Boss Fight Start)</li>
			<li><a href={saveUrl('portal/boss-core2')}>Core 2 Incineration</a></li>
			<li><a href={saveUrl('portal/boss-core3')}>Core 3 Incineration</a></li>
			<li><a href={saveUrl('portal/boss-core4')}>Core 4 Incineration</a> (Boss Fight End)</li>
		</ul>
	</li>
	<li><a href={saveUrl('portal/outside')}><b>Outside</b></a></li>
	<li><a href={saveUrl('portal/outro')}><b>Outro Sequence</b></a> (Cake)</li>
	<li>
		<a href={saveUrl('portal/credits')}><b>Credits</b></a> (load the outro savegame instead, this only
		shows text and doesn't play Still Alive)
	</li>
</ul>

<h2>Portal 2</h2>

<ul>
	<li>
		<b>Chapter 1:</b>
		The Courtesy Call
		<ul>
			<li>
				Chamber 0
				<i>(after Container Ride)</i>
				<ul>
					<li><a href={saveUrl('p2/c1-c0')}>Start</a></li>
					<li><a href={saveUrl('p2/c1-c0-skip')}>Skip the dialogue</a></li>
				</ul>
			</li>
			<li><a href={saveUrl('p2/c1-c1')}>Chamber 1</a> (Portal Carousel)</li>
			<li><a href={saveUrl('p2/c1-c2')}>Chamber 2</a> (Portal Gun)</li>
			<li><a href={saveUrl('p2/c1-c3')}>Chamber 3</a> (Smooth Jazz)</li>
			<li><a href={saveUrl('p2/c1-c4')}>Chamber 4</a> (after Smooth Jazz)</li>
			<li><a href={saveUrl('p2/c1-c5')}>Chamber 5</a> (Cube Momentum)</li>
			<li>
				Chamber 6
				<i>(Future Starter)</i>
				<ul>
					<li><a href={saveUrl('p2/c1-c6')}>Room 1</a></li>
					<li><a href={saveUrl('p2/c1-c6-room2')}>Room 2</a></li>
				</ul>
			</li>
			<li>
				Chamber 7
				<i>(Secret Panel)</i>
				<ul>
					<li><a href={saveUrl('p2/c1-c7')}>Start</a></li>
					<li><a href={saveUrl('p2/c1-c7-drop')}>Wheatley drops off the rail</a></li>
					<li><a href={saveUrl('p2/c1-c7-open')}>Secret Panel opens</a></li>
				</ul>
			</li>
			<li>
				GLaDOS Chamber
				<i>(Wakeup)</i>
				<ul>
					<li><a href={saveUrl('p2/c1-boss')}>Start</a></li>
					<li><a href={saveUrl('p2/c1-boss-wakeup')}>GLaDOS wakes up</a></li>
				</ul>
			</li>
			<li><a href={saveUrl('p2/c1-c19')}>Chamber 19</a> (Incinerator)</li>
		</ul>
	</li>
	<li>
		<b>Chapter 2:</b>
		The Cold Boot
		<ul>
			<li><a href={saveUrl('p2/c2-c1')}>Chamber 1</a> (Laser Intro)</li>
			<li><a href={saveUrl('p2/c2-c2')}>Chamber 2</a> (Laser Stairs)</li>
			<li><a href={saveUrl('p2/c2-c3')}>Chamber 3</a> (Dual Lasers)</li>
			<li><a href={saveUrl('p2/c2-c4')}>Chamber 4</a> (Laser Over Goo)</li>
			<li><a href={saveUrl('p2/c2-c5')}>Chamber 5</a> (Catapult Intro)</li>
			<li><a href={saveUrl('p2/c2-c6')}>Chamber 6</a> (Trust Fling)</li>
			<li><a href={saveUrl('p2/c2-c7')}>Chamber 7</a> (Pit Flings)</li>
			<li><a href={saveUrl('p2/c2-c8')}>Chamber 8</a> (Fizzler Intro)</li>
		</ul>
	</li>
	<li>
		<b>Chapter 3:</b>
		The Return
		<ul>
			<li><a href={saveUrl('p2/c3-c9')}>Chamber 9</a> (Ceiling Catapult)</li>
			<li><a href={saveUrl('p2/c3-c10')}>Chamber 10</a> (Ricochet)</li>
			<li><a href={saveUrl('p2/c3-c11')}>Chamber 11</a> (Bridge Intro)</li>
			<li><a href={saveUrl('p2/c3-c12')}>Chamber 12</a> (Bridge the Gap)</li>
			<li><a href={saveUrl('p2/c3-c13')}>Chamber 13</a> (Turret Intro)</li>
			<li><a href={saveUrl('p2/c3-c14')}>Chamber 14</a> (Laser Relays)</li>
			<li><a href={saveUrl('p2/c3-c15')}>Chamber 15</a> (Turret Blocker)</li>
			<li><a href={saveUrl('p2/c3-c16')}>Chamber 16</a> (Laser vs. Turret)</li>
			<li><a href={saveUrl('p2/c3-c17')}>Chamber 17</a> (Pull the Rug)</li>
		</ul>
	</li>
	<li>
		<b>Chapter 4:</b>
		The Surprise
		<ul>
			<li><a href={saveUrl('p2/c4-c18')}>Chamber 18</a> (Column Blocker)</li>
			<li><a href={saveUrl('p2/c4-c19')}>Chamber 19</a> (Laser Chaining)</li>
			<li><a href={saveUrl('p2/c4-c20')}>Chamber 20</a> (Triple Laser)</li>
			<li><a href={saveUrl('p2/c4-c21')}>Chamber 21</a> (Jailbreak)</li>
			<li><a href={saveUrl('p2/c4-e1')}>Escape Part 1</a></li>
			<li><a href={saveUrl('p2/c4-e2')}>Escape Part 2</a></li>
		</ul>
	</li>
	<li>
		<b>Chapter 5:</b>
		The Escape
		<ul>
			<li>
				Turret Manufacturing
				<i>(Turret Factory)</i>
				<ul>
					<li><a href={saveUrl('p2/c5-e1')}>Obstacle 1</a></li>
					<li><a href={saveUrl('p2/c5-e1-obst2')}>Obstacle 2</a></li>
				</ul>
			</li>
			<li>
				Turret Control Center
				<i>(Turret Sabotage)</i>
				<ul>
					<li><a href={saveUrl('p2/c5-e2')}>Obstacle 1</a></li>
					<li><a href={saveUrl('p2/c5-e2-obst2')}>Obstacle 2</a></li>
				</ul>
			</li>
			<li><a href={saveUrl('p2/c5-e3')}>Neurotoxin Generator</a> (Neurotoxin Sabotage)</li>
			<li><a href={saveUrl('p2/c5-pipe')}>Tube Ride</a></li>
			<li>
				GLaDOS' Lair
				<i>(Core)</i>
				<ul>
					<li><a href={saveUrl('p2/c5-cat')}>Tube Exit</a></li>
					<li><a href={saveUrl('p2/c5-boss')}>GLaDOS' Lair</a></li>
					<li><a href={saveUrl('p2/c5-stalemate')}>Stalemate</a></li>
				</ul>
			</li>
		</ul>
	</li>
</ul>

To be continued... (I still have 62 savegames ready to put them here)
