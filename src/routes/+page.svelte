<script lang="ts">
	let pozdrav = 'ahoj';
</script>

<title>PulseRP - Main</title>
<link
	rel="stylesheet"
	href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css"
/>
<body class="min-h-screen bg-gradient-to-b from-blue-900 to-blue-300">
	<div class="column overflow-hidden border-b-2 border-black">
		<div class="relative h-18 w-full bg-gradient-to-b from-slate-900 to-slate-700">
			<div class="mr-4 ml-4 flex h-full items-center justify-between">
				<a href="/login" class="group relative text-xl text-white"
					><span class="mr-1"><i class="fa-solid fa-house"></i></span>Přihlásit se
					<span
						class="pointer-events-none absolute -bottom-1 left-0 h-1 w-0 bg-blue-700 transition-all duration-300 group-hover:w-full"
					></span>
				</a>
				<div class="flex items-center gap-7 text-white">
					<a href="/shop" class="group relative">
						<span class="mr-1"><i class="fa-solid fa-shop"></i></span>Obchod
						<span
							class="pointer-events-none absolute -bottom-1 left-0 h-1 w-0 bg-blue-700 transition-all duration-300 group-hover:w-full"
						></span>
					</a>
					<a href="/about" class="group relative">
						<span class="mr-1"><i class="fa-solid fa-question"></i></span>O nás
						<span
							class="pointer-events-none absolute -bottom-1 left-0 h-1 w-0 bg-blue-700 transition-all duration-300 group-hover:w-full"
						></span>
					</a>
					<a href="/statistiky" class="group relative">
						<span class="mr-1"><i class="fa-solid fa-chart-simple "></i></span>Statistiky
						<span
							class="pointer-events-none absolute -bottom-1 left-0 h-1 w-0 bg-blue-700 transition-all duration-300 group-hover:w-full"
						></span>
					</a>
					<a href="/team" class="group relative">
						<span class="mr-1"><i class="fa-solid fa-people-group"></i></span>Náš team
						<span
							class="pointer-events-none absolute -bottom-1 left-0 h-1 w-0 bg-blue-700 transition-all duration-300 group-hover:w-full"
						></span>
					</a>
					<a href="/rules" class="group relative">
						<span class="mr-1"><i class="fa-solid fa-book"></i></span>Pravidla
						<span
							class="pointer-events-none absolute -bottom-1 left-0 h-1 w-0 bg-blue-700 transition-all duration-300 group-hover:w-full"
						></span>
					</a>
				</div>
				<a href="/" class="group relative text-xl text-white">
					<span class="mr-1"><i class="fa-solid fa-bolt"></i></span>PulseRP
					<span
						class="pointer-events-none absolute -bottom-1 left-0 h-1 w-0 bg-blue-700 transition-all duration-300 group-hover:w-full"
					></span>
				</a>
			</div>
		</div>
		<div class="h-2 w-full bg-white rounded-b-xl shadow-[0_8px_24px_0_rgba(30,64,175,0.25)]"></div>
	</div>
	<div class="text-center flex-column">
		<h1 class="text-6xl text-gray-900 mt-32 bg-gradient-to-b from-slate-900 to-gray-700 bg-clip-text text-transparent">Vítej na portálu</h1>
		<span class="gap-2 flex items-center justify-center">
			<h1 class="text-7xl text-gray-900 mt-4 bg-gradient-to-b from-blue-500 to-white bg-clip-text text-transparent">PulseRP</h1>
			<span class="text-7xl bg-gradient-to-b from-blue-500 to-white bg-clip-text text-transparent"><i class="fa-solid fa-bolt"></i></span>
		</span>
	</div>
</body>
