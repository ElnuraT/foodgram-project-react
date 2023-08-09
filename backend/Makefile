ifneq (,$(wildcard ./.env))
    include .env
    export
endif
run_gunicorn:
	gunicorn --bind 0.0.0.0:${NGINX_PORT} foodgram.wsgi