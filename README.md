# Build

	docker build -t dod91/docker-nginx-spdy .

# Run
# docker run --rm -ti --net host -v $(pwd)/sites-enabled:/etc/nginx/sites-enabled dgageot/ngxpagespeed