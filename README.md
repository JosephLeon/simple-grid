This is a super simple and light-weight sass grid system.

Ex:

	.main-col {
		@include container;
	}

	.main {
		@include grid(8, 1);
	}

	.right-col {
		@include grid(9, 4)
	}
