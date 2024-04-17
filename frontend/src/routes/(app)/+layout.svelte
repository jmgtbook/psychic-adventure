<script>
	import { goto } from '$app/navigation';
    const gotoMypage = () => {
        goto('/mypage');
    };
	const gotoCheckchek = () => {
        goto('/checkchek');
    };
</script>

<header class="header">
	<div class="home-header">
		<div class="header">
			<div class="header-1">
				<div class="li-header-1">
					<a href="/login" class="div">로그인</a>
					<a href="/home" class="div2">회원가입</a>
					<a href="/home" class="div2">장바구니</a>
					<a href="/mypage" class="div3">마이페이지</a>
					<a href="/home" class="div2">문의하기</a>
				</div>
			</div>
			<div class="header-2">
				<div class="box-header-2">
					<button on:click={gotoCheckchek} class="button-checkchek">
						<svg
							class="box-checkchek"
							width="29"
							height="36"
							viewBox="0 0 29 36"
							fill="none"
							xmlns="http://www.w3.org/2000/svg"
						>
							<path
								d="M13.3645 24.3536L2 32.1912V2H27V32.1912L15.6355 24.3536L14.5 23.5705L13.3645 24.3536Z"
								fill="white"
								stroke="black"
								stroke-width="4"
							/>
						</svg>
					</button>
					<a href="/home" class="chek">CHEK</a>
					<article class="line-7"></article>
					<button class="button-totalsearch">
						<div class="div6">통합검색</div>
						<svg
							class="totalsearchimg"
							width="24"
							height="24"
							viewBox="0 0 24 24"
							fill="none"
							xmlns="http://www.w3.org/2000/svg"
						>
							<path
								fill-rule="evenodd"
								clip-rule="evenodd"
								d="M7.28577 9.29289C7.67591 8.90237 8.30845 8.90237 8.6986 9.29289L11.9883 12.5858L15.2779 9.29289C15.6681 8.90237 16.3006 8.90237 16.6907 9.29289C17.0809 9.68342 17.0809 10.3166 16.6907 10.7071L12.6947 14.7071C12.3045 15.0976 11.672 15.0976 11.2818 14.7071L7.28577 10.7071C6.89563 10.3166 6.89563 9.68342 7.28577 9.29289Z"
								fill="black"
							/>
						</svg>
					</button>
					<button class="button-search">
						<svg
							class="icon-search"
							width="36"
							height="36"
							viewBox="0 0 36 36"
							fill="none"
							xmlns="http://www.w3.org/2000/svg"
						>
							<g clip-path="url(#clip0_70_424)">
								<path
									fill-rule="evenodd"
									clip-rule="evenodd"
									d="M14.6642 0C6.56537 0 0 6.49302 0 14.5026C0 22.5121 6.56537 29.0051 14.6642 29.0051C17.958 29.0051 20.9982 27.9311 23.4462 26.1179L32.2961 35.3932C33.1142 36.2023 34.533 36.2023 35.3511 35.3932C36.1692 34.5841 36.1692 33.1809 35.3511 32.3718L26.4089 23.1879C28.2423 20.7668 29.3283 17.7601 29.3283 14.5026C29.3283 6.49302 22.7629 0 14.6642 0ZM4.18976 14.5026C4.18976 8.78147 8.87931 4.14359 14.6642 4.14359C20.449 4.14359 25.1386 8.78147 25.1386 14.5026C25.1386 20.2237 20.449 24.8616 14.6642 24.8616C8.87931 24.8616 4.18976 20.2237 4.18976 14.5026Z"
									fill="black"
								/>
							</g>
							<defs>
								<clipPath id="clip0_70_424">
									<rect width="35.9647" height="36" fill="white" />
								</clipPath>
							</defs>
						</svg>
					</button>
					<button on:click={gotoMypage} class="button-mypage">
						<svg
							class="icon-mypage"
							width="36"
							height="36"
							viewBox="0 0 36 36"
							fill="none"
							xmlns="http://www.w3.org/2000/svg"
						>
							<path
								d="M30.6 33H30.57M30.57 33H5.4C4.08 33 3 31.92 3 30.6V25.125C3 24.75 3 24.555 3.18 24.195C3.75 22.875 5.43 21.765 8.055 20.82M30.57 33C31.89 33 32.97 31.92 32.97 30.6V25.125C32.97 24.765 32.97 24.375 32.79 24.195C32.235 22.89 30.54 21.75 27.915 20.82M18 20.25C13.875 20.25 10.5 16.875 10.5 12.75V10.5C10.5 6.375 13.875 3 18 3C22.125 3 25.5 6.375 25.5 10.5V12.75C25.5 16.875 22.125 20.25 18 20.25Z"
								stroke="black"
								stroke-width="4"
								stroke-linecap="round"
								stroke-linejoin="round"
							/>
						</svg>
					</button>
					<div class="box-inputsearch">
						<input class="input-search" placeholder="검색어를 입력하세요" />
					</div>
				</div>
			</div>
		</div>
		<div class="nav-1">
			<div class="box-nav-1">
				<div class="box-category">
					<svg
						class="si-align-justify"
						width="24"
						height="25"
						viewBox="0 0 24 25"
						fill="none"
						xmlns="http://www.w3.org/2000/svg"
					>
						<path
							d="M3 5.5C2.44772 5.5 2 5.94772 2 6.5C2 7.05228 2.44772 7.5 3 7.5H21C21.5523 7.5 22 7.05228 22 6.5C22 5.94772 21.5523 5.5 21 5.5H3Z"
							fill="black"
						/>
						<path
							d="M3 9.5C2.44772 9.5 2 9.94772 2 10.5C2 11.0523 2.44772 11.5 3 11.5H21C21.5523 11.5 22 11.0523 22 10.5C22 9.94772 21.5523 9.5 21 9.5H3Z"
							fill="black"
						/>
						<path
							d="M2 14.5C2 13.9477 2.44772 13.5 3 13.5H21C21.5523 13.5 22 13.9477 22 14.5C22 15.0523 21.5523 15.5 21 15.5H3C2.44772 15.5 2 15.0523 2 14.5Z"
							fill="black"
						/>
						<path
							d="M3 17.5C2.44772 17.5 2 17.9477 2 18.5C2 19.0523 2.44772 19.5 3 19.5H21C21.5523 19.5 22 19.0523 22 18.5C22 17.9477 21.5523 17.5 21 17.5H3Z"
							fill="black"
						/>
					</svg>
					<a href="/home" class="category">CATEGORY</a>
				</div>
				<svg
					class="box-line-9"
					width="1"
					height="24"
					viewBox="0 0 1 24"
					fill="none"
					xmlns="http://www.w3.org/2000/svg"
				>
					<line x1="-0.5" y1="23.5974" x2="-0.5" y2="0.402586" stroke="black" stroke-width="2" />
				</svg>
				<a href="/home" class="home">HOME</a>
				<a href="/chekbook" class="chekbook">CHEKBOOK</a>
				<a href="/home" class="univsell">UNIVSELL</a>
				<a href="/home" class="locker">LOCKER</a>
			</div>
		</div>
	</div>
</header>

<slot />

<footer class="layout-footer"></footer>

<style>
	a {
		text-decoration-line: none;
	}
	button {
		background-color: rgba(255, 255, 255, 0);
		border: rgba(255, 255, 255, 0);
	}
	.home-header,
	.home-header * {
		box-sizing: border-box;
	}
	.home-header {
		display: flex;
		flex-direction: column;
		gap: 0rem;
		align-items: flex-start;
		justify-content: flex-start;
		height: 11.125rem;
		position: relative;
	}
	.header {
		display: flex;
		flex-direction: column;
		gap: 0rem;
		align-items: flex-start;
		justify-content: flex-start;
		flex-shrink: 0;
		width: 120rem;
		position: relative;
	}
	.header-1 {
		padding: 0rem 25rem 0rem 25rem;
		display: flex;
		flex-direction: column;
		gap: 0.625rem;
		align-items: flex-end;
		justify-content: flex-end;
		flex-shrink: 0;
		width: 120rem;
		height: 1.5625rem;
		position: relative;
	}
	.li-header-1 {
		display: flex;
		flex-direction: row;
		gap: 1.25rem;
		align-items: center;
		justify-content: flex-end;
		flex-shrink: 0;
		position: relative;
	}
	.div {
		color: #000000;
		text-align: center;
		font-family: 'Itim-Regular', sans-serif;
		font-size: 0.6875rem;
		line-height: 2.5625rem;
		font-weight: 400;
		position: relative;
		width: 2.0625rem;
		height: 1.25rem;
		display: flex;
		align-items: center;
		justify-content: center;
	}
	.div2 {
		color: #000000;
		text-align: center;
		font-family: 'Itim-Regular', sans-serif;
		font-size: 0.6875rem;
		line-height: 2.5625rem;
		font-weight: 400;
		position: relative;
		width: 2.75rem;
		height: 1.25rem;
		display: flex;
		align-items: center;
		justify-content: center;
	}
	.div3 {
		color: #000000;
		text-align: center;
		font-family: 'Itim-Regular', sans-serif;
		font-size: 0.6875rem;
		line-height: 2.5625rem;
		font-weight: 400;
		position: relative;
		width: 3.4375rem;
		height: 1.25rem;
		display: flex;
		align-items: center;
		justify-content: center;
	}
	.header-2 {
		display: flex;
		flex-direction: column;
		gap: 0.625rem;
		align-items: flex-start;
		justify-content: flex-end;
		flex-shrink: 0;
		width: 120rem;
		height: 4.0625rem;
		position: relative;
	}
	.box-header-2 {
		background: rgba(255, 255, 255, 0);
		flex-shrink: 0;
		width: 120rem;
		height: 3.3125rem;
		position: relative;
		overflow: hidden;
	}
	.button-checkchek {
		padding: 0.3125rem 0.625rem 0.3125rem 0.625rem;
		display: flex;
		flex-direction: row;
		gap: 0.625rem;
		align-items: flex-start;
		justify-content: flex-start;
		width: 3.125rem;
		height: 3.125rem;
		position: absolute;
		left: 92.5rem;
		top: 0rem;
	}
	.box-checkchek {
		display: flex;
		flex-direction: row;
		gap: 0.625rem;
		align-items: center;
		justify-content: center;
		flex-shrink: 0;
		width: 1.8125rem;
		height: 2.25rem;
		position: relative;
		overflow: visible;
	}
	.button-checkchek:hover{
		box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
	}
	.chek {
		color: #000000;
		letter-spacing: 0.625rem;
		text-align: center;
		font-family: 'Inika', sans-serif;
		font-size: 2.25rem;
		line-height: 2.5625rem;
		font-weight: 700;
		position: absolute;
		left: 22.25rem;
		top: 0rem;
		width: 8.75rem;
		height: 3.3125rem;
		display: flex;
		align-items: center;
		justify-content: center;
	}
	.line-7 {
		border-style: solid;
		border-color: #000000;
		border-width: 0.25rem 0 0 0;
		width: 44.27%;
		height: 0%;
		position: absolute;
		right: 27.6%;
		left: 28.12%;
		bottom: 7.55%;
		top: 92.45%;
		transform-origin: 0 0;
		transform: rotate(0deg) scale(1, 1);
	}
	.button-totalsearch {
		padding: 0rem 0.3125rem 0rem 0.3125rem;
		display: flex;
		flex-direction: row;
		gap: 0rem;
		align-items: center;
		justify-content: flex-start;
		height: 1.875rem;
		position: absolute;
		left: 34.1875rem;
		top: 0.625rem;
	}
	.div6 {
		color: #000000;
		text-align: center;
		font-family: 'Inika', sans-serif;
		font-size: 1.25rem;
		line-height: 2.5625rem;
		font-weight: 700;
		position: relative;
		width: 5.375rem;
		height: 1.875rem;
		display: flex;
		align-items: center;
		justify-content: center;
	}
	.totalsearchimg {
		flex-shrink: 0;
		width: 1.49875rem;
		height: 1.5rem;
		position: relative;
		overflow: visible;
	}
	.button-search {
		padding: 0.625rem;
		display: flex;
		flex-direction: row;
		gap: 0.625rem;
		align-items: flex-end;
		justify-content: flex-start;
		width: 3.3125rem;
		height: 3.125rem;
		position: absolute;
		left: 83.5625rem;
		top: 0rem;
	}
	.icon-search {
		flex-shrink: 0;
		width: 2.2475rem;
		height: 2.25rem;
		position: relative;
		overflow: visible;
	}
	.button-mypage {
		padding: 0.625rem;
		display: flex;
		flex-direction: row;
		gap: 0.625rem;
		align-items: flex-end;
		justify-content: center;
		width: 3.125rem;
		height: 3.125rem;
		position: absolute;
		left: 88.25rem;
		top: 0rem;
	}
	.button-mypage:hover{
		box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
	}
	.icon-mypage {
		flex-shrink: 0;
		width: 2.25rem;
		height: 2.25rem;
		position: relative;
		overflow: visible;
	}

	.box-inputsearch {
		display: flex;
		flex-direction: column;
		gap: 0rem;
		align-items: center;
		justify-content: center;
		width: 41.8125rem;
		height: 2.8125rem;
		position: absolute;
		left: 41.75rem;
		top: 0rem;
	}
	.input-search {
		color: #333232;
		text-align: left;
		font-family: 'Inter-Regular', sans-serif;
		font-size: 1.25rem;
		font-weight: 700;
		position: relative;
		width: 41.8125rem;
		height: 2.8125rem;
		display: flex;
		align-items: center;
		justify-content: flex-start;
		border: none;
	}

	.input-search:focus {
		outline: none;
	}
	.input-search::placeholder {
		color: rgba(0, 0, 0, 0.2);
		border: none;
	}
	.input-search:focus::placeholder {
		color: transparent;
	}
	.nav-1 {
		padding: 0rem 22.5rem 0rem 22.5rem;
		display: flex;
		flex-direction: row;
		gap: 0.625rem;
		align-items: center;
		justify-content: flex-start;
		flex-shrink: 0;
		width: 120rem;
		height: 5rem;
		position: relative;
	}
	.box-nav-1 {
		padding: 0.0625rem 0rem 0.0625rem 0rem;
		display: flex;
		flex-direction: row;
		gap: 1.5625rem;
		align-items: center;
		justify-content: flex-start;
		flex-shrink: 0;
		width: 36.9375rem;
		height: 1.6875rem;
		position: relative;
	}
	.box-category {
		padding: 0rem 0rem 0.0625rem 0rem;
		display: flex;
		flex-direction: row;
		gap: 0.4375rem;
		align-items: center;
		justify-content: center;
		flex-shrink: 0;
		position: relative;
	}
	.si-align-justify {
		flex-shrink: 0;
		width: 1.5rem;
		height: 1.5rem;
		position: relative;
		overflow: visible;
	}
	.category {
		color: #000000;
		text-align: center;
		font-family: 'Inika', sans-serif;
		font-size: 1rem;
		line-height: 2.5625rem;
		font-weight: 700;
		position: relative;
		width: 5.875rem;
		height: 0.875rem;
		display: flex;
		align-items: center;
		justify-content: center;
	}
	.box-line-9 {
		display: flex;
		flex-direction: row;
		align-items: center;
		justify-content: space-between;
		flex-shrink: 0;
		width: 0.0625rem;
		height: auto;
		position: relative;
		overflow: visible;
	}
	.home {
		color: #000000;
		text-align: center;
		font-family: 'Inika', sans-serif;
		font-size: 1rem;
		line-height: 2.5625rem;
		font-weight: 700;
		position: relative;
		width: 3.375rem;
		height: 0.875rem;
		display: flex;
		align-items: center;
		justify-content: center;
	}
	.chekbook {
		color: #000000;
		text-align: center;
		font-family: 'Inika', sans-serif;
		font-size: 1rem;
		line-height: 2.5625rem;
		font-weight: 700;
		position: relative;
		width: 6.125rem;
		height: 0.875rem;
		display: flex;
		align-items: center;
		justify-content: center;
	}
	.univsell {
		color: #000000;
		text-align: center;
		font-family: 'Inika', sans-serif;
		font-size: 1rem;
		line-height: 2.5625rem;
		font-weight: 700;
		position: relative;
		width: 5.875rem;
		height: 0.875rem;
		display: flex;
		align-items: center;
		justify-content: center;
	}
	.locker {
		color: #000000;
		text-align: center;
		font-family: 'Inika', sans-serif;
		font-size: 1rem;
		line-height: 2.5625rem;
		font-weight: 700;
		position: relative;
		width: 4.375rem;
		height: 0.875rem;
		display: flex;
		align-items: center;
		justify-content: center;
	}
</style>
