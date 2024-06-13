<div class="bg-slate-50 p-10 rounded-sm drop-shadow-s">
	<form action="" method="post">
		<div class="flex align-middle justify-center items-center my-10">
			<svg
				xmlns="http://www.w3.org/2000/svg"
				width="4em"
				height="4em"
				viewBox="0 0 24 24"
				{...$$props}
			>
				<path fill="gray" d="M12 18H6v-4h6m9 0v-2l-1-5H4l-1 5v2h1v6h10v-6h4v6h2v-6m0-10H4v2h16z" />
			</svg>
		</div>
		<div class="flex">
			<label for="user">Usuario</label>
			<input name="user" type="text" />
		</div>
		<div class="flex">
			<label for="password">Contraseña</label>
			<input name="password" type="text" />
		</div>
		<div>
			<button>Login</button>
		</div>
	</form>
</div>
