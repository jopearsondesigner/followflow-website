<script lang="ts">
	import { resolve } from '$app/paths';
	import logoLight from '$lib/assets/logos/followflow-logo-light.svg';
</script>

<svelte:head>
	<title>FollowFlow — AI Follow-Up Command Center</title>

	<meta
		name="description"
		content="FollowFlow helps founder-led service businesses know who to follow up with next, why it matters, and what to say before warm leads go cold."
	/>

	<meta property="og:title" content="FollowFlow — AI Follow-Up Command Center" />
	<meta
		property="og:description"
		content="A calm AI command center for prioritizing warm leads, surfacing revenue at risk, and suggesting the next follow-up."
	/>
	<meta property="og:type" content="website" />
	<meta property="og:image" content="/og-followflow.png" />
	<meta property="og:image:width" content="1200" />
	<meta property="og:image:height" content="630" />
	<meta
		property="og:image:alt"
		content="FollowFlow social preview showing the headline Move the lead before momentum drops beside a product dashboard."
	/>

	<meta name="twitter:card" content="summary_large_image" />
	<meta name="twitter:title" content="FollowFlow — AI Follow-Up Command Center" />
	<meta
		name="twitter:description"
		content="Know who to follow up with next — and what to say — before warm leads go cold."
	/>
	<meta name="twitter:image" content="/og-followflow.png" />
	<meta
		name="twitter:image:alt"
		content="FollowFlow social preview showing the headline Move the lead before momentum drops beside a product dashboard."
	/>
</svelte:head>

<main class="ff-page-bg min-h-screen overflow-hidden text-[var(--ff-text)]">
	<header
		class="fixed top-0 right-0 left-0 z-50 border-b border-[rgba(255,255,255,0.06)] bg-[rgba(8,11,16,0.72)] backdrop-blur-xl"
	>
		<div class="mx-auto flex h-16 max-w-7xl items-center justify-between px-6">
			<a href={resolve('/')} class="inline-flex items-center transition-opacity hover:opacity-80">
				<img src={logoLight} alt="FollowFlow" class="h-6 w-auto" />
			</a>

			<nav class="hidden items-center gap-7 text-sm text-[var(--ff-text-muted)] md:flex">
				<a href={resolve('/#problem')} class="transition-colors hover:text-[var(--ff-text)]"
					>Problem</a
				>
				<a href={resolve('/#product')} class="transition-colors hover:text-[var(--ff-text)]"
					>Product</a
				>
				<a href={resolve('/#demo')} class="transition-colors hover:text-[var(--ff-text)]">Demo</a>
			</nav>

			<a
				href="https://followflow-demo.netlify.app/dashboard"
				target="_blank"
				rel="noreferrer"
				class="ff-button-secondary px-4 py-2 text-sm"
			>
				View demo
			</a>
		</div>
	</header>

	<section
		class="relative mx-auto grid min-h-screen max-w-7xl items-center gap-16 px-6 pt-32 pb-24 lg:grid-cols-[0.88fr_1.12fr] xl:gap-20"
	>
		<div
			class="pointer-events-none absolute top-1/2 left-1/2 h-[44rem] w-[44rem] -translate-x-1/2 -translate-y-1/2 rounded-full bg-[rgba(56,213,255,0.055)] blur-[130px]"
		></div>

		<div class="relative z-10 lg:scale-[0.96] xl:scale-100">
			<p class="text-sm font-semibold tracking-[0.14em] text-[var(--ff-cyan)] uppercase">
				FollowFlow
			</p>

			<h1
				class="mt-5 max-w-4xl text-5xl leading-[0.92] font-semibold tracking-[-0.065em] md:text-7xl xl:text-[5.4rem]"
			>
				Stop letting warm leads cool off quietly.
			</h1>

			<p class="mt-6 max-w-2xl text-lg leading-8 text-[var(--ff-text-muted)]">
				FollowFlow shows founder-led service businesses who to follow up with next, why it matters,
				and what to say before momentum drops.
			</p>

			<div class="mt-9 flex flex-wrap gap-3">
				<a
					href="https://followflow-demo.netlify.app/dashboard"
					target="_blank"
					rel="noreferrer"
					class="ff-button-primary px-5 py-3 text-sm"
				>
					View product demo
				</a>

				<a
					href="https://github.com/jopearsondesigner"
					class="ff-button-secondary px-5 py-3 text-sm"
				>
					View source
				</a>
			</div>

			<div class="mt-10 grid max-w-xl gap-3 sm:grid-cols-3">
				<div
					class="rounded-[var(--ff-radius-md)] border border-[rgba(255,255,255,0.07)] bg-[rgba(255,255,255,0.025)] p-4"
				>
					<p class="text-xs font-semibold tracking-[0.12em] text-[var(--ff-cyan)] uppercase">
						Example signal
					</p>
					<p class="mt-3 text-2xl font-semibold tracking-tight">$8.7k</p>
					<p class="mt-1 text-xs leading-5 text-[var(--ff-text-muted)]">in open opportunities</p>
				</div>

				<div
					class="rounded-[var(--ff-radius-md)] border border-[rgba(255,255,255,0.07)] bg-[rgba(255,255,255,0.025)] p-4"
				>
					<p class="text-xs font-semibold tracking-[0.12em] text-[var(--ff-amber)] uppercase">
						Queue pressure
					</p>
					<p class="mt-3 text-2xl font-semibold tracking-tight">7</p>
					<p class="mt-1 text-xs leading-5 text-[var(--ff-text-muted)]">leads need attention</p>
				</div>

				<div
					class="rounded-[var(--ff-radius-md)] border border-[rgba(94,242,184,0.12)] bg-[rgba(94,242,184,0.035)] p-4"
				>
					<p class="text-xs font-semibold tracking-[0.12em] text-[var(--ff-mint)] uppercase">
						Next best move
					</p>
					<p class="mt-3 text-2xl font-semibold tracking-tight">1</p>
					<p class="mt-1 text-xs leading-5 text-[var(--ff-text-muted)]">
						follow-up rises to the top
					</p>
				</div>
			</div>
		</div>

		<div class="relative z-10 lg:scale-[0.96] xl:scale-100">
			<div
				class="pointer-events-none absolute -top-8 left-[5.5rem] z-20 hidden rounded-[var(--ff-radius-md)] border border-[rgba(56,213,255,0.22)] bg-[rgba(8,11,16,0.86)] px-4 py-3 shadow-[0_18px_50px_rgba(0,0,0,0.35)] backdrop-blur-xl md:block"
			>
				<p class="text-xs font-semibold tracking-[0.08em] text-[var(--ff-cyan)] uppercase">
					Signal detected
				</p>
				<p class="mt-1 text-sm text-[var(--ff-text)]">Quote request opened yesterday</p>
				<p class="mt-1 text-xs text-[var(--ff-text-muted)]">No response sent yet</p>
			</div>

			<div
				class="pointer-events-none absolute -right-2 top-28 z-20 hidden rounded-[var(--ff-radius-md)] border border-[rgba(255,184,107,0.18)] bg-[rgba(8,11,16,0.82)] px-4 py-3 shadow-[0_18px_50px_rgba(0,0,0,0.35)] backdrop-blur-xl md:block"
			>
				<p class="text-xs font-medium text-[var(--ff-amber)]">$2.4k at risk</p>
				<p class="mt-1 text-sm text-[var(--ff-text-muted)]">Window still active</p>
			</div>

			<div
				class="pointer-events-none absolute -bottom-8 left-16 z-20 hidden rounded-[var(--ff-radius-md)] border border-[rgba(94,242,184,0.18)] bg-[rgba(8,11,16,0.82)] px-4 py-3 shadow-[0_18px_50px_rgba(0,0,0,0.35)] backdrop-blur-xl md:block"
			>
				<p class="text-xs font-medium text-[var(--ff-mint)]">Suggested reply ready</p>
				<p class="mt-1 text-sm text-[var(--ff-text-muted)]">Friendly tone</p>
			</div>

			<div
				class="relative overflow-hidden rounded-[1.35rem] border border-[rgba(56,213,255,0.16)] bg-[#101827] p-3 shadow-[0_30px_100px_rgba(0,0,0,0.45)]"
			>
				<div
					class="absolute inset-0 bg-[radial-gradient(circle_at_top_left,rgba(56,213,255,0.12),transparent_34%),radial-gradient(circle_at_bottom_right,rgba(94,242,184,0.08),transparent_36%)]"
				></div>

				<div
					class="relative mb-3 flex items-center justify-between rounded-t-[1rem] border border-[rgba(255,255,255,0.07)] bg-[rgba(8,11,16,0.62)] px-4 py-3"
				>
					<div class="flex items-center gap-2">
						<span class="h-2.5 w-2.5 rounded-full bg-[rgba(255,107,122,0.85)]"></span>
						<span class="h-2.5 w-2.5 rounded-full bg-[rgba(255,184,107,0.85)]"></span>
						<span class="h-2.5 w-2.5 rounded-full bg-[rgba(94,242,184,0.85)]"></span>
					</div>

					<p class="text-xs font-medium text-[var(--ff-text-muted)]">followflow.app / today</p>
				</div>

				<div
					class="relative rounded-b-[1rem] border border-[rgba(255,255,255,0.07)] bg-[rgba(8,11,16,0.74)] p-5"
				>
					<div class="flex items-center justify-between gap-4">
						<div>
							<p class="text-sm font-medium text-[var(--ff-cyan)]">Today’s Flow</p>
							<h2 class="mt-2 text-3xl font-semibold tracking-tight">Start with this lead</h2>
						</div>

						<div
							class="rounded-[var(--ff-radius-md)] border border-[rgba(255,255,255,0.08)] bg-[rgba(255,255,255,0.03)] px-4 py-3 text-right"
						>
							<p class="text-2xl font-semibold">$2.4k</p>
							<p class="text-xs text-[var(--ff-text-muted)]">at risk</p>
						</div>
					</div>

					<div
						class="mt-6 rounded-[var(--ff-radius-xl)] border border-[rgba(56,213,255,0.2)] bg-[#1b2638] p-6 shadow-[0_0_60px_rgba(56,213,255,0.08)]"
					>
						<div class="flex items-center justify-between gap-4">
							<p
								class="rounded-[var(--ff-radius-sm)] border border-[rgba(56,213,255,0.24)] bg-[rgba(56,213,255,0.06)] px-3 py-1 text-[0.68rem] font-semibold tracking-[0.08em] text-[var(--ff-cyan)] uppercase"
							>
								Recommended first action
							</p>

							<p class="text-sm text-[var(--ff-text-muted)]">Window is active</p>
						</div>

						<div class="mt-6 flex gap-5">
							<div class="w-1.5 shrink-0 rounded-full bg-[var(--ff-cyan)]"></div>

							<div>
								<h3 class="text-5xl leading-none font-semibold tracking-[-0.05em]">
									Sarah Mitchell
								</h3>

								<p class="mt-2 text-sm text-[var(--ff-text-muted)]">
									Interior consultation · Timeline request
								</p>

								<p class="mt-6 max-w-2xl text-lg leading-8">
									Asked about availability yesterday. No reply has been sent yet.
								</p>

								<div class="mt-7">
									<div class="mb-2 flex items-center justify-between text-xs">
										<span class="text-[var(--ff-text-muted)]">Needs response today</span>
										<span class="text-[var(--ff-cyan)]">96 urgency</span>
									</div>

									<div class="h-1.5 overflow-hidden rounded-full bg-[#0b111c]">
										<div class="h-full w-[96%] rounded-full bg-[var(--ff-cyan)]"></div>
									</div>
								</div>
							</div>
						</div>
					</div>

					<div class="mt-5 grid gap-4 md:grid-cols-[0.95fr_1.05fr]">
						<div
							class="rounded-[var(--ff-radius-lg)] border border-[rgba(255,255,255,0.07)] bg-[rgba(255,255,255,0.025)] p-5"
						>
							<p class="text-sm font-medium text-[var(--ff-cyan)]">Why this lead is first</p>

							<div class="mt-4 space-y-3 text-sm leading-6 text-[var(--ff-text-muted)]">
								<p>Evidence: quote request is still active.</p>
								<p>Risk: momentum is cooling.</p>
								<p>Action: send a clear next-step reply.</p>
							</div>
						</div>

						<div
							class="rounded-[var(--ff-radius-lg)] border border-[rgba(255,255,255,0.07)] bg-[#101827] p-5"
						>
							<p class="text-sm font-medium text-[var(--ff-cyan)]">Suggested reply</p>

							<p class="mt-4 leading-7 text-[var(--ff-text-muted)]">
								Hi Sarah — I have availability this week if you’d like to talk through the next
								steps.
							</p>
						</div>
					</div>
				</div>
			</div>
		</div>
	</section>

	<section id="problem" class="relative border-t border-[rgba(255,255,255,0.06)] px-6 py-28">
		<div class="mx-auto grid max-w-7xl gap-12 lg:grid-cols-[0.8fr_1.2fr]">
			<div>
				<p class="text-sm font-semibold tracking-[0.14em] text-[var(--ff-cyan)] uppercase">
					The problem
				</p>

				<h2 class="mt-5 max-w-xl text-4xl leading-[0.96] font-semibold md:text-6xl">
					Warm leads don’t vanish. They cool off quietly.
				</h2>
			</div>

			<div class="grid gap-4 md:grid-cols-2">
				<div
					class="rounded-[var(--ff-radius-xl)] border border-[rgba(255,255,255,0.07)] bg-[rgba(255,255,255,0.025)] p-6"
				>
					<p class="text-lg font-semibold">A quote request sits too long.</p>
					<p class="mt-3 leading-7 text-[var(--ff-text-muted)]">
						The lead was interested yesterday. Today, they are comparing options.
					</p>
				</div>

				<div
					class="rounded-[var(--ff-radius-xl)] border border-[rgba(255,255,255,0.07)] bg-[rgba(255,255,255,0.025)] p-6"
				>
					<p class="text-lg font-semibold">The founder gets overloaded.</p>
					<p class="mt-3 leading-7 text-[var(--ff-text-muted)]">
						Follow-up is scattered across inboxes, forms, DMs, referrals, and old threads.
					</p>
				</div>

				<div
					class="rounded-[var(--ff-radius-xl)] border border-[rgba(255,255,255,0.07)] bg-[rgba(255,255,255,0.025)] p-6"
				>
					<p class="text-lg font-semibold">Priority gets blurry.</p>
					<p class="mt-3 leading-7 text-[var(--ff-text-muted)]">
						Every lead feels important, so the next best action is hard to see.
					</p>
				</div>

				<div
					class="relative overflow-hidden rounded-[var(--ff-radius-xl)] border border-[rgba(56,213,255,0.22)] bg-[rgba(56,213,255,0.06)] p-6 shadow-[0_0_50px_rgba(56,213,255,0.055)] md:col-span-2"
				>
					<div
						class="pointer-events-none absolute -right-16 -top-16 h-40 w-40 rounded-full bg-[rgba(56,213,255,0.12)] blur-3xl"
					></div>

					<p
						class="relative text-sm font-semibold tracking-[0.12em] text-[var(--ff-cyan)] uppercase"
					>
						The hidden cost
					</p>

					<p class="relative mt-4 text-2xl font-semibold tracking-tight text-[var(--ff-text)]">
						Revenue leaks quietly when follow-up has no priority system.
					</p>

					<p class="relative mt-4 max-w-2xl leading-7 text-[var(--ff-text-muted)]">
						FollowFlow turns scattered signals into a clear daily action, so the founder can move
						the warmest opportunity before the window closes.
					</p>
				</div>
			</div>
		</div>
	</section>
	<section id="product" class="relative border-t border-[rgba(255,255,255,0.06)] px-6 py-28">
		<div class="mx-auto max-w-7xl">
			<div class="max-w-3xl">
				<p class="text-sm font-semibold tracking-[0.14em] text-[var(--ff-cyan)] uppercase">
					How it works
				</p>

				<h2 class="mt-5 text-4xl leading-[0.96] font-semibold md:text-6xl">
					FollowFlow turns scattered follow-up into one clear next move.
				</h2>

				<p class="mt-6 text-lg leading-8 text-[var(--ff-text-muted)]">
					Instead of making founders sort through every conversation manually, FollowFlow reads the
					signal, explains the risk, and recommends the action that matters most today.
				</p>
			</div>

			<div class="mt-14 grid gap-4 lg:grid-cols-3">
				<div
					class="rounded-[var(--ff-radius-xl)] border border-[rgba(255,255,255,0.07)] bg-[rgba(255,255,255,0.025)] p-7"
				>
					<p class="text-sm font-semibold tracking-[0.14em] text-[var(--ff-cyan)] uppercase">
						01 / Evidence
					</p>

					<h3 class="mt-5 text-2xl font-semibold tracking-tight">Find the signal.</h3>

					<p class="mt-4 leading-7 text-[var(--ff-text-muted)]">
						FollowFlow surfaces the lead activity that matters: a recent quote request, an
						unanswered reply, a warm referral, or a conversation that is starting to cool.
					</p>

					<div
						class="mt-6 rounded-[var(--ff-radius-md)] border border-[rgba(255,255,255,0.07)] bg-[rgba(8,11,16,0.42)] p-4"
					>
						<p
							class="text-xs font-semibold tracking-[0.12em] text-[var(--ff-text-muted)] uppercase"
						>
							Input
						</p>
						<p class="mt-2 text-sm text-[var(--ff-text)]">“Asked about availability yesterday.”</p>
					</div>
				</div>

				<div
					class="rounded-[var(--ff-radius-xl)] border border-[rgba(255,184,107,0.14)] bg-[rgba(255,184,107,0.035)] p-7"
				>
					<p class="text-sm font-semibold tracking-[0.14em] text-[var(--ff-amber)] uppercase">
						02 / Risk
					</p>

					<h3 class="mt-5 text-2xl font-semibold tracking-tight">Understand what’s slipping.</h3>

					<p class="mt-4 leading-7 text-[var(--ff-text-muted)]">
						The dashboard translates messy follow-up into priority: what revenue may be at risk, how
						urgent the lead is, and why this opportunity should move first.
					</p>

					<div
						class="mt-6 rounded-[var(--ff-radius-md)] border border-[rgba(255,184,107,0.12)] bg-[rgba(8,11,16,0.42)] p-4"
					>
						<p class="text-xs font-semibold tracking-[0.12em] text-[var(--ff-amber)] uppercase">
							Risk
						</p>
						<p class="mt-2 text-sm text-[var(--ff-text)]">$2.4k opportunity, no reply sent yet.</p>
					</div>
				</div>

				<div
					class="rounded-[var(--ff-radius-xl)] border border-[rgba(94,242,184,0.14)] bg-[rgba(94,242,184,0.035)] p-7"
				>
					<p class="text-sm font-semibold tracking-[0.14em] text-[var(--ff-mint)] uppercase">
						03 / Action
					</p>

					<h3 class="mt-5 text-2xl font-semibold tracking-tight">Send the next message.</h3>

					<p class="mt-4 leading-7 text-[var(--ff-text-muted)]">
						FollowFlow gives the founder a calm, usable next step — including a suggested reply that
						matches the lead, the timing, and the tone of the conversation.
					</p>

					<div
						class="mt-6 rounded-[var(--ff-radius-md)] border border-[rgba(94,242,184,0.12)] bg-[rgba(8,11,16,0.42)] p-4"
					>
						<p class="text-xs font-semibold tracking-[0.12em] text-[var(--ff-mint)] uppercase">
							Output
						</p>
						<p class="mt-2 text-sm text-[var(--ff-text)]">
							“Follow up first — window is still active.”
						</p>
					</div>
				</div>
			</div>
		</div>
	</section>
	<section id="demo" class="relative border-t border-[rgba(255,255,255,0.06)] px-6 py-28">
		<div
			class="mx-auto max-w-7xl overflow-hidden rounded-[1.5rem] border border-[rgba(56,213,255,0.14)] bg-[rgba(17,24,39,0.72)] p-8 shadow-[0_30px_100px_rgba(0,0,0,0.35)] md:p-12"
		>
			<div class="grid items-center gap-10 lg:grid-cols-[1fr_auto]">
				<div>
					<p class="text-sm font-semibold tracking-[0.14em] text-[var(--ff-cyan)] uppercase">
						Product demo
					</p>

					<h2 class="mt-5 max-w-3xl text-4xl leading-[0.96] font-semibold md:text-6xl">
						See how FollowFlow decides who needs attention first.
					</h2>

					<div class="mt-6 max-w-2xl space-y-4">
						<p class="text-lg leading-8 text-[var(--ff-text-muted)]">
							Explore the interactive dashboard prototype and see how a warm lead moves from
							scattered signal to prioritized action.
						</p>

						<p class="max-w-xl text-sm leading-6 text-[rgba(244,247,250,0.68)]">
							Built around a simple decision model: evidence, risk, and the next best follow-up.
						</p>
					</div>
				</div>

				<div class="flex flex-wrap gap-3 lg:justify-end">
					<a
						href="https://followflow-demo.netlify.app/dashboard"
						target="_blank"
						rel="noreferrer"
						class="ff-button-primary px-5 py-3 text-sm"
					>
						View product demo
					</a>

					<a
						href="https://github.com/jopearsondesigner/followflow-website"
						target="_blank"
						rel="noreferrer"
						class="ff-button-secondary px-5 py-3 text-sm"
					>
						View source
					</a>
				</div>
			</div>
		</div>
	</section>
	<section class="relative border-t border-[rgba(255,255,255,0.06)] px-6 py-24">
		<div class="mx-auto grid max-w-7xl gap-10 lg:grid-cols-[0.8fr_1.2fr]">
			<div>
				<p class="text-sm font-semibold tracking-[0.14em] text-[var(--ff-cyan)] uppercase">
					Product exploration
				</p>

				<h2 class="mt-5 max-w-xl text-4xl leading-[0.96] font-semibold md:text-5xl">
					Designed as a focused AI product concept for founder-led teams.
				</h2>
			</div>

			<div class="grid gap-4 md:grid-cols-3">
				<div
					class="rounded-[var(--ff-radius-xl)] border border-[rgba(255,255,255,0.07)] bg-[rgba(255,255,255,0.025)] p-6"
				>
					<p class="text-lg font-semibold">Defined the product angle</p>
					<p class="mt-3 leading-7 text-[var(--ff-text-muted)]">
						Framed FollowFlow around a specific founder problem: warm opportunities getting lost
						because follow-up has no clear priority system.
					</p>
				</div>

				<div
					class="rounded-[var(--ff-radius-xl)] border border-[rgba(255,255,255,0.07)] bg-[rgba(255,255,255,0.025)] p-6"
				>
					<p class="text-lg font-semibold">Designed the decision model</p>
					<p class="mt-3 leading-7 text-[var(--ff-text-muted)]">
						Created the Evidence → Risk → Action flow so the interface explains why a lead matters,
						not just which lead appears first.
					</p>
				</div>

				<div
					class="rounded-[var(--ff-radius-xl)] border border-[rgba(255,255,255,0.07)] bg-[rgba(255,255,255,0.025)] p-6"
				>
					<p class="text-lg font-semibold">Built the front-end prototype</p>
					<p class="mt-3 leading-7 text-[var(--ff-text-muted)]">
						Implemented the marketing page and dashboard prototype in SvelteKit and TailwindCSS with
						a shared visual system.
					</p>
				</div>
			</div>
		</div>
	</section>
</main>
