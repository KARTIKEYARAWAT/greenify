# greenify
<!DOCTYPE html>
<html>

<head>
	<title>GREENIFY</title>
	<meta charset="utf-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<meta name="format-detection" content="telephone=no">
	<meta name="apple-mobile-web-app-capable" content="yes">
	<meta name="author" content="author">
	<meta name="keywords" content="keywords">
	<meta name="description" content="description">

	<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/css/bootstrap.min.css" rel="stylesheet"
		integrity="sha384-4bw+/aepP/YC94hEpVNVgiZdgIC5+VKNBQNGCHeKRQN+PtmoHDEXuppvnDJzQIu9" crossorigin="anonymous">
	<link rel="stylesheet" type="text/css" href="css/vendor.css">
	<link rel="stylesheet" type="text/css" href="style.css">

	<link rel="preconnect" href="https://fonts.googleapis.com">
	<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
	<link
		href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,700;1,300;1,400;1,700&family=Roboto:ital,wght@0,300;0,400;0,700;1,300;1,400;1,700&display=swap"
		rel="stylesheet">

</head>

<body>
	<svg xmlns="http://www.w3.org/2000/svg" style="display: none;">
		<defs>
			<symbol xmlns="http://www.w3.org/2000/svg" id="instagram" viewBox="0 0 15 15">
				<path fill="none" stroke="currentColor"
					d="M11 3.5h1M4.5.5h6a4 4 0 0 1 4 4v6a4 4 0 0 1-4 4h-6a4 4 0 0 1-4-4v-6a4 4 0 0 1 4-4Zm3 10a3 3 0 1 1 0-6a3 3 0 0 1 0 6Z" />
			</symbol>
			<symbol xmlns="http://www.w3.org/2000/svg" id="facebook" viewBox="0 0 15 15">
				<path fill="none" stroke="currentColor"
					d="M7.5 14.5a7 7 0 1 1 0-14a7 7 0 0 1 0 14Zm0 0v-8a2 2 0 0 1 2-2h.5m-5 4h5" />
			</symbol>
			<symbol xmlns="http://www.w3.org/2000/svg" id="twitter" viewBox="0 0 15 15">
				<path fill="currentColor"
					d="m14.478 1.5l.5-.033a.5.5 0 0 0-.871-.301l.371.334Zm-.498 2.959a.5.5 0 1 0-1 0h1Zm-6.49.082h-.5h.5Zm0 .959h.5h-.5Zm-6.99 7V12a.5.5 0 0 0-.278.916L.5 12.5Zm.998-11l.469-.175a.5.5 0 0 0-.916-.048l.447.223Zm3.994 9l.354.353a.5.5 0 0 0-.195-.827l-.159.474Zm7.224-8.027l-.37.336l.18.199l.265-.04l-.075-.495Zm1.264-.94c.051.778.003 1.25-.123 1.606c-.122.345-.336.629-.723 1l.692.722c.438-.42.776-.832.974-1.388c.193-.546.232-1.178.177-2.006l-.998.066Zm0 3.654V4.46h-1v.728h1Zm-6.99-.646V5.5h1v-.959h-1Zm0 .959V6h1v-.5h-1ZM10.525 1a3.539 3.539 0 0 0-3.537 3.541h1A2.539 2.539 0 0 1 10.526 2V1Zm2.454 4.187C12.98 9.503 9.487 13 5.18 13v1c4.86 0 8.8-3.946 8.8-8.813h-1ZM1.03 1.675C1.574 3.127 3.614 6 7.49 6V5C4.174 5 2.421 2.54 1.966 1.325l-.937.35Zm.021-.398C.004 3.373-.157 5.407.604 7.139c.759 1.727 2.392 3.055 4.73 3.835l.317-.948c-2.155-.72-3.518-1.892-4.132-3.29c-.612-1.393-.523-3.11.427-5.013l-.895-.446Zm4.087 8.87C4.536 10.75 2.726 12 .5 12v1c2.566 0 4.617-1.416 5.346-2.147l-.708-.706Zm7.949-8.009A3.445 3.445 0 0 0 10.526 1v1c.721 0 1.37.311 1.82.809l.74-.671Zm-.296.83a3.513 3.513 0 0 0 2.06-1.134l-.744-.668a2.514 2.514 0 0 1-1.466.813l.15.989ZM.222 12.916C1.863 14.01 3.583 14 5.18 14v-1c-1.63 0-3.048-.011-4.402-.916l-.556.832Z" />
			</symbol>
			<symbol xmlns="http://www.w3.org/2000/svg" id="pinterest" viewBox="0 0 15 15">
				<path fill="none" stroke="currentColor"
					d="m4.5 13.5l3-7m-3.236 3a2.989 2.989 0 0 1-.764-2V7A3.5 3.5 0 0 1 7 3.5h1A3.5 3.5 0 0 1 11.5 7v.5a3 3 0 0 1-3 3a2.081 2.081 0 0 1-1.974-1.423L6.5 9m1 5.5a7 7 0 1 1 0-14a7 7 0 0 1 0 14Z" />
			</symbol>
			<symbol xmlns="http://www.w3.org/2000/svg" id="youtube" viewBox="0 0 15 15">
				<path fill="currentColor"
					d="m1.61 12.738l-.104.489l.105-.489Zm11.78 0l.104.489l-.105-.489Zm0-10.476l.104-.489l-.105.489Zm-11.78 0l.106.489l-.105-.489ZM6.5 5.5l.277-.416A.5.5 0 0 0 6 5.5h.5Zm0 4H6a.5.5 0 0 0 .777.416L6.5 9.5Zm3-2l.277.416a.5.5 0 0 0 0-.832L9.5 7.5ZM0 3.636v7.728h1V3.636H0Zm15 7.728V3.636h-1v7.728h1ZM1.506 13.227c3.951.847 8.037.847 11.988 0l-.21-.978a27.605 27.605 0 0 1-11.568 0l-.21.978ZM13.494 1.773a28.606 28.606 0 0 0-11.988 0l.21.978a27.607 27.607 0 0 1 11.568 0l.21-.978ZM15 3.636c0-.898-.628-1.675-1.506-1.863l-.21.978c.418.09.716.458.716.885h1Zm-1 7.728a.905.905 0 0 1-.716.885l.21.978A1.905 1.905 0 0 0 15 11.364h-1Zm-14 0c0 .898.628 1.675 1.506 1.863l.21-.978A.905.905 0 0 1 1 11.364H0Zm1-7.728c0-.427.298-.796.716-.885l-.21-.978A1.905 1.905 0 0 0 0 3.636h1ZM6 5.5v4h1v-4H6Zm.777 4.416l3-2l-.554-.832l-3 2l.554.832Zm3-2.832l-3-2l-.554.832l3 2l.554-.832Z" />
			</symbol>
			<symbol xmlns="http://www.w3.org/2000/svg" id="dribble" viewBox="0 0 15 15">
				<path fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round"
					d="M4.839 1.024c3.346 4.041 5.096 7.922 5.704 12.782M.533 6.82c5.985-.138 9.402-1.083 11.97-4.216M2.7 12.594c3.221-4.902 7.171-5.65 11.755-4.293M14.5 7.5a7 7 0 1 0-14 0a7 7 0 0 0 14 0Z" />
			</symbol>
			<symbol xmlns="http://www.w3.org/2000/svg" id="calendar" viewBox="0 0 24 24">
				<g fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2">
					<rect width="20" height="18" x="2" y="4" rx="4" />
					<path d="M8 2v4m8-4v4M2 10h20" />
				</g>
			</symbol>
			<symbol xmlns="http://www.w3.org/2000/svg" id="shopping-bag" viewBox="0 0 24 24">
				<g fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2">
					<path
						d="M3.977 9.84A2 2 0 0 1 5.971 8h12.058a2 2 0 0 1 1.994 1.84l.803 10A2 2 0 0 1 18.833 22H5.167a2 2 0 0 1-1.993-2.16l.803-10Z" />
					<path d="M16 11V6a4 4 0 0 0-4-4v0a4 4 0 0 0-4 4v5" />
				</g>
			</symbol>
			<symbol xmlns="http://www.w3.org/2000/svg" id="gift" viewBox="0 0 24 24">
				<g fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2">
					<rect width="18" height="14" x="3" y="8" rx="2" />
					<path d="M12 5a3 3 0 1 0-3 3m6 0a3 3 0 1 0-3-3m0 0v17m9-7H3" />
				</g>
			</symbol>
			<symbol xmlns="http://www.w3.org/2000/svg" id="arrow-cycle" viewBox="0 0 24 24">
				<g fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2">
					<path
						d="M22 12c0 6-4.39 10-9.806 10C7.792 22 4.24 19.665 3 16m-1-4C2 6 6.39 2 11.806 2C16.209 2 19.76 4.335 21 8" />
					<path d="m7 17l-4-1l-1 4M17 7l4 1l1-4" />
				</g>
			</symbol>
			<symbol xmlns="http://www.w3.org/2000/svg" id="link" viewBox="0 0 24 24">
				<path fill="currentColor"
					d="M12 19a1 1 0 1 0-1-1a1 1 0 0 0 1 1Zm5 0a1 1 0 1 0-1-1a1 1 0 0 0 1 1Zm0-4a1 1 0 1 0-1-1a1 1 0 0 0 1 1Zm-5 0a1 1 0 1 0-1-1a1 1 0 0 0 1 1Zm7-12h-1V2a1 1 0 0 0-2 0v1H8V2a1 1 0 0 0-2 0v1H5a3 3 0 0 0-3 3v14a3 3 0 0 0 3 3h14a3 3 0 0 0 3-3V6a3 3 0 0 0-3-3Zm1 17a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1v-9h16Zm0-11H4V6a1 1 0 0 1 1-1h1v1a1 1 0 0 0 2 0V5h8v1a1 1 0 0 0 2 0V5h1a1 1 0 0 1 1 1ZM7 15a1 1 0 1 0-1-1a1 1 0 0 0 1 1Zm0 4a1 1 0 1 0-1-1a1 1 0 0 0 1 1Z" />
			</symbol>
			<symbol xmlns="http://www.w3.org/2000/svg" id="arrow-left" viewBox="0 0 24 24">
				<path fill="currentColor"
					d="M17 11H9.41l3.3-3.29a1 1 0 1 0-1.42-1.42l-5 5a1 1 0 0 0-.21.33a1 1 0 0 0 0 .76a1 1 0 0 0 .21.33l5 5a1 1 0 0 0 1.42 0a1 1 0 0 0 0-1.42L9.41 13H17a1 1 0 0 0 0-2Z" />
			</symbol>
			<symbol xmlns="http://www.w3.org/2000/svg" id="arrow-right" viewBox="0 0 24 24">
				<path fill="currentColor"
					d="M17.92 11.62a1 1 0 0 0-.21-.33l-5-5a1 1 0 0 0-1.42 1.42l3.3 3.29H7a1 1 0 0 0 0 2h7.59l-3.3 3.29a1 1 0 0 0 0 1.42a1 1 0 0 0 1.42 0l5-5a1 1 0 0 0 .21-.33a1 1 0 0 0 0-.76Z" />
			</symbol>
			<symbol xmlns="http://www.w3.org/2000/svg" id="play" viewBox="0 0 24 24">
				<g fill="none" fill-rule="evenodd">
					<path
						d="M24 0v24H0V0h24ZM12.593 23.258l-.011.002l-.071.035l-.02.004l-.014-.004l-.071-.035c-.01-.004-.019-.001-.024.005l-.004.01l-.017.428l.005.02l.01.013l.104.074l.015.004l.012-.004l.104-.074l.012-.016l.004-.017l-.017-.427c-.002-.01-.009-.017-.017-.018Zm.265-.113l-.013.002l-.185.093l-.01.01l-.003.011l.018.43l.005.012l.008.007l.201.093c.012.004.023 0 .029-.008l.004-.014l-.034-.614c-.003-.012-.01-.02-.02-.022Zm-.715.002a.023.023 0 0 0-.027.006l-.006.014l-.034.614c0 .012.007.02.017.024l.015-.002l.201-.093l.01-.008l.004-.011l.017-.43l-.003-.012l-.01-.01l-.184-.092Z" />
					<path fill="currentColor"
						d="M5.669 4.76a1.469 1.469 0 0 1 2.04-1.177c1.062.454 3.442 1.533 6.462 3.276c3.021 1.744 5.146 3.267 6.069 3.958c.788.591.79 1.763.001 2.356c-.914.687-3.013 2.19-6.07 3.956c-3.06 1.766-5.412 2.832-6.464 3.28c-.906.387-1.92-.2-2.038-1.177c-.138-1.142-.396-3.735-.396-7.237c0-3.5.257-6.092.396-7.235Z" />
				</g>
			</symbol>
			<symbol xmlns="http://www.w3.org/2000/svg" id="category" viewBox="0 0 24 24">
				<path fill="currentColor"
					d="M19 5.5h-6.28l-.32-1a3 3 0 0 0-2.84-2H5a3 3 0 0 0-3 3v13a3 3 0 0 0 3 3h14a3 3 0 0 0 3-3v-10a3 3 0 0 0-3-3Zm1 13a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1v-13a1 1 0 0 1 1-1h4.56a1 1 0 0 1 .95.68l.54 1.64a1 1 0 0 0 .95.68h7a1 1 0 0 1 1 1Z" />
			</symbol>
			<symbol xmlns="http://www.w3.org/2000/svg" id="calendar" viewBox="0 0 24 24">
				<path fill="currentColor"
					d="M19 4h-2V3a1 1 0 0 0-2 0v1H9V3a1 1 0 0 0-2 0v1H5a3 3 0 0 0-3 3v12a3 3 0 0 0 3 3h14a3 3 0 0 0 3-3V7a3 3 0 0 0-3-3Zm1 15a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1v-7h16Zm0-9H4V7a1 1 0 0 1 1-1h2v1a1 1 0 0 0 2 0V6h6v1a1 1 0 0 0 2 0V6h2a1 1 0 0 1 1 1Z" />
			</symbol>
			<symbol xmlns="http://www.w3.org/2000/svg" id="heart" viewBox="0 0 24 24">
				<path fill="currentColor"
					d="M20.16 4.61A6.27 6.27 0 0 0 12 4a6.27 6.27 0 0 0-8.16 9.48l7.45 7.45a1 1 0 0 0 1.42 0l7.45-7.45a6.27 6.27 0 0 0 0-8.87Zm-1.41 7.46L12 18.81l-6.75-6.74a4.28 4.28 0 0 1 3-7.3a4.25 4.25 0 0 1 3 1.25a1 1 0 0 0 1.42 0a4.27 4.27 0 0 1 6 6.05Z" />
			</symbol>
			<symbol xmlns="http://www.w3.org/2000/svg" id="plus" viewBox="0 0 24 24">
				<path fill="currentColor"
					d="M19 11h-6V5a1 1 0 0 0-2 0v6H5a1 1 0 0 0 0 2h6v6a1 1 0 0 0 2 0v-6h6a1 1 0 0 0 0-2Z" />
			</symbol>
			<symbol xmlns="http://www.w3.org/2000/svg" id="minus" viewBox="0 0 24 24">
				<path fill="currentColor" d="M19 11H5a1 1 0 0 0 0 2h14a1 1 0 0 0 0-2Z" />
			</symbol>
			<symbol xmlns="http://www.w3.org/2000/svg" id="cart" viewBox="0 0 24 24">
				<path fill="currentColor"
					d="M8.5 19a1.5 1.5 0 1 0 1.5 1.5A1.5 1.5 0 0 0 8.5 19ZM19 16H7a1 1 0 0 1 0-2h8.491a3.013 3.013 0 0 0 2.885-2.176l1.585-5.55A1 1 0 0 0 19 5H6.74a3.007 3.007 0 0 0-2.82-2H3a1 1 0 0 0 0 2h.921a1.005 1.005 0 0 1 .962.725l.155.545v.005l1.641 5.742A3 3 0 0 0 7 18h12a1 1 0 0 0 0-2Zm-1.326-9l-1.22 4.274a1.005 1.005 0 0 1-.963.726H8.754l-.255-.892L7.326 7ZM16.5 19a1.5 1.5 0 1 0 1.5 1.5a1.5 1.5 0 0 0-1.5-1.5Z" />
			</symbol>
			<symbol xmlns="http://www.w3.org/2000/svg" id="check" viewBox="0 0 24 24">
				<path fill="currentColor"
					d="M18.71 7.21a1 1 0 0 0-1.42 0l-7.45 7.46l-3.13-3.14A1 1 0 1 0 5.29 13l3.84 3.84a1 1 0 0 0 1.42 0l8.16-8.16a1 1 0 0 0 0-1.47Z" />
			</symbol>
			<symbol xmlns="http://www.w3.org/2000/svg" id="trash" viewBox="0 0 24 24">
				<path fill="currentColor"
					d="M10 18a1 1 0 0 0 1-1v-6a1 1 0 0 0-2 0v6a1 1 0 0 0 1 1ZM20 6h-4V5a3 3 0 0 0-3-3h-2a3 3 0 0 0-3 3v1H4a1 1 0 0 0 0 2h1v11a3 3 0 0 0 3 3h8a3 3 0 0 0 3-3V8h1a1 1 0 0 0 0-2ZM10 5a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v1h-4Zm7 14a1 1 0 0 1-1 1H8a1 1 0 0 1-1-1V8h10Zm-3-1a1 1 0 0 0 1-1v-6a1 1 0 0 0-2 0v6a1 1 0 0 0 1 1Z" />
			</symbol>
			<symbol xmlns="http://www.w3.org/2000/svg" id="star-outline" viewBox="0 0 15 15">
				<path fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round"
					d="M7.5 9.804L5.337 11l.413-2.533L4 6.674l2.418-.37L7.5 4l1.082 2.304l2.418.37l-1.75 1.793L9.663 11L7.5 9.804Z" />
			</symbol>
			<symbol xmlns="http://www.w3.org/2000/svg" id="star-solid" viewBox="0 0 15 15">
				<path fill="currentColor"
					d="M7.953 3.788a.5.5 0 0 0-.906 0L6.08 5.85l-2.154.33a.5.5 0 0 0-.283.843l1.574 1.613l-.373 2.284a.5.5 0 0 0 .736.518l1.92-1.063l1.921 1.063a.5.5 0 0 0 .736-.519l-.373-2.283l1.574-1.613a.5.5 0 0 0-.283-.844L8.921 5.85l-.968-2.062Z" />
			</symbol>
			<symbol xmlns="http://www.w3.org/2000/svg" id="search" viewBox="0 0 24 24">
				<path fill="currentColor"
					d="M21.71 20.29L18 16.61A9 9 0 1 0 16.61 18l3.68 3.68a1 1 0 0 0 1.42 0a1 1 0 0 0 0-1.39ZM11 18a7 7 0 1 1 7-7a7 7 0 0 1-7 7Z" />
			</symbol>
			<symbol xmlns="http://www.w3.org/2000/svg" id="user" viewBox="0 0 24 24">
				<path fill="currentColor"
					d="M15.71 12.71a6 6 0 1 0-7.42 0a10 10 0 0 0-6.22 8.18a1 1 0 0 0 2 .22a8 8 0 0 1 15.9 0a1 1 0 0 0 1 .89h.11a1 1 0 0 0 .88-1.1a10 10 0 0 0-6.25-8.19ZM12 12a4 4 0 1 1 4-4a4 4 0 0 1-4 4Z" />
			</symbol>
			<symbol xmlns="http://www.w3.org/2000/svg" id="close" viewBox="0 0 15 15">
				<path fill="currentColor"
					d="M7.953 3.788a.5.5 0 0 0-.906 0L6.08 5.85l-2.154.33a.5.5 0 0 0-.283.843l1.574 1.613l-.373 2.284a.5.5 0 0 0 .736.518l1.92-1.063l1.921 1.063a.5.5 0 0 0 .736-.519l-.373-2.283l1.574-1.613a.5.5 0 0 0-.283-.844L8.921 5.85l-.968-2.062Z" />
			</symbol>
			<symbol xmlns="http://www.w3.org/2000/svg" id="quote" viewBox="0 0 448 512">
				<path fill="currentColor" d="M0 216C0 149.7 53.7 96 120 96h8c17.7 0 32 14.3 32 32s-14.3 32-32 32h-8c-30.9 0-56 25.1-56 56v8h64c35.3 0 64 28.7 64 64v64c0 35.3-28.7 64-64 64H64c-35.3 0-64-28.7-64-64V216zm256 0c0-66.3 53.7-120 120-120h8c17.7 0 32 14.3 32 32s-14.3 32-32 32h-8c-30.9 0-56 25.1-56 56v8h64c35.3 0 64 28.7 64 64v64c0 35.3-28.7 64-64 64h-64c-35.3 0-64-28.7-64-64V216z"/>
			</symbol>
		</defs>
	</svg>

	<div class="nav nav-overlay">
		<div class="nav__content">
			<ul class="nav__list">
				<li class="nav__list-item active-nav"><a href="index.html" class="hover-target"><span class="display-3">Home</span></a></li>
				<li class="nav__list-item"><a href="about.html" class="hover-target"><span class="display-3">About</span></a></li>
							
				
				<li class="nav__list-item"><a href="magazine.html" class="hover-target"><span class="display-3">Challenges</span></a></li>
							
				<li class="nav__list-item"><a href="tools.html" class="hover-target"><span class="display-3">Technology & Tools</span></a></li>
				<li class="nav__list-item"><a href="alternative.html" class="hover-target"><span class="display-3">Alternatives & Solutions</span></a></li>
							
				
			</ul>
		</div>
	</div>

	<header id="header" class="mt-4">
		<div class="container-fluid">
			<a href="index.html" class="logo">
				<img src="images/LOGO.svg" alt="logo">
			</a>
		</div>
	</header>

	<nav id="navbar">
		<input id="menu-toggle" type="checkbox" />
		<label class="menu-btn" for="menu-toggle">
		<span></span>
		</label>
	</nav>

	<section id="billboard" class="py-1 py-md-5">
		<div class="container">
			<div class="row align-items-center">
				<div class="col-md-4">
					<div class="text-content mt-5" data-aos="fade-in">
						<h1 class="display-1 text-uppercase">ENVIRONMENT HEALTH & EDUCATION</h1>
						<a href="https://files.eric.ed.gov/fulltext/ED502021.pdf" class="btn btn-dark px-5 py-3">Read more</a>
					</div>
				</div>
				<div class="col-md-8">
					<figure class="position-relative">
						<img src="images/SAVEPLANET.jpg" class="img-fluid" alt="photographer">
						<figcaption class="bg-white p-1 m-1 p-md-5 m-md-5 col-md-5">Environmental health and education are vital for sustainable living, ensuring a harmonious relationship between humans and their surroundings.
							Through awareness and education, we can mitigate environmental risks and safeguard both public health and the planet.
							</figcaption>
					</figure>
				</div>
			</div>
		</div>
	</section>

	<section id="features" class="py-1 my-1 py-md-5 my-md-5" data-bs-theme="dark">
		<div class="container">
			<div class="row row-cols-1 row-cols-sm-2 row-cols-md-3 row-cols-lg-3 g-5 m-2 m-md-0 p-2 p-md-5 bg-black">
				<div class="col m-0">
				  <div class="mt-3">
					<h4 class="fw-bold mb-2">OUR ABODE</h4>
					<p class="text-white">"The environment is where we all meet; where we all have a mutual interest; it is the one thing all of us share." - Lady Bird Johnson</p>
				  </div>
				</div>
				<div class="col m-0">
				  <div class="mt-3">
					<h4 class="fw-bold mb-2">ENVIRONMENT AS AN ASSET</h4>
					<p class="text-white">"The environment is not a resource; it's an asset that we all share and must protect." - Wangari Maathai</p>
				  </div>
				</div>
				<div class="col m-0">
				  <div class="mt-3">
					<h4 class="fw-bold mb-2">SUSTAINABILITY</h4>
					<p class="text-white">"Sustainability is the key to our future survival on this planet, and will also determine success on all levels." - Shari Arison</p>
				  </div>
				</div>
			  </div>
		  </div>
		</div>
	</section>

	<section id="welcome" class="welcome my-2 my-md-5">
		<div class="container">
			<div class="row">
				<div class="col-md-6 offset-md-3 text-center">
					<h2>CONSERVING WHAT WE HAVE LEFT</h2>
					<p>Preserving our environment today secures a thriving ecosystem for tomorrow's prosperity and well-being. Education about the environment empowers individuals to become stewards of our planet, fostering a sustainable future for all. By conserving habitats, species, and ecosystems, we uphold ecological integrity and promote resilience in the face of environmental challenges.</p>
				</div>
			</div>
		</div>
	</section>

	<section id="about" class="personal-info py-2 py-md-5 overflow-hidden">
		<div class="container">
			<div class="row">
				<div class="col-md-7">
					<figure data-aos="slide-right">
						<img src="images/PLASTICOCEAN.jpg" class="img-fluid" alt="Beauty">
					</figure>
				</div>
				<div class="col-md-5">
					<div class="m-2 p-2 m-md-5 p-md-5" data-aos="slide-left">
						<h2 class="display-1 text-uppercase">HEALTHY ENVIRONMENT</h2>
						<p>Environmental health focuses on the interplay between human health and the quality of our surroundings, striving for a safe and sustainable environment for all. Ensuring environmental health involves addressing factors such as air and water quality, sanitation, and hazardous waste management to protect both human well-being and the ecosystems we depend on.</p>
						<a href="https://iris.who.int/bitstream/handle/10665/325877/WHO-CED-PHE-DO-19.01-eng.pdf?sequence=1" class="btn btn-dark px-5 py-3">READ MORE</a>
					</div>
				</div>
			</div>
		</div>
	</section>

	<section id="services" class="personal-info py-2 py-md-5 overflow-hidden">
		<div class="container">
			<div class="row">
				<div class="col-md-5">
					<div class="m-2 p-2 m-md-5 p-md-5" data-aos="slide-right">
						<h2 class="display-1 text-uppercase">EDUCATION & AWARENESS</h2>
						<p>Education and awareness about our environment are essential for fostering a culture of <a href="https://earth.org/environmental-education/"><u>sustainability</u></a>, encouraging informed decisions, and promoting responsible stewardship of our planet. By increasing understanding and consciousness about environmental issues, we empower individuals and communities to take proactive steps towards preserving and restoring the health of our ecosystems.</p>
						<a href="https://sustainabledevelopment.un.org/content/documents/926unesco9.pdf" class="btn btn-dark px-5 py-3">READ MORE</a>
					</div>
				</div>
				<div class="col-md-7">
					<figure data-aos="slide-left">
						<img src="images/SDG.png" class="img-fluid" alt="Beauty">
					</figure>
				</div>
			</div>
		</div>
	</section>

	<section class="testimonials py-5">
		<div class="container">
			<div class="row">
				<div class="section-header text-center my-5">
					<h3 class="display-1 text-uppercase">DIVE DEEPER</h3>
				</div>
			</div>
			<div class="row">
				<div class="col-md-4">
					<div class="testimonial-item">
						<blockquote>
							<svg class="text-primary" width="24" height="24" viewBox="0 0 24 24">
								<use xlink:href="#quote"></use>
							</svg>
							<H2>CHALLENGES</H2>
							<p class="fs-5">“Challenges to maintaining a healthy environment include pollution, habitat destruction, climate change, and unsustainable resource use, all of which require collective action and innovative solutions to address effectively.”</p>
							<div class="review-title"><a href="magazine.html" class="btn btn-dark px-5 py-3">LEARN</a></div>
							<div class="review-desc text-muted"></div>
						</blockquote>
					</div>
				</div>
				<div class="col-md-4">
					<div class="testimonial-item">
						<blockquote>
							<svg class="text-primary" width="24" height="24" viewBox="0 0 24 24">
								<use xlink:href="#quote"></use>
							</svg>
							<H2>TECHNOLOGIES & TOOLS</H2>
							<p class="fs-5">"Advanced tools and technologies, such as AI-driven sensors and remote sensing, enable real-time monitoring of environmental health. These innovations also support environmental education efforts by providing interactive platforms and data visualization tools."
								</p>
							<div class="review-title"><a href="tools.html" class="btn btn-dark px-5 py-3">EXPLORE</a></div>
							<div class="review-desc text-muted"></div>
						</blockquote>
					</div>
				</div>
				<div class="col-md-4">
					<div class="testimonial-item">
						<blockquote>
							<svg class="text-primary" width="24" height="24" viewBox="0 0 24 24">
								<use xlink:href="#quote"></use>
							</svg>
							<H2>ALTERNATIVES & SOLUTIONS</H2>
							<p class="fs-5">"Transitioning to renewable energy sources such as solar, wind, and hydroelectric power offers a cleaner and healthier alternative to fossil fuels, reducing air and water pollution while mitigating climate change impacts."






							</p>
							<div class="review-title"><a href="alternative.html" class="btn btn-dark px-5 py-3">READ</a></div>
							<div class="review-desc text-muted"></div>
						</blockquote>
					</div>
				</div>
			</div>
		</div>
	</section>

	<section id="blog" class="latest-blogs py-2 py-md-5">
		<div class="container-fluid">

			<div class="row">
				<div class="col-md-4 pb-5">
					<div class="post-content mb-3">
						<div class="meta-tags text-uppercase text-gray d-flex gap-2 fs-6 mb-2 align-items-center">
							<span class="meta-date">EARTH</span>
							<span>:</span>
							<span class="meta-category"><a href="https://education.nationalgeographic.org/resource/conserving-earth/">The Beautiful Planet</a></span>
						</div>
						<h3 class="post-title mb-2"><a href="https://sdgs.un.org/sites/default/files/documents/3792UNEP%2520Post%25202015%2520Note%2520%25233%2520Health.pdf">The Dark Side</a></h3>
						<p>The future holds dark prospects for both the environment and humanity due to ongoing environmental degradation. Without immediate and concerted action, we face worsening disasters.</p>
					</div>
					<div class="post-thumbnail">
						<img src="images/POLLUTION.jpg" alt="Post" class="img-fluid">
					</div>
				</div><!--post-item-->

				<div class="col-md-4 pb-5">
					<div class="post-thumbnail">
						<img src="images/ENVHEALTH.jpg" alt="Post" class="img-fluid">
					</div>
					<div class="post-content mb-3">
						<div class="meta-tags text-uppercase text-gray d-flex gap-2 fs-6 mb-2 mt-3 align-items-center">
							<span class="meta-date">Waking UP</span>
							<span>:</span>
							<span class="meta-category"><a href="https://www.unep.org/news-and-stories/story/wake-call-humanity-qa-climate-expert-ipcc-report">A Call That Must Be Taken</a></span>
						</div>
						<h3 class="post-title mb-2"><a href="https://theconversation.com/us/topics/environment-3387">Research and Analysis</a>
						</h3>
						<p>Field focuses on investigating how environmental factors such as air and water quality, pollution, climate change, and biodiversity loss impact human health and well-being.</p>
					</div>
					<div class="post-thumbnail">
						<img src="images/CLIMATECHANGE.png" alt="Post" class="img-fluid">
					</div>
				</div><!--post-item-->

				<div class="col-md-4 pb-5">
					<div class="post-content mb-3">
						<div class="meta-tags text-uppercase text-gray d-flex gap-2 fs-6 mb-2 align-items-center">
							<span class="meta-date">START-UPS</span>
							<span>:</span>
							<span class="meta-category"><a href="https://www.trvst.world/environment/famous-environmentalists/"></a>INSPIRATION TO ALL</span>
						</div>
						<div class="post-thumbnail">
							<img src="images/HONEYWELL.jpg" alt="Post" class="img-fluid">
						</div>
						<h3 class="post-title mb-2"><a href="https://www.nature.org/en-us/what-we-do/our-insights/perspectives/the-science-of-sustainability/">A Promising Future</a>
						</h3>
						<p>By prioritizing environmental health and education, we pave the way for a thriving future where both human health and the environment are safeguarded and respected.</p>
					</div>
					<div class="post-thumbnail">
						<img src="images/UNICEF.jpg" alt="Post" class="img-fluid">
					</div>
					<div class="post-thumbnail">
						<img src="images/STARTUP.jpg" alt="Post" class="img-fluid">
					</div>
				</div><!--post-item-->

			</div><!--post-content-->
		
		</div>
	</section>

	<section class="bg-secondary py-5">
		<div class="container">
			
			<div class="row">
				
				
				<div class="col-md-8 offset-md-2">
					<div class="row">
				
						<div class="col-md-8">
				
							<h3>DONATE US</h3>
							<p class="text-muted">Help us make a difference. Donate today and join us in our mission to create a better home.Every contribution counts!</p>
						</div>
						<div class="col-md-4">

							<a href="#" class="btn btn-dark px-5 py-3">DONATE</a>
							
						</div>
					</div>
				</div>
				
			</div>
		</div>
	</section>

	<footer id="footer" class="bg-black pt-5" data-bs-theme="dark">
		<div class="container">

			<div class="row">
				<div class="col-6 col-md-2">
					<div class="footer-menu">
						<h5 class="widget-title mb-4">Quick Links</h5>
						<ul class="menu-list list-unstyled fs-6">
							<li class="menu-item">
								<a href="index.html" class="item-anchor">Home</a>
							</li>
							
							<li class="menu-item">
								<a href="https://www.greenindustrypros.com/industry-updates/article/22884666/state-of-the-green-industry-2024-trends" class="item-anchor">Green Industry</a>
							</li>
							<li class="menu-item">
								<a href="https://enterpriseleague.com/blog/environmental-startups/" class="item-anchor">START-UPS</a>
							</li>
							<li class="menu-item">
								<a href="https://earth.org/home/" class="item-anchor">News & Updates</a>
							</li>
						</ul>
					</div>
				</div>
				<div class="col-6 col-md-2">
					<div class="footer-menu">
						<h5 class="widget-title mb-4">About</h5>
						<ul class="menu-list list-unstyled fs-6">
							<li class="menu-item">
								<a href="https://youtu.be/jAa58N4Jlos?si=OK1vg6uFvjHERsF5" class="item-anchor">YouTube Video: Climate change</a>
							</li>
							<li class="menu-item">
								<a href="about.html" class="item-anchor">About us</a>
							</li>
							
							<li class="menu-item">
								<a href="https://youtu.be/QQYgCxu988s?si=9Tqx4STrtdOsosPq" class="item-anchor">Promotions</a>
							</li>
							
						</ul>
					</div>
				</div>
				<div class="col-6 col-md-2">
					<div class="footer-menu">
						<h5 class="widget-title mb-4">Help & Info</h5>
						<ul class="menu-list list-unstyled fs-6">
							
							
							
							<li class="menu-item">
								<a href="https://online.ucpress.edu/cse" class="item-anchor">Case Studies</a>
							</li>
							<li class="menu-item">
								<a href="#" class="item-anchor">Credits</a>
							</li>
							<li class="menu-item">
								<a href="https://www.theworldcounts.com/stories/environmental-facts-and-statistics" class="item-anchor">Facts & Statistics</a>
							</li>
						</ul>
					</div>
				</div>
				<div class="col-md-4 offset-md-2 text-start text-md-end">
					<div class="mb-4">
						<a href="index.html">
							<a href="index.html" ><h1>GO GREEN</h1></a>
							<img src="" alt="">
						</a>
					</div>
					<p>Let's paint the world green with actions, not just words. Embrace sustainability; it's the key to our planet's resilience and our future prosperity. "He that plants trees loves others beside himself."</p>

					<ul class="list-unstyled">
						<li><a href="mailto:contact@yourwebsite.com">contact@yourwebsite.com</a></li>
						<li>0182 451 7222</li>
						<li>LOVELY PROFESSIONAL UNIVERSITY, GRAND TRUNK ROAD</li>
						<li>144001, JALANDHAR, PUNJAB</li>
					</ul>

					<div class="social-links">
						<ul class="list-unstyled d-flex justify-content-start justify-content-md-end flex-wrap gap-3">
							<li>
								<a href="#" class="text-secondary">
									<svg width="24" height="24" viewBox="0 0 24 24">
										<use xlink:href="#facebook"></use>
									</svg>
								</a>
							</li>
							<li>
								<a href="#" class="text-secondary">
									<svg width="24" height="24" viewBox="0 0 24 24">
										<use xlink:href="#twitter"></use>
									</svg>
								</a>
							</li>
							<li>
								<a href="#" class="text-secondary">
									<svg width="24" height="24" viewBox="0 0 24 24">
										<use xlink:href="#youtube"></use>
									</svg>
								</a>
							</li>
							<li>
								<a href="#" class="text-secondary">
									<svg width="24" height="24" viewBox="0 0 24 24">
										<use xlink:href="#pinterest"></use>
									</svg>
								</a>
							</li>
							<li>
								<a href="#" class="text-secondary">
									<svg width="24" height="24" viewBox="0 0 24 24">
										<use xlink:href="#instagram"></use>
									</svg>
								</a>
							</li>
						</ul>
					</div>
				</div>
			</div>

			<div class="border-top py-4">
				<div class="row">
					<div class="col-md-6">
						<p>© Copyright 2024 GREENIFY. All rights reserved.</p>
					</div>
					<div class="col-md-6 text-start text-md-end">
						<p>Desinged by Team GREENIFY</p>
						
					</div>
				</div>
			</div>

		</div>
	</footer>

	<script src="js/jquery-1.11.0.min.js"></script>
	<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/js/bootstrap.bundle.min.js"
		integrity="sha384-HwwvtgBNo3bZJJLYd8oVXjrBZt8cqVSpeBNS5n7C8IVInixGAoxmnlMuBnhbgrkm"
		crossorigin="anonymous"></script>
	<script type="text/javascript" src="js/plugins.js"></script>
	<script type="text/javascript" src="js/script.js"></script>

</body>

</html>
