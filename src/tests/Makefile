tests: youtube_fetch_test

youtube_fetch_test: youtube_fetch.test.c ../discord-in-c/youtube_fetch.c
	@gcc -o youtube_fetch.test youtube_fetch.test.c ../discord-in-c/youtube_fetch.h ../discord-in-c/youtube_fetch.c ../discord-in-c/cJSON.h ../discord-in-c/cJSON.c -g -pedantic -lcurl -fsanitize=address
	@./youtube_fetch.test