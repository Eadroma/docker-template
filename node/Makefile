down:
	docker compose down --remove-orphans -v

up:
	docker compose up -d app

shell:
	docker compose exec app sh

start: 
	make --no-print-directory down
	make --no-print-directory up
	# docker compose exec app npm install
	make --no-print-directory shell

stop: down